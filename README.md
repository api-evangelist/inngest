# Inngest (inngest)

Inngest is an event-driven durable execution platform for background jobs, step functions, scheduled workflows, and AI agent orchestration. This repo profiles Inngest's developer surface: REST API (v1 + v2), SDKs, Dev Server CLI, AgentKit, Connect, Realtime, Insights, and self-hosting.

**URL:** [Visit APIs.yml URL](https://raw.githubusercontent.com/api-evangelist/inngest/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

AI Agents, AgentKit, Background Jobs, Connect, Cron Jobs, Dev Server, Durable Endpoints, Durable Execution, Event-Driven, Insights, Orchestration, Queues, Realtime, Self-Hosting, Serverless, Signals, Step Functions, Webhooks, Workflows

## Timestamps

- **Created:** 2026-03-03
- **Modified:** 2026-05-22

## APIs

### Inngest REST API

The Inngest REST API spans two surfaces:

- **v1** — event ingestion (`/e/{eventKey}`, alias `inn.gs`), event listing/inspection, and run inspection (status, step jobs, cancel) under `/v1/...`.
- **v2** — management surface under `/v2/...` covering account, environments, apps (sync), function invocation, webhooks, event/signing keys, canonical run summaries, and OpenTelemetry-style trace trees.

Authenticated calls use a `Bearer signkey-...` token from the v2 signing-keys endpoint. The same surface is hosted locally by the Inngest Dev Server on `http://localhost:8288` (v1) and `http://localhost:8288/api/v2` (v2).

**Human URL:** https://www.inngest.com/docs/reference/rest-api
**API Reference:** https://api-docs.inngest.com
**Base URL:** https://api.inngest.com

#### Tags

Account, Apps, Environments, Events, Functions, Keys, REST API, Runs, Trace, Webhooks, Workflows

#### API Properties

- [Documentation](https://www.inngest.com/docs)
- [APIReference](https://api-docs.inngest.com)
- [OpenAPI (upstream v2)](https://api-docs.inngest.com/api-specs/v2.json)
- [OpenAPI (this repo)](openapi/inngest-openapi.yml)
- [Rules](rules/inngest-rules.yml)
- [GettingStarted](https://www.inngest.com/docs/getting-started/nextjs-quick-start)
- [Vocabulary](vocabulary/inngest-vocabulary.yml)
- [Plans](plans/inngest-plans-pricing.yml)
- [RateLimits](rate-limits/inngest-rate-limits.yml)
- [FinOps](finops/inngest-finops.yml)

#### Naftiko Capabilities

- [Events](capabilities/inngest-events.yaml)
- [Runs](capabilities/inngest-runs.yaml)
- [Functions](capabilities/inngest-functions.yaml)
- [Environments](capabilities/inngest-environments.yaml)
- [Webhooks](capabilities/inngest-webhooks.yaml)
- [Keys](capabilities/inngest-keys.yaml)
- [Apps](capabilities/inngest-apps.yaml)
- [Account](capabilities/inngest-account.yaml)
- [Durable Workflow (composition)](capabilities/durable-workflow.yaml)

#### JSON Schemas

- [Event](json-schema/inngest-event-schema.json)
- [Run](json-schema/inngest-run-schema.json)
- [Function](json-schema/inngest-function-schema.json)
- [Trace Span](json-schema/inngest-trace-span-schema.json)
- [Environment](json-schema/inngest-environment-schema.json)
- [Webhook](json-schema/inngest-webhook-schema.json)

#### JSON Structures

- [Event](json-structure/inngest-event-structure.json)
- [Run](json-structure/inngest-run-structure.json)
- [Trace](json-structure/inngest-trace-structure.json)

#### JSON-LD

- [Context](json-ld/inngest-context.jsonld)

#### Examples

- [Send Event](examples/inngest-send-event-example.json)
- [Get Run](examples/inngest-get-run-example.json)
- [Get Trace](examples/inngest-get-trace-example.json)
- [List Functions](examples/inngest-list-functions-example.json)
- [Invoke Function](examples/inngest-invoke-function-example.json)
- [List Environments](examples/inngest-list-environments-example.json)
- [Create Webhook](examples/inngest-create-webhook-example.json)

## SDKs, CLI, and Tooling

- **TypeScript SDK** — [github.com/inngest/inngest-js](https://github.com/inngest/inngest-js) (`inngest`; v4 GA March 2026)
- **Python SDK** — [github.com/inngest/inngest-py](https://github.com/inngest/inngest-py)
- **Go SDK** — [github.com/inngest/inngestgo](https://github.com/inngest/inngestgo)
- **Kotlin SDK** — [github.com/inngest/inngest-kt](https://github.com/inngest/inngest-kt)
- **Rust SDK** — [github.com/inngest/inngest-rs](https://github.com/inngest/inngest-rs)
- **Browser SDK** — [github.com/inngest/inngest-browser](https://github.com/inngest/inngest-browser)
- **Deno SDK** — [github.com/inngest/inngest-deno](https://github.com/inngest/inngest-deno)
- **Dev Server CLI** — `curl -sSfL https://cli.inngest.com/install.sh | sh` then `inngest dev -u http://localhost:3000/api/inngest` (UI on `http://localhost:8288`, Connect on `8289`)
- **AgentKit** — [agentkit.inngest.com](https://agentkit.inngest.com) (`@inngest/agent-kit`, multi-agent networks with deterministic routing)
- **WorkflowKit** — [github.com/inngest/workflow-kit](https://github.com/inngest/workflow-kit) (Zapier-like workflow UI components)
- **Event Schemas** — [github.com/inngest/event-schemas](https://github.com/inngest/event-schemas)
- **GitHub Actions** — [setup-inngest](https://github.com/inngest/setup-inngest), [action-deploy-functions](https://github.com/inngest/action-deploy-functions), [action-test-functions](https://github.com/inngest/action-test-functions)
- **Self-Hosting** — `docker pull inngest/inngest` and the [inngest-helm](https://github.com/inngest/inngest-helm) chart (Postgres + Redis + optional KEDA)

## Common Properties

- [Portal](https://www.inngest.com)
- [Documentation](https://www.inngest.com/docs)
- [APIReference](https://api-docs.inngest.com)
- [GettingStarted](https://www.inngest.com/docs/getting-started/nextjs-quick-start)
- [Blog](https://www.inngest.com/blog)
- [Changelog](https://www.inngest.com/changelog)
- [Pricing](https://www.inngest.com/pricing)
- [About](https://www.inngest.com/about)
- [SignUp](https://app.inngest.com/sign-up)
- [Login](https://app.inngest.com)
- [Support](https://app.inngest.com/support)
- [StatusPage](https://status.inngest.com)
- [RoadMap](https://roadmap.inngest.com/roadmap)
- [FAQ](https://www.inngest.com/docs/faq)
- [Privacy](https://www.inngest.com/privacy)
- [TermsOfService](https://www.inngest.com/terms)
- [Security](https://www.inngest.com/security)
- [TrustCenter](https://trust.inngest.com/)
- [Contact](https://www.inngest.com/contact)
- [GitHubOrg](https://github.com/inngest)
- [GitHubRepo (core)](https://github.com/inngest/inngest)
- [Discord](https://www.inngest.com/discord)
- [X](https://x.com/inngest)
- [Bluesky](https://bsky.app/profile/inngest.com)
- [SelfHosting](https://www.inngest.com/docs/self-hosting)
- [DockerImage](https://hub.docker.com/r/inngest/inngest)
- [HelmChart](https://github.com/inngest/inngest-helm)
- [Dev Server](https://www.inngest.com/docs/dev-server)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
