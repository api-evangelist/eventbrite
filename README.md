# Eventbrite (eventbrite)

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
