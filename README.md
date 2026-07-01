# Maven AGI (maven-agi)

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
