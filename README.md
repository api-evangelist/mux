# Mux (mux)

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

Mux is an API-first video platform that provides developer tools for video streaming, on-demand video, live streaming, real-time video, and video analytics, used to ingest, transcode, store, deliver, and measure video inside applications without managing video infrastructure. The Mux platform is delivered through two product families: Mux Video (ingest, asset management, live streams, playback IDs, signed URLs, and Mux Player) and Mux Data (QoE analytics for any HTML5 video player). All Mux REST APIs are served from https://api.mux.com, authenticated via HTTP Basic auth using a Mux Access Token ID and Secret, and fully described by an OpenAPI specification.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mux/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mux/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Video
- Streaming
- Live Streaming
- Video Analytics
- QoE
- Video On Demand
- Transcoding
- Mux Player

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Mux Video API

REST API for ingesting, transcoding, storing, and delivering on-demand and live video. Provides endpoints for direct uploads, assets, playback IDs, signing keys, live streams, simulcast targets, transcription, and webhooks. Authenticated via HTTP Basic auth using a Mux Access Token ID and Secret.

- **Human URL:** [https://www.mux.com/docs/api-reference](https://www.mux.com/docs/api-reference)
- **Base URL:** `https://api.mux.com`

#### Tags

- Video
- Streaming
- Live
- VOD
- Transcoding

#### Properties

- [Documentation](https://www.mux.com/docs/api-reference)
- [OpenAPI](https://www.mux.com/api-spec.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://www.mux.com/docs/core/make-api-requests)
- [Getting Started](https://www.mux.com/docs/core/mux-fundamentals)
- [Postman Collection](collections/mux.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mux.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mux Data API

REST API for Mux Data, providing video Quality of Experience (QoE) analytics across any HTML5 player. Endpoints cover environments, filters, metrics, video views, exports, alerts, and real-time data. Authenticated via HTTP Basic auth with a Mux Access Token ID and Secret.

- **Human URL:** [https://www.mux.com/docs/api-reference](https://www.mux.com/docs/api-reference)
- **Base URL:** `https://api.mux.com`

#### Tags

- Video Analytics
- QoE
- Monitoring
- Mux Data

#### Properties

- [Documentation](https://www.mux.com/docs/api-reference)
- [OpenAPI](https://www.mux.com/api-spec.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mux.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mux.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/mux)
- [Website](https://www.mux.com)
- [Documentation](https://www.mux.com/docs)
- [GitHub Organization](https://github.com/muxinc)
- [OpenAPI](https://www.mux.com/api-spec.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Pricing](https://www.mux.com/pricing)
- [Sign Up](https://dashboard.mux.com/signup)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
