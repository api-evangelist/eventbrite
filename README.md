# Eventbrite (eventbrite)

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

A global self-service ticketing and event technology platform for live experiences. Enables creators to plan, promote, and sell tickets for events of all sizes. The Eventbrite Platform exposes a REST API plus webhooks that lets developers manage events, attendees, orders, organizations, ticket classes, and venues.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/eventbrite/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/eventbrite/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Events
- Event Technology
- Ticketing
- Marketplace

## Timestamps

- **Created:** 2026-05-05
- **Modified:** 2026-05-16

## APIs

### Eventbrite Platform API

The Eventbrite Platform API is a REST API that lets developers manage events, attendees, orders, organizations, ticket classes, venues, categories, and event series on Eventbrite. The API uses OAuth 2.0 with bearer tokens (private and OAuth-issued tokens); resources are accessed under the v3 base path at https://www.eventbriteapi.com/v3 and return JSON payloads. Typical use cases include syncing event inventory into external sites, fulfilling tickets and check-in flows, embedding event creation into partner platforms, and reporting on attendee and sales data.

- **Human URL:** [https://www.eventbrite.com/platform/api](https://www.eventbrite.com/platform/api)
- **Base URL:** `https://www.eventbriteapi.com/v3`

#### Tags

- Events
- Attendees
- Orders
- Organizations
- Ticket Classes
- Venues
- Categories

#### Properties

- [Documentation](https://www.eventbrite.com/platform/api)
- [Signup U R L](https://www.eventbrite.com/platform/api-keys)
- [Authentication](https://www.eventbrite.com/platform/api#/introduction/authentication)
- [Postman Collection](collections/eventbrite.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/eventbrite.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Eventbrite Webhooks

Eventbrite Webhooks deliver HTTP POST notifications to subscriber URLs when events such as event publish/unpublish, order placement and updates, attendee changes, refunds, and check-ins occur on Eventbrite. Developers register webhook endpoints against an organization via the Platform API and use the resulting payloads to drive real-time integrations without polling the REST API.

- **Human URL:** [https://www.eventbrite.com/platform/api#/reference/webhook](https://www.eventbrite.com/platform/api#/reference/webhook)
- **Base URL:** `https://www.eventbriteapi.com/v3`

#### Tags

- Webhooks
- Events
- Orders
- Notifications
- Automation

#### Properties

- [Documentation](https://www.eventbrite.com/platform/api#/reference/webhook)
- [Postman Collection](collections/eventbrite.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/eventbrite.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Eventbrite Python SDK

The Eventbrite Python SDK is an open-source client library maintained by Eventbrite that provides idiomatic Python access to the Eventbrite Platform API for managing events, orders, attendees, and related resources.

- **Human URL:** [https://github.com/eventbrite/eventbrite-sdk-python](https://github.com/eventbrite/eventbrite-sdk-python)
- **Base URL:** `https://www.eventbriteapi.com/v3`

#### Tags

- SDK
- Python
- Client Library

#### Properties

- [Source Code](https://github.com/eventbrite/eventbrite-sdk-python)
- [SDK](https://pypi.org/project/eventbrite/)
- [Postman Collection](collections/eventbrite.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/eventbrite.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/eventbrite)
- [Website](https://www.eventbrite.com/)
- [Developer Portal](https://www.eventbrite.com/platform/)
- [Documentation](https://www.eventbrite.com/platform/api)
- [Signup U R L](https://www.eventbrite.com/platform/api-keys)
- [Source Code](https://github.com/eventbrite)
- [Privacy Policy](https://www.eventbrite.com/support/articles/en_US/Troubleshooting/eventbrite-privacy-policy)
- [Terms of Service](https://www.eventbrite.com/support/articles/en_US/Troubleshooting/eventbrite-terms-of-service)
- [Support](https://www.eventbrite.com/support/contact-us)
- [Blog](https://www.eventbrite.com/blog/)
- [Login](https://www.eventbrite.com/signin/)
