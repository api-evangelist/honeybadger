# Honeybadger

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

Honeybadger is an application monitoring platform that combines exception tracking, uptime monitoring, cron and background job monitoring, and status pages into a single service for software developers and operations teams. The platform supports a wide range of languages and frameworks including Ruby, Rails, Python, Node.js, PHP, Elixir, Go, and JavaScript, and integrates with Slack, GitHub, PagerDuty, and other developer tools. Honeybadger exposes a Reporting API for ingesting errors, deploys, and check-ins, plus a Data API for accessing account data, both using HTTP Basic authentication.

**Areas:** Error Monitoring · Exception Tracking · Application Performance Monitoring · Uptime Monitoring · Cron Monitoring · Observability

## Honeybadger on APIs.io

Everything profiled for Honeybadger is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/honeybadger/](https://apis.io/providers/honeybadger/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [Honeybadger Reporting API](https://apis.io/apis/honeybadger/reporting-api/) — Ingestion API for submitting exceptions, deploys, check-ins, source maps, and events from instrumented applications to Honeybadger. Uses a Project API Key…
- [Honeybadger Data API](https://apis.io/apis/honeybadger/data-api/) — REST API for reading and modifying account data such as projects, faults, comments, teams, and integrations. Authenticated via HTTP Basic auth using a…
- [Honeybadger Outbound Webhook Notifications](https://apis.io/apis/honeybadger/webhooks/) — Outbound webhook notification surface delivered by Honeybadger to subscriber URLs configured via Project Settings > Alerts & Integrations. Covers the…
- [Honeybadger Check In API](https://apis.io/apis/honeybadger/honeybadger-check-in-api/) — The Check In API from Honeybadger — 1 operation(s) for check in.
- [Honeybadger Deploys API](https://apis.io/apis/honeybadger/honeybadger-deploys-api/) — The Deploys API from Honeybadger — 1 operation(s) for deploys.
- [Honeybadger Events API](https://apis.io/apis/honeybadger/honeybadger-events-api/) — The Events API from Honeybadger — 1 operation(s) for events.
- [Honeybadger Notices API](https://apis.io/apis/honeybadger/honeybadger-notices-api/) — The Notices API from Honeybadger — 1 operation(s) for notices.
- [Honeybadger Projects API](https://apis.io/apis/honeybadger/honeybadger-projects-api/) — The Projects API from Honeybadger — 21 operation(s) for projects.
- [Honeybadger Source Maps API](https://apis.io/apis/honeybadger/honeybadger-source-maps-api/) — The Source Maps API from Honeybadger — 1 operation(s) for source maps.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Honeybadger Outbound Webhook Notifications](https://apis.io/asyncapis/honeybadger/honeybadger-webhooks-asyncapi/)

#### Event channels (3)

Individual events and webhooks the provider emits.

- [microsoftTeams](https://apis.io/channels/honeybadger/microsoftteams/)
- [slack](https://apis.io/channels/honeybadger/slack/)
- [webhook](https://apis.io/channels/honeybadger/webhook/)

#### MCP servers (2)

Model Context Protocol servers that expose the API to agents.

- [honeybadger](https://apis.io/servers/honeybadger/honeybadger/)
- [MCP Server](https://apis.io/servers/honeybadger/mcp-server/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Honeybadger Agentic Access](https://apis.io/agentic-access/honeybadger/honeybadger-agentic-access/)

#### Collections (7)

Postman and Open Collection request collections.

- [Honeybadger API](https://apis.io/collections/honeybadger/open-honeybadger/)
- [Honeybadger Check In API](https://apis.io/collections/honeybadger/open-honeybadger-check-in-api/)
- [Honeybadger Check In Deploys API](https://apis.io/collections/honeybadger/open-honeybadger-deploys-api/)
- [Honeybadger Check In Events API](https://apis.io/collections/honeybadger/open-honeybadger-events-api/)
- [Honeybadger Check In Notices API](https://apis.io/collections/honeybadger/open-honeybadger-notices-api/)
- [Honeybadger Check In Projects API](https://apis.io/collections/honeybadger/open-honeybadger-projects-api/)
- [Honeybadger Check In Source Maps API](https://apis.io/collections/honeybadger/open-honeybadger-source-maps-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Honeybadger — asyncapi rules](https://apis.io/rules/honeybadger/honeybadger-asyncapi-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Honeybadger Authentication](https://apis.io/security/honeybadger/honeybadger-authentication/)
- [Honeybadger Domain Security](https://apis.io/security/honeybadger/honeybadger-domain-security/)
- [Honeybadger Trust Center](https://apis.io/security/honeybadger/honeybadger-trust-center/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.honeybadger.io)
- [Documentation](https://docs.honeybadger.io)
- [Pricing](https://www.honeybadger.io/plans/)
- [Blog](https://www.honeybadger.io/blog/)
- [GitHub](https://github.com/honeybadger-io)

## API Evangelist rating

**Kin Score 34.4** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 54.3 |
| Contract governance | 11.4 |
| Operational transparency | 2.6 |
| Developer ergonomics | 28.6 |
| Access clarity | 31.6 |

**Agent readiness 44.4** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/honeybadger/](https://apis.io/providers/honeybadger/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Honeybadger: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/honeybadger/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
