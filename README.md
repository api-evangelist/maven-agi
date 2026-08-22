# Maven AGI (maven-agi)

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

Maven AGI is an enterprise AI agent platform for customer experience. Its AI agents answer questions, take actions, and improve with every interaction across chat, email, voice, and SMS. The Maven Platform API lets developers build apps that manage conversations, knowledge, actions, users, events, and triggers, authenticated with an App ID and App Secret scoped to an organization and agent.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/maven-agi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/maven-agi/refs/heads/main/apis.yml)

## Authentication

The Maven Platform API uses HTTP Basic authentication with your **App ID** as the username and **App Secret** as the password, obtained from the Developer Portal. Every request also sends `X-Organization-Id` and `X-Agent-Id` headers to scope the call to a specific organization and agent.

- **Base URL (Production):** `https://www.mavenagi-apis.com/v1`
- **Base URL (Staging):** `https://www.staging.mavenagi-apis.com/v1`

## Tags

- AI
- Agents
- Customer Support
- Customer Experience
- Conversational AI
- Knowledge

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Maven AGI Conversation API

Initialize conversations, append messages, ask questions of the agent (streaming or non-streaming), categorize, submit action forms, manage conversation metadata, deliver messages, search, and export conversations.

- **Human URL:** [https://docs.mavenagi.com/maven-platform](https://docs.mavenagi.com/maven-platform)
- **Base URL:** `https://www.mavenagi-apis.com/v1`

#### Tags

- Conversations
- Ask
- Messages
- Chat

#### Properties

- [Documentation](https://docs.mavenagi.com)
- [API Reference](https://github.com/mavenagi/mavenagi-python/blob/main/reference.md)
- [OpenAPI](openapi/maven-agi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maven-agi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maven-agi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maven AGI Knowledge API

Create and version knowledge bases, add and refresh knowledge documents, and search knowledge bases and documents that ground the agent's answers.

- **Human URL:** [https://docs.mavenagi.com/maven-platform](https://docs.mavenagi.com/maven-platform)
- **Base URL:** `https://www.mavenagi-apis.com/v1`

#### Tags

- Knowledge
- Documents
- Knowledge Bases
- RAG

#### Properties

- [Documentation](https://docs.mavenagi.com)
- [API Reference](https://github.com/mavenagi/mavenagi-python/blob/main/reference.md)
- [OpenAPI](openapi/maven-agi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maven-agi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maven-agi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maven AGI Actions API

Register, search, retrieve, patch, and delete Actions - the parameterized operations against external business systems that agents can call to get work done during a conversation.

- **Human URL:** [https://docs.mavenagi.com/maven-platform](https://docs.mavenagi.com/maven-platform)
- **Base URL:** `https://www.mavenagi-apis.com/v1`

#### Tags

- Actions
- Tools
- Function Calling

#### Properties

- [Documentation](https://docs.mavenagi.com)
- [API Reference](https://github.com/mavenagi/mavenagi-python/blob/main/reference.md)
- [OpenAPI](openapi/maven-agi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maven-agi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maven-agi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maven AGI Users API

Create or update users, retrieve and delete users, and read and search the resolved agent-user identities associated with an agent.

- **Human URL:** [https://docs.mavenagi.com/maven-platform](https://docs.mavenagi.com/maven-platform)
- **Base URL:** `https://www.mavenagi-apis.com/v1`

#### Tags

- Users
- Agent Users
- Identity

#### Properties

- [Documentation](https://docs.mavenagi.com)
- [API Reference](https://github.com/mavenagi/mavenagi-python/blob/main/reference.md)
- [OpenAPI](openapi/maven-agi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maven-agi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maven-agi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maven AGI Agents API

Create, list, retrieve, patch, and delete agents within an organization, the top-level configuration that defines an AI agent's behavior and scope.

- **Human URL:** [https://docs.mavenagi.com/maven-platform](https://docs.mavenagi.com/maven-platform)
- **Base URL:** `https://www.mavenagi-apis.com/v1`

#### Tags

- Agents
- Organizations
- Configuration

#### Properties

- [Documentation](https://docs.mavenagi.com)
- [API Reference](https://github.com/mavenagi/mavenagi-python/blob/main/reference.md)
- [OpenAPI](openapi/maven-agi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maven-agi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maven-agi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maven AGI Events API

Create, retrieve, search, and export events - the timeline of activity and signals emitted by agents and users that feed analytics and triggers.

- **Human URL:** [https://docs.mavenagi.com/maven-platform](https://docs.mavenagi.com/maven-platform)
- **Base URL:** `https://www.mavenagi-apis.com/v1`

#### Tags

- Events
- Analytics
- Timeline

#### Properties

- [Documentation](https://docs.mavenagi.com)
- [API Reference](https://github.com/mavenagi/mavenagi-python/blob/main/reference.md)
- [OpenAPI](openapi/maven-agi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maven-agi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maven-agi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maven AGI Triggers API

Create or update, retrieve, patch, search, and delete event triggers that automate downstream behavior in response to conversation and event activity.

- **Human URL:** [https://docs.mavenagi.com/maven-platform](https://docs.mavenagi.com/maven-platform)
- **Base URL:** `https://www.mavenagi-apis.com/v1`

#### Tags

- Triggers
- Automation
- Webhooks

#### Properties

- [Documentation](https://docs.mavenagi.com)
- [API Reference](https://github.com/mavenagi/mavenagi-python/blob/main/reference.md)
- [OpenAPI](openapi/maven-agi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maven-agi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maven-agi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maven AGI App Settings API

Read and patch the per-app settings that a Maven app uses to store its installation configuration and search across app-scoped settings.

- **Human URL:** [https://docs.mavenagi.com/maven-platform](https://docs.mavenagi.com/maven-platform)
- **Base URL:** `https://www.mavenagi-apis.com/v1`

#### Tags

- Apps
- Settings
- Configuration

#### Properties

- [Documentation](https://docs.mavenagi.com)
- [API Reference](https://github.com/mavenagi/mavenagi-python/blob/main/reference.md)
- [OpenAPI](openapi/maven-agi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maven-agi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maven-agi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maven AGI Analytics API

Query conversation, event, feedback, and agent-user tables and charts to build reporting on agent performance, deflection, and customer outcomes.

- **Human URL:** [https://docs.mavenagi.com/maven-platform](https://docs.mavenagi.com/maven-platform)
- **Base URL:** `https://www.mavenagi-apis.com/v1`

#### Tags

- Analytics
- Reporting
- Charts

#### Properties

- [Documentation](https://docs.mavenagi.com)
- [API Reference](https://github.com/mavenagi/mavenagi-python/blob/main/reference.md)
- [OpenAPI](openapi/maven-agi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maven-agi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maven-agi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/mavenagi)
- [LinkedIn](https://www.linkedin.com/company/mavenagi)
- [Website](https://www.mavenagi.com)
- [Documentation](https://docs.mavenagi.com)
- [Plans](plans/maven-agi-plans-pricing.yml)
- [Rate Limits](rate-limits/maven-agi-rate-limits.yml)
- [Fin Ops](finops/maven-agi-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
