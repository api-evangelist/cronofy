# Cronofy (cronofy)

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
