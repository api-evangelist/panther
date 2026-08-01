---
name: Triage a Panther alert
description: List, inspect, comment on, and update the status of security alerts in a Panther instance.
api: openapi/panther-rest-openapi.yml
operations: [alert#list, alert#get, alert#events, comment#create, alert#patch]
---

# Triage a Panther alert

Operate the Panther REST API to work an alert queue. Base host is your per-instance
`api.<your-panther-host>`; on Cloud Connected / self-hosted, prefix paths with `/v1`.

## Auth
Every request sends the header `X-API-Key: <token>`. The token needs the
`AlertRead` and `AlertModify` permissions.

## Steps
1. **List open alerts** — `GET /alerts` (operationId `alert#list`). Page with the
   `cursor` query param; the response is `{ results: [...], next: <cursor> }`.
   Loop while `next` is non-empty.
2. **Inspect one alert** — `GET /alerts/{id}` (`alert#get`) for full detail, and
   `GET /alerts/{id}/events` (`alert#events`) to pull the triggering events.
3. **Comment your findings** — `POST /alert-comments` (`comment#create`) with the
   `alert-id` and comment body.
4. **Update status** — `PATCH /alerts/{id}` (`alert#patch`) to set status
   (e.g. TRIAGED, RESOLVED) and assignee. To act on many at once use
   `PATCH /alerts` (`alert#bulkPatch`).

## Rules
- Errors return `{ "message": "..." }` — not RFC 9457. Handle 400/403/404/409.
- There is no idempotency-key header; do not blindly retry non-GET calls on timeout —
  re-fetch the alert to confirm state first.
