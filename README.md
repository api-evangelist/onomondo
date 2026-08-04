# Onomondo (onomondo)

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
