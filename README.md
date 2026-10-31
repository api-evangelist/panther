# Panther

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Panther is a cloud-native, code-driven detection and response platform and AI-powered SOC that ingests and normalizes security logs at petabyte scale into a security data lake (customer-connected AWS/Snowflake/Databricks or Panther-hosted). It offers Python detection-as-code, AI-generated detections, correlation and scheduled rules, cloud-security policies, and an AI SOC agent that auto-triages and investigates alerts. Developers automate it through a REST API (X-API-Key), a GraphQL API, Terraform, the panther_analysis_tool CLI, and official local and remote MCP servers. Backed by ICONIQ Capital and Lightspeed Venture Partners.

**Areas:** Company · Security · SIEM · Detection and Response · Security Operations · Threat Detection · Log Management · Data Lake · Cloud Security · Developer Tools

## Panther on APIs.io

Everything profiled for Panther is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/panther/](https://apis.io/providers/panther/)** — or go straight to one of the APIs or properties below.

### APIs (21)

- [Panther Alert API](https://apis.io/apis/panther/panther-alert-api/) — The alert api handles all operations for alerts
- [Panther api token API](https://apis.io/apis/panther/panther-api-token-api/) — The api token api handles all operations for api tokens
- [Panther aws cloud account API](https://apis.io/apis/panther/panther-aws-cloud-account-api/) — The AWS Cloud Account API handles all operations for AWS Cloud Account scanner integrations
- [Panther Comment API](https://apis.io/apis/panther/panther-comment-api/) — The comment api handles all operations for alerts comments
- [Panther Contexttag API](https://apis.io/apis/panther/panther-contexttag-api/) — The context tag API handles all operations for alert context tags
- [Panther correlation rule API](https://apis.io/apis/panther/panther-correlation-rule-api/) — The correlation rule api handles all operations for correlation rules
- [Panther data model API](https://apis.io/apis/panther/panther-data-model-api/) — The data model api handles all operations for data models
- [Panther gcs source API](https://apis.io/apis/panther/panther-gcs-source-api/) — The GCS source API handles all operations for Google Cloud Storage log sources
- [Panther Global API](https://apis.io/apis/panther/panther-global-api/) — The global api handles all operations for globals
- [Panther http source API](https://apis.io/apis/panther/panther-http-source-api/) — The http source api handles all operations for http sources
- [Panther log forwarder source API](https://apis.io/apis/panther/panther-log-forwarder-source-api/) — The log forwarder source api handles all operations for log forwarder sources
- [Panther log source alarm API](https://apis.io/apis/panther/panther-log-source-alarm-api/) — Manage the drop-off alarm (SOURCE_NO_DATA) for log source integrations. Other alarm types shown in the Panther UI (permissions checks, classification…
- [Panther Policy API](https://apis.io/apis/panther/panther-policy-api/) — The policy api handles all operations for policies
- [Panther pub/sub source API](https://apis.io/apis/panther/panther-pub-sub-source-api/) — The Pub/Sub source API handles all operations for GCP Pub/Sub log sources
- [Panther Query API](https://apis.io/apis/panther/panther-query-api/) — The query api handles operations for queries
- [Panther Role API](https://apis.io/apis/panther/panther-role-api/) — The role api handles all operations for roles
- [Panther Rule API](https://apis.io/apis/panther/panther-rule-api/) — The rule api handles all operations for rules
- [Panther s3 source API](https://apis.io/apis/panther/panther-s3-source-api/) — The S3 source API handles all operations for AWS S3 log sources
- [Panther scheduled rule API](https://apis.io/apis/panther/panther-scheduled-rule-api/) — The scheduled rule api handles all operations for scheduled rules
- [Panther simple rule API](https://apis.io/apis/panther/panther-simple-rule-api/) — The simple rule api handles all operations for simple rules
- [Panther User API](https://apis.io/apis/panther/panther-user-api/) — The user api handles all operations for users

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Panther Webhooks](https://apis.io/asyncapis/panther/panther-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [panther-mcp.yml](https://apis.io/servers/panther/panther-mcp-yml/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Panther Agentic Access](https://apis.io/agentic-access/panther/panther-agentic-access/)

#### Collections (21)

Postman and Open Collection request collections.

- [Panther REST alert API](https://apis.io/collections/panther/open-panther-alert-api/)
- [Panther REST alert api token API](https://apis.io/collections/panther/open-panther-api-token-api/)
- [Panther REST alert aws cloud account API](https://apis.io/collections/panther/open-panther-aws-cloud-account-api/)
- [Panther REST alert comment API](https://apis.io/collections/panther/open-panther-comment-api/)
- [Panther REST alert contexttag API](https://apis.io/collections/panther/open-panther-contexttag-api/)
- [Panther REST alert correlation rule API](https://apis.io/collections/panther/open-panther-correlation-rule-api/)
- [Panther REST alert data model API](https://apis.io/collections/panther/open-panther-data-model-api/)
- [Panther REST alert gcs source API](https://apis.io/collections/panther/open-panther-gcs-source-api/)
- [Panther REST alert global API](https://apis.io/collections/panther/open-panther-global-api/)
- [Panther REST alert http source API](https://apis.io/collections/panther/open-panther-http-source-api/)
- [Panther REST alert log forwarder source API](https://apis.io/collections/panther/open-panther-log-forwarder-source-api/)
- [Panther REST alert log source alarm API](https://apis.io/collections/panther/open-panther-log-source-alarm-api/)
- [Panther REST alert policy API](https://apis.io/collections/panther/open-panther-policy-api/)
- [Panther REST alert pub/sub source API](https://apis.io/collections/panther/open-panther-pub-sub-source-api/)
- [Panther REST alert query API](https://apis.io/collections/panther/open-panther-query-api/)
- [Panther REST alert role API](https://apis.io/collections/panther/open-panther-role-api/)
- [Panther REST alert rule API](https://apis.io/collections/panther/open-panther-rule-api/)
- [Panther REST alert s3 source API](https://apis.io/collections/panther/open-panther-s3-source-api/)
- [Panther REST alert scheduled rule API](https://apis.io/collections/panther/open-panther-scheduled-rule-api/)
- [Panther REST alert simple rule API](https://apis.io/collections/panther/open-panther-simple-rule-api/)
- [Panther REST alert user API](https://apis.io/collections/panther/open-panther-user-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Panther Rest Overlay](https://apis.io/overlays/panther/panther-rest-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Panther Authentication](https://apis.io/security/panther/panther-authentication/)
- [Panther Domain Security](https://apis.io/security/panther/panther-domain-security/)
- [Panther Trust Center](https://apis.io/security/panther/panther-trust-center/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.panther.com/)
- [Documentation](https://docs.panther.com/)
- [Getting started](https://docs.panther.com/quick-start)
- [Pricing](https://www.panther.com/pricing)
- [Sign up](https://www.panther.com/request-a-demo)
- [Support](https://help.panther.com/)
- [Blog](https://www.panther.com/blog)
- [Compliance](https://www.panther.com/security)
- [Terms of service](https://www.panther.com/terms-of-service)
- [Privacy policy](https://www.panther.com/privacy-policy)
- [GitHub](https://github.com/panther-labs)
- [Status](https://status.panther.com/)

## API Evangelist rating

**Kin Score 54.6** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 54.1 |
| Contract governance | 18.2 |
| Operational transparency | 26.3 |
| Developer ergonomics | 73.2 |
| Access clarity | 60.5 |

**Agent readiness 34.5** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | distinct |

**Regulatory alignment 29.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/panther/](https://apis.io/providers/panther/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Panther: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/panther/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
