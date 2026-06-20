# GridX (gridx)

GridX Inc. (Walnut Creek, California) is the Enterprise Rate Platform for modern utilities. Its cloud-based Rate Engine replicates utility billing-system (CIS) bill calculations to design, measure, implement, and bill advanced rates and programs. GridX exposes a partner/enterprise developer API (the Calculate / Empower APIs) for rate calculation, pricing retrieval, customer info/usage, bill and cost analysis, and OpenADR demand-response program subscriptions, currently documented for specific utility deployments (e.g., PG&E, SCE).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/gridx/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/gridx/refs/heads/main/apis.yml)

## Tags

- Energy
- Utilities
- Rate Engine
- Billing
- Rate Analytics

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### GridX Rate Engine API

Cloud-based Rate Engine that replicates utility CIS bill calculations. The documented Pricing API returns historical, current, and forecasted dynamic prices (generation and distribution components per interval) for a given utility, market, program, and rate, with examples for PG&E and SCE deployments.

- **Human URL:** [https://api-calculate-docs.gridx.com/calculate-apis-gridx-docs/get-pricing](https://api-calculate-docs.gridx.com/calculate-apis-gridx-docs/get-pricing)
- **Base URL:** `https://pge-pe-api.gridx.com/v1`

#### Tags

- Rate Engine
- Bill Calculation
- Pricing

#### Properties

- [Documentation](https://api-calculate-docs.gridx.com/calculate-apis-gridx-docs/get-pricing)
- [API Reference](https://api-calculate-docs.gridx.com/calculate-apis-gridx-docs/get-pricing)
- [OpenAPI](openapi/gridx-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gridx.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gridx.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GridX Bill Calculation API

GridX Calculate accurately calculates bills based on tariff, contract, rider, option, and tax rules, with real-time rate analysis and the ability to apply modifiers to simulate behavior changes. Documented customer endpoints return account info (rate code, voltage class, circuit, CCA) and interval consumption/generation usage used as inputs to bill calculation.

- **Human URL:** [https://gridx.com/calculate/](https://gridx.com/calculate/)
- **Base URL:** `https://pge-pe-api.gridx.com/v1`

#### Tags

- Bill Calculation
- Calculate
- Tariffs

#### Properties

- [Documentation](https://gridx.com/calculate/)
- [API Reference](https://api-calculate-docs.gridx.com/calculate-apis-gridx-docs/get-customer-info)
- [OpenAPI](openapi/gridx-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gridx.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gridx.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GridX Rate Analytics API

GridX Empower is a set of rate, cost, and bill analysis APIs that deliver personalized insights to engagement channels (MyAccount, portals, mobile, IVR, call center). Categories include Rate Analysis (forward-looking comparison across eligible rates), Bill Analysis and Bill Forecast, and per-interval Cost Calculation.

- **Human URL:** [https://empower.gridx.com/](https://empower.gridx.com/)
- **Base URL:** `https://pge-pe-api.gridx.com/v1`

#### Tags

- Rate Analytics
- Bill Analysis
- Empower

#### Properties

- [Documentation](https://empower.gridx.com/)
- [API Reference](https://gridx.com/empower/)
- [OpenAPI](openapi/gridx-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gridx.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gridx.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### GridX OpenADR Programs API

OpenADR-aligned API for demand-response programs - list available programs and create, retrieve, and delete program subscriptions - secured with a separate token-authentication flow.

- **Human URL:** [https://api-calculate-docs.gridx.com/calculate-apis-gridx-docs/get-pricing](https://api-calculate-docs.gridx.com/calculate-apis-gridx-docs/get-pricing)
- **Base URL:** `https://pge-pe-api.gridx.com/v1`

#### Tags

- OpenADR
- Demand Response
- Programs

#### Properties

- [Documentation](https://api-calculate-docs.gridx.com/calculate-apis-gridx-docs/get-pricing)
- [OpenAPI](openapi/gridx-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gridx.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gridx.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/gridx-inc)
- [Website](https://www.gridx.com/)
- [Documentation](https://api-calculate-docs.gridx.com/calculate-apis-gridx-docs/get-pricing)
- [Plans](plans/gridx-plans-pricing.yml)
- [Rate Limits](rate-limits/gridx-rate-limits.yml)
- [Fin Ops](finops/gridx-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
