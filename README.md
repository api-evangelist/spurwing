# Spurwing (spurwing)

Spurwing is an enterprise-grade appointment scheduling, calendar, and time-management API. Its REST API powers booking widgets, marketplaces, SaaS, and healthcare scheduling with multi-user calendars, provider availability, group meetings, time-zone handling, and client booking. Public read and booking operations are scoped by a public Provider ID, while private operations use a Bearer API key. Spurwing joined Healthie.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/spurwing/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/spurwing/refs/heads/main/apis.yml)

## Tags

- Scheduling
- Appointments
- Booking
- Calendar
- Availability

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Spurwing Providers API

Provider calendars are the core scheduling entity in Spurwing. Each provider has a public Provider ID used to scope public availability and booking requests, supporting multi-user calendars for teams and organizations.

- **Human URL:** [https://docs.spurwing.io/](https://docs.spurwing.io/)
- **Base URL:** `https://api.spurwing.io/api/v2`

#### Tags

- Providers
- Calendars
- Scheduling

#### Properties

- [Documentation](https://docs.spurwing.io/)
- [OpenAPI](openapi/spurwing-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spurwing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spurwing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spurwing Availability API

Returns the days and bookable time slots a provider has open for a given appointment type and date range, with time-zone and organization-level options.

- **Human URL:** [https://docs.spurwing.io/](https://docs.spurwing.io/)
- **Base URL:** `https://api.spurwing.io/api/v2`

#### Tags

- Availability
- Slots
- Time Zones

#### Properties

- [Documentation](https://docs.spurwing.io/)
- [OpenAPI](openapi/spurwing-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spurwing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spurwing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spurwing Appointments API

Book client appointments, create group appointments, list an account's appointments, and cancel appointments. Booking is public per Provider ID; listing, group creation, and cancellation require a Bearer API key.

- **Human URL:** [https://docs.spurwing.io/](https://docs.spurwing.io/)
- **Base URL:** `https://api.spurwing.io/api/v2`

#### Tags

- Appointments
- Booking
- Group Meetings

#### Properties

- [Documentation](https://docs.spurwing.io/)
- [OpenAPI](openapi/spurwing-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spurwing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spurwing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spurwing Services API

Lists the appointment types (services) configured on a provider's calendar, each defining a bookable service with its own duration and availability rules.

- **Human URL:** [https://docs.spurwing.io/](https://docs.spurwing.io/)
- **Base URL:** `https://api.spurwing.io/api/v2`

#### Tags

- Services
- Appointment Types
- Catalog

#### Properties

- [Documentation](https://docs.spurwing.io/)
- [OpenAPI](openapi/spurwing-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spurwing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spurwing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spurwing Webhooks API

Spurwing references webhook-style event notifications for scheduling events in its integration guidance. Specific webhook event types and payloads are not reconciled in this artifact; verify against the official documentation.

- **Human URL:** [https://docs.spurwing.io/](https://docs.spurwing.io/)
- **Base URL:** `https://api.spurwing.io/api/v2`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.spurwing.io/)

## Common Properties

- [GitHub Organization](https://github.com/SpurwingIO)
- [LinkedIn](https://www.linkedin.com/company/spurwingio)
- [Website](https://www.spurwing.io/)
- [Documentation](https://docs.spurwing.io/)
- [Plans](plans/spurwing-plans-pricing.yml)
- [Rate Limits](rate-limits/spurwing-rate-limits.yml)
- [Fin Ops](finops/spurwing-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
