# Honeybadger (honeybadger)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Honeybadger is an application monitoring platform that combines exception tracking, uptime monitoring, cron and background job monitoring, and status pages into a single service for software developers and operations teams. The platform supports a wide range of languages and frameworks including Ruby, Rails, Python, Node.js, PHP, Elixir, Go, and JavaScript, and integrates with Slack, GitHub, PagerDuty, and other developer tools. Honeybadger exposes a Reporting API for ingesting errors, deploys, and check-ins, plus a Data API for accessing account data, both using HTTP Basic authentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/honeybadger/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/honeybadger/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Error Monitoring
- Exception Tracking
- Application Performance Monitoring
- Uptime Monitoring
- Cron Monitoring
- Observability

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-30

## APIs

### Honeybadger Reporting API

Ingestion API for submitting exceptions, deploys, check-ins, source maps, and events from instrumented applications to Honeybadger. Uses a Project API Key as the authentication credential and accepts JSON payloads over HTTPS.

- **Human URL:** [https://docs.honeybadger.io/api/](https://docs.honeybadger.io/api/)
- **Base URL:** `https://api.honeybadger.io/v1`

#### Tags

- Error Monitoring
- Exception Tracking
- Reporting API
- Ingestion

#### Properties

- [Documentation](https://docs.honeybadger.io/api/)
- [Postman Collection](collections/honeybadger.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/honeybadger.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Honeybadger Data API

REST API for reading and modifying account data such as projects, faults, comments, teams, and integrations. Authenticated via HTTP Basic auth using a Personal Authentication Token as the username.

- **Human URL:** [https://docs.honeybadger.io/api/getting-started/](https://docs.honeybadger.io/api/getting-started/)
- **Base URL:** `https://app.honeybadger.io`

#### Tags

- Error Monitoring
- Data API
- HTTP Basic Auth
- Personal Authentication Token

#### Properties

- [Documentation](https://docs.honeybadger.io/api/getting-started/)
- [Postman Collection](collections/honeybadger.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/honeybadger.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Honeybadger Outbound Webhook Notifications

Outbound webhook notification surface delivered by Honeybadger to subscriber URLs configured via Project Settings > Alerts & Integrations. Covers the generic Webhook integration's documented event types (occurred, resolved, unresolved, assigned, commented, rate_exceeded, deployed, check_in_missing, check_in_reporting, down, up, cert_will_expire) plus the Slack and Microsoft Teams chat-platform delivery channels.

- **Human URL:** [https://docs.honeybadger.io/guides/integrations/webhook/](https://docs.honeybadger.io/guides/integrations/webhook/)
- **Base URL:** `https://example.com`

#### Tags

- Webhooks
- Notifications
- AsyncAPI
- Slack
- Microsoft Teams
- Event-Driven

#### Properties

- [Documentation](https://docs.honeybadger.io/guides/integrations/webhook/)
- [Documentation](https://docs.honeybadger.io/guides/integrations/slack/)
- [Documentation](https://docs.honeybadger.io/guides/integrations/microsoft-teams/)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/honeybadger/refs/heads/main/asyncapi/honeybadger-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/honeybadger.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/honeybadger.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.honeybadger.io)
- [Documentation](https://docs.honeybadger.io)
- [Pricing](https://www.honeybadger.io/plans/)
- [Sign Up](https://app.honeybadger.io/users/sign_up)
- [Blog](https://www.honeybadger.io/blog/)
- [GitHub Organization](https://github.com/honeybadger-io)
- [Git Hub  S D K](https://github.com/honeybadger-io/cli)
- [Support](mailto:support@honeybadger.io)
- [LinkedIn](https://www.linkedin.com/company/honeybadger-industries)
- [M C P Server](https://github.com/honeybadger-io/honeybadger-mcp-server)
- [L L Ms Txt](https://docs.honeybadger.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
