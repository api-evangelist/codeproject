# CodeProject (codeproject)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

CodeProject is a long-running online community for software developers founded in 1999, hosting hundreds of thousands of developer-contributed articles, tutorials, code samples, tips, and a Q&A forum across a broad range of programming topics. It exposes a public REST API at api.codeproject.com (V1 Beta) for read access to articles, forum messages, questions, and authenticated user data, secured by OAuth 2.0 Bearer Tokens. CodeProject also operates CodeProject.AI Server, a free, open-source, self-hosted AI service that exposes object detection, face recognition, license-plate reading (ALPR), scene classification, image processing, audio classification, text analytics, and YOLOv5 training through a local HTTP REST API. CodeProject.AI is widely integrated with home-automation and surveillance platforms (Blue Iris, Home Assistant, Agent DVR).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/codeproject/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/codeproject/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- AI
- Articles
- Community
- Computer Vision
- Developer Community
- Face Recognition
- Forum
- Knowledge Base
- License Plate Recognition
- Object Detection
- Q&A
- Software Development
- Tutorials

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### CodeProject REST API

OAuth 2.0 protected REST API providing read access to CodeProject articles, forum messages, questions, and authenticated user data (answers, articles, blog posts, bookmarks, notifications, profile, reputation, tips). Supports Client Credentials, Authorization Code, and Implicit Grant flows. Tokens are issued by the CodeProject identity server and presented as Bearer tokens in the Authorization header.

- **Human URL:** [https://api.codeproject.com/Help](https://api.codeproject.com/Help)
- **Base URL:** `https://api.codeproject.com`

#### Tags

- Articles
- Community
- Forum
- OAuth2
- Q&A
- Read-Only

#### Properties

- [Documentation](https://api.codeproject.com/Help)
- [Base U R L](https://api.codeproject.com/)
- [Samples](https://api.codeproject.com/Samples)
- [Article](https://www.codeproject.com/Articles/986918/The-CodeProject-API-Part)
- [Article](https://www.codeproject.com/articles/989081/the-code-project-api-part-getting-some-rest)
- [OpenAPI](openapi/codeproject-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/codeproject-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/codeproject-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CodeProject.AI Server API

Self-hosted AI service that exposes computer vision (object detection, scene, face, ALPR), image processing (background removal, cartoonise, portrait filter, super-resolution), audio classification, NLP (sentiment, summarization), and YOLOv5 training endpoints through a local HTTP REST API. All endpoints are POST and accept multipart uploads. The server runs on Windows, macOS, Linux, Raspberry Pi, Jetson, and OrangePi, plus Docker images, and integrates with Blue Iris, Home Assistant, and Agent DVR for surveillance use cases.

- **Human URL:** [https://www.codeproject.com/AI/](https://www.codeproject.com/AI/)
- **Base URL:** `http://localhost:32168`

#### Tags

- AI
- Audio
- Computer Vision
- Face Recognition
- Image Processing
- License Plate Recognition
- Object Detection
- On-Premise
- Self-Hosted
- Text
- Training

#### Properties

- [Portal](https://www.codeproject.com/AI/)
- [Documentation](https://codeproject.github.io/codeproject.ai/)
- [API Reference](https://codeproject.github.io/codeproject.ai/api/api_reference.html)
- [Source Code](https://github.com/codeproject/CodeProject.AI-Server)
- [OpenAPI](openapi/codeproject-ai-server-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/codeproject-ai-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/codeproject-ai-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/the-code-project)
- [Website](https://www.codeproject.com/)
- [Documentation](https://api.codeproject.com/Help)
- [Samples](https://api.codeproject.com/Samples)
- [Terms of Service](https://www.codeproject.com/Terms)
- [Privacy Policy](https://www.codeproject.com/privacy)
- [Forum](https://www.codeproject.com/Lounge.aspx)
- [Tutorials](https://www.codeproject.com/KB/)
- [Support](https://www.codeproject.com/Questions/)
- [Newsletter](https://www.codeproject.com/newsletters)
- [Portal](https://codeproject.ai/)
- [Git Hub](https://github.com/codeproject)
- [JSON-LD](json-ld/codeproject-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/codeproject-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
