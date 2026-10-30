# Inngest

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

Inngest is an event-driven durable execution platform for background jobs, step functions, scheduled workflows, and AI agent orchestration. It exposes a v1 event ingestion and run inspection API, a v2 management API (accounts, environments, apps, webhooks, keys, function invocation, runs, traces), official SDKs for TypeScript, Python, Go, and Kotlin, AgentKit for multi-agent systems, Connect for persistent worker connections, Realtime streaming, Signals, Durable Endpoints, Insights (SQL over events and runs), and a heavily-marketed local Dev Server CLI.

**Areas:** AI Agents · AgentKit · Background Jobs · Connect · Cron Jobs · Dev Server · Durable Endpoints · Durable Execution · Event-Driven · Insights · Orchestration · Queues

## Inngest on APIs.io

Everything profiled for Inngest is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/inngest/](https://apis.io/providers/inngest/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [Inngest Account API](https://apis.io/apis/inngest/inngest-account-api/) — Account-level details for the authenticated user.
- [Inngest Apps API](https://apis.io/apis/inngest/inngest-apps-api/) — Sync app endpoints exposing Inngest functions.
- [Inngest Environments API](https://apis.io/apis/inngest/inngest-environments-api/) — Manage production and branch environments for an account.
- [Inngest Events API](https://apis.io/apis/inngest/inngest-events-api/) — Send and inspect events that trigger Inngest functions.
- [Inngest Functions API](https://apis.io/apis/inngest/inngest-functions-api/) — List and invoke deployed Inngest functions.
- [Inngest Keys API](https://apis.io/apis/inngest/inngest-keys-api/) — Manage event keys and signing keys per environment.
- [Inngest Runs API](https://apis.io/apis/inngest/inngest-runs-api/) — Fetch the status, jobs, and trace trees of function runs.
- [Inngest Webhooks API](https://apis.io/apis/inngest/inngest-webhooks-api/) — Manage inbound webhooks that translate third-party payloads into Inngest events.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Inngest Agentic Access](https://apis.io/agentic-access/inngest/inngest-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [InngestEnvironment](https://apis.io/schemas/inngest/inngest-environment/)
- [InngestEvent](https://apis.io/schemas/inngest/inngest-event/)
- [InngestFunction](https://apis.io/schemas/inngest/inngest-function/)
- [InngestRun](https://apis.io/schemas/inngest/inngest-run/)
- [InngestTraceSpan](https://apis.io/schemas/inngest/inngest-trace-span/)
- [InngestWebhook](https://apis.io/schemas/inngest/inngest-webhook/)

#### JSON Structure (3)

Data models expressed in JSON Structure.

- [Inngest Event Structure](https://apis.io/json-structure/inngest/inngest-event-structure/)
- [Inngest Run Structure](https://apis.io/json-structure/inngest/inngest-run-structure/)
- [Inngest Trace Structure](https://apis.io/json-structure/inngest/inngest-trace-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Inngest Context](https://apis.io/jsonld/inngest/inngest-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Inngest Vocabulary](https://apis.io/vocabularies/inngest/inngest-vocabulary/)

#### Examples (7)

Example requests and responses.

- [Inngest Create Webhook Example](https://apis.io/examples/inngest/inngest-create-webhook-example/)
- [Inngest Get Run Example](https://apis.io/examples/inngest/inngest-get-run-example/)
- [Inngest Get Trace Example](https://apis.io/examples/inngest/inngest-get-trace-example/)
- [Inngest Invoke Function Example](https://apis.io/examples/inngest/inngest-invoke-function-example/)
- [Inngest List Environments Example](https://apis.io/examples/inngest/inngest-list-environments-example/)
- [Inngest List Functions Example](https://apis.io/examples/inngest/inngest-list-functions-example/)
- [Inngest Send Event Example](https://apis.io/examples/inngest/inngest-send-event-example/)

#### Collections (17)

Postman and Open Collection request collections.

- [Inngest REST API](https://apis.io/collections/inngest/open-inngest/)
- [Inngest REST Account API](https://apis.io/collections/inngest/open-inngest-account-api/)
- [Inngest REST Account Apps API](https://apis.io/collections/inngest/open-inngest-apps-api/)
- [Inngest REST Account Environments API](https://apis.io/collections/inngest/open-inngest-environments-api/)
- [Inngest REST Account Events API](https://apis.io/collections/inngest/open-inngest-events-api/)
- [Inngest REST Account Functions API](https://apis.io/collections/inngest/open-inngest-functions-api/)
- [Inngest REST Account Keys API](https://apis.io/collections/inngest/open-inngest-keys-api/)
- [Inngest REST Account Runs API](https://apis.io/collections/inngest/open-inngest-runs-api/)
- [Inngest REST Account Webhooks API](https://apis.io/collections/inngest/open-inngest-webhooks-api/)
- [Inngest REST Account API](https://apis.io/collections/inngest/postman-inngest-account-api/)
- [Inngest REST Account Apps API](https://apis.io/collections/inngest/postman-inngest-apps-api/)
- [Inngest REST Account Environments API](https://apis.io/collections/inngest/postman-inngest-environments-api/)
- [Inngest REST Account Events API](https://apis.io/collections/inngest/postman-inngest-events-api/)
- [Inngest REST Account Functions API](https://apis.io/collections/inngest/postman-inngest-functions-api/)
- [Inngest REST Account Keys API](https://apis.io/collections/inngest/postman-inngest-keys-api/)
- [Inngest REST Account Runs API](https://apis.io/collections/inngest/postman-inngest-runs-api/)
- [Inngest REST Account Webhooks API](https://apis.io/collections/inngest/postman-inngest-webhooks-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Inngest — jsonschema rules](https://apis.io/rules/inngest/inngest-jsonschema-spectral-rules/)
- [Inngest API Rules](https://apis.io/rules/inngest/inngest-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Inngest Authentication](https://apis.io/security/inngest/inngest-authentication/)
- [Inngest Domain Security](https://apis.io/security/inngest/inngest-domain-security/)
- [Inngest Trust Center](https://apis.io/security/inngest/inngest-trust-center/)
- [Inngest Vulnerability Disclosure](https://apis.io/security/inngest/inngest-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Inngest Plans Pricing](https://apis.io/plans/inngest/inngest-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Inngest Rate Limits](https://apis.io/rate-limits/inngest/inngest-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Inngest Finops](https://apis.io/finops/inngest/inngest-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.inngest.com/)
- [Documentation](https://www.inngest.com/docs)
- [Getting started](https://www.inngest.com/docs/getting-started/nextjs-quick-start)
- [API reference](https://api-docs.inngest.com)
- [Pricing](https://www.inngest.com/pricing)
- [Support](https://app.inngest.com/support)
- [Changelog](https://www.inngest.com/changelog)
- [Blog](https://www.inngest.com/blog)
- [Security](https://www.inngest.com/security)
- [Trust centre](https://trust.inngest.com/)
- [Terms of service](https://www.inngest.com/terms)
- [Status](https://status.inngest.com)

## API Evangelist rating

**Kin Score 59.3** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 63.7 |
| Contract governance | 23.5 |
| Operational transparency | 60.5 |
| Developer ergonomics | 72.6 |
| Access clarity | 46.1 |

**Agent readiness 37.9** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
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

**Regulatory alignment 30.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/inngest/](https://apis.io/providers/inngest/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Inngest: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/inngest/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
