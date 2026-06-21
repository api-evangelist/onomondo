# Onomondo (onomondo)

Onomondo is a global IoT cellular-connectivity platform that connects devices to 680+ networks across 180+ countries using a single core network. The Onomondo API (https://api.onomondo.com) provides programmatic management of SIMs, data usage, network lists, SMS, webhooks, connectors, and tags with Bearer API-key authentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/onomondo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/onomondo/refs/heads/main/apis.yml)

## Tags

- IoT
- Connectivity
- Cellular
- SIM
- Telecom

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Onomondo SIMs API

List, find, retrieve, and update SIMs across an IoT fleet, including activation state, data limits, network lists, IMEI lock, supported technologies, and tag assignment (single and bulk).

- **Human URL:** [https://docs.onomondo.com/readme/sims](https://docs.onomondo.com/readme/sims)
- **Base URL:** `https://api.onomondo.com`

#### Tags

- SIM
- IoT
- Fleet Management

#### Properties

- [Documentation](https://docs.onomondo.com/readme/sims)
- [API Reference](https://docs.onomondo.com/)
- [OpenAPI](openapi/onomondo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/onomondo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/onomondo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Onomondo Usage & Traffic API

Retrieve data usage for all SIMs, an individual SIM, or aggregated by Tag, plus SMS usage records. Complements the Traffic Monitor tooling for real-time packet-level traffic inspection.

- **Human URL:** [https://docs.onomondo.com/readme/usage](https://docs.onomondo.com/readme/usage)
- **Base URL:** `https://api.onomondo.com`

#### Tags

- Usage
- Traffic
- Metering

#### Properties

- [Documentation](https://docs.onomondo.com/readme/usage)
- [Documentation](https://docs.onomondo.com/traffic-monitor-cli)
- [OpenAPI](openapi/onomondo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/onomondo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/onomondo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Onomondo Networks API

Create, retrieve, update, and delete Network Lists - named allow-lists of MCC/MNC network entries with associated Tags that control which mobile networks SIMs may attach to.

- **Human URL:** [https://docs.onomondo.com/readme/network-whitelists](https://docs.onomondo.com/readme/network-whitelists)
- **Base URL:** `https://api.onomondo.com`

#### Tags

- Networks
- MCC
- MNC

#### Properties

- [Documentation](https://docs.onomondo.com/readme/network-whitelists)
- [OpenAPI](openapi/onomondo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/onomondo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/onomondo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Onomondo Webhooks & Notifications API

Manage webhooks that deliver near-real-time SIM events (usage, network registration/deregistration/authentication, SMS, location, and cost-alert) as HTTP POST callbacks, with Tag-based filtering and event-type exclusion.

- **Human URL:** [https://docs.onomondo.com/readme/webhooks](https://docs.onomondo.com/readme/webhooks)
- **Base URL:** `https://api.onomondo.com`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.onomondo.com/readme/webhooks)
- [Documentation](https://docs.onomondo.com/webhooks-reference)
- [OpenAPI](openapi/onomondo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/onomondo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/onomondo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Onomondo Apps & Connectors API

Create, update, and delete Connectors (Apps) that forward device traffic to cloud destinations such as HTTPS, TLS, Microsoft Azure IoT, and AWS IoT Core, plus search organization Tags used to group SIMs.

- **Human URL:** [https://docs.onomondo.com/readme/connectors](https://docs.onomondo.com/readme/connectors)
- **Base URL:** `https://api.onomondo.com`

#### Tags

- Connectors
- Integrations
- Cloud

#### Properties

- [Documentation](https://docs.onomondo.com/readme/connectors)
- [OpenAPI](openapi/onomondo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/onomondo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/onomondo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/onomondo)
- [LinkedIn](https://www.linkedin.com/company/onomondo)
- [Website](https://onomondo.com/)
- [Documentation](https://docs.onomondo.com/)
- [Plans](plans/onomondo-plans-pricing.yml)
- [Rate Limits](rate-limits/onomondo-rate-limits.yml)
- [Fin Ops](finops/onomondo-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
