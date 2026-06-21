# Cronofy (cronofy)

Cronofy is a scheduling and calendar API platform that provides a unified interface to Google Calendar, Microsoft 365 / Outlook, Exchange, and Apple iCloud. Its REST API powers two-way calendar sync, real-time availability and scheduling, smart invites, scheduling links, and push notifications for software teams embedding scheduling into their products.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cronofy/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cronofy/refs/heads/main/apis.yml)

## Tags

- Scheduling
- Calendar
- Availability
- Booking
- Productivity

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Cronofy Calendars API

List a user's connected calendars across Google, Microsoft 365 / Outlook, Exchange, and Apple iCloud, create application calendars, and read account profile and userinfo identity details.

- **Human URL:** [https://docs.cronofy.com/developers/api/calendars/](https://docs.cronofy.com/developers/api/calendars/)
- **Base URL:** `https://api.cronofy.com/v1`

#### Tags

- Calendars
- Profiles
- Identity

#### Properties

- [Documentation](https://docs.cronofy.com/developers/api/calendars/)
- [API Reference](https://docs.cronofy.com/developers/api/)
- [OpenAPI](openapi/cronofy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cronofy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cronofy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cronofy Events API

Read events and free/busy information across all of a user's calendars, and create, update, or delete events within a managed calendar with two-way sync.

- **Human URL:** [https://docs.cronofy.com/developers/api/events/](https://docs.cronofy.com/developers/api/events/)
- **Base URL:** `https://api.cronofy.com/v1`

#### Tags

- Events
- Free-Busy
- Sync

#### Properties

- [Documentation](https://docs.cronofy.com/developers/api/events/)
- [API Reference](https://docs.cronofy.com/developers/api/events/free-busy/)
- [OpenAPI](openapi/cronofy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cronofy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cronofy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cronofy Availability API

Query common availability for people and resources, run sequenced availability across multiple events, and generate hosted Real-Time Scheduling and Real-Time Sequencing pages backed by live calendar data.

- **Human URL:** [https://docs.cronofy.com/developers/api/scheduling/availability/](https://docs.cronofy.com/developers/api/scheduling/availability/)
- **Base URL:** `https://api.cronofy.com/v1`

#### Tags

- Availability
- Scheduling
- Real-Time Scheduling

#### Properties

- [Documentation](https://docs.cronofy.com/developers/api/scheduling/)
- [API Reference](https://docs.cronofy.com/developers/api/scheduling/availability/)
- [OpenAPI](openapi/cronofy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cronofy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cronofy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cronofy Smart Invites API

Send users calendar invites and track their interactions (accept, decline, tentative) without requiring any calendar authorization, with create, update, cancel, and status retrieval.

- **Human URL:** [https://docs.cronofy.com/developers/api/smart-invites/](https://docs.cronofy.com/developers/api/smart-invites/)
- **Base URL:** `https://api.cronofy.com/v1`

#### Tags

- Smart Invites
- Calendar Invites
- No Auth

#### Properties

- [Documentation](https://docs.cronofy.com/developers/api/smart-invites/)
- [API Reference](https://docs.cronofy.com/developers/api/smart-invites/create-smart-invite/)
- [OpenAPI](openapi/cronofy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cronofy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cronofy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cronofy Scheduling Links API

Generate shareable Real-Time Scheduling URLs where invitees pick a preferred time from live availability, with the resulting event written into the host's calendar automatically.

- **Human URL:** [https://docs.cronofy.com/developers/api/scheduling/real-time-scheduling/](https://docs.cronofy.com/developers/api/scheduling/real-time-scheduling/)
- **Base URL:** `https://api.cronofy.com/v1`

#### Tags

- Scheduling Links
- Booking
- Real-Time Booking

#### Properties

- [Documentation](https://docs.cronofy.com/developers/api/scheduling/real-time-scheduling/)
- [API Reference](https://docs.cronofy.com/developers/api/scheduling/)
- [OpenAPI](openapi/cronofy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cronofy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cronofy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cronofy Push Notifications API

Create, list, and close notification channels that deliver real-time push notifications to a callback URL whenever changes occur in a user's connected calendars.

- **Human URL:** [https://docs.cronofy.com/developers/api/push-notifications/](https://docs.cronofy.com/developers/api/push-notifications/)
- **Base URL:** `https://api.cronofy.com/v1`

#### Tags

- Push Notifications
- Channels
- Webhooks

#### Properties

- [Documentation](https://docs.cronofy.com/developers/api/push-notifications/)
- [API Reference](https://docs.cronofy.com/developers/api/push-notifications/create-channel/)
- [OpenAPI](openapi/cronofy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cronofy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cronofy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/cronofy)
- [LinkedIn](https://www.linkedin.com/company/cronofy)
- [Website](https://www.cronofy.com)
- [Documentation](https://docs.cronofy.com/developers/)
- [Plans](plans/cronofy-plans-pricing.yml)
- [Rate Limits](rate-limits/cronofy-rate-limits.yml)
- [Fin Ops](finops/cronofy-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
