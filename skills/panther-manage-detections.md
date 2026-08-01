---
name: Manage Panther detection rules
description: Create, read, update, and delete Panther detection rules as code via the REST API.
api: openapi/panther-rest-openapi.yml
operations: [rule#list, rule#get, rule#create, rule#put, rule#delete]
---

# Manage Panther detection rules

Manage Panther's Python detection rules programmatically. Requires an API token
with `RuleRead` and `RuleModify` permissions; send `X-API-Key: <token>`.

## Steps
1. **List rules** — `GET /rules` (`rule#list`), cursor-paginated
   (`{ results, next }`).
2. **Fetch one** — `GET /rules/{id}` (`rule#get`).
3. **Create a rule** — `POST /rules` (`rule#create`) with the rule body
   (id, displayName, enabled, severity, body/Python, logTypes, tests).
4. **Update a rule** — `PUT /rules/{id}` (`rule#put`) with the full replacement
   object. A create against an existing id returns `409 exists`.
5. **Delete a rule** — `DELETE /rules/{id}` (`rule#delete`).

## Related resources
Same shape applies to `/simple-rules`, `/scheduled-rules`, `/correlation-rules`,
`/policies`, `/data-models`, and `/globals`. For bulk detections-as-code,
prefer the `panther_analysis_tool` CLI (`pip install panther_analysis_tool`).

## Rules
- Validate before upload; malformed bodies return `400 bad_request` with `{ message }`.
- No idempotency-key contract — treat create/PUT as non-replay-safe.
