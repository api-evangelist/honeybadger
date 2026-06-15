# Honeybadger (honeybadger)

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
