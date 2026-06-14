# FDC3 (fdc3)

FDC3 (Financial Desktop Connectivity and Collaboration Consortium) is an open standard hosted by FINOS for interoperability between financial desktop applications. The standard defines how applications launch other apps, share typed context data, raise and resolve intents across the financial desktop, and register themselves in an App Directory. FDC3 eliminates the need for custom bilateral agreements between software vendors and enables plug-and-play integration workflows for financial services firms. Current version is 2.2, licensed under the Community Specification License 1.0 with code released under Apache 2.0.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fdc3/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fdc3/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Financial Services
- Fintech
- Desktop Interoperability
- Open Standard
- FINOS
- Context Sharing
- Intents

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### FDC3 Desktop Agent API

The FDC3 Desktop Agent API is the primary interface for application interoperability on the financial desktop. It provides a JavaScript/TypeScript API that applications use to open other applications, raise intents to request functionality from peer apps, broadcast typed context data on channels, listen for incoming context and intents, discover available applications and their capabilities, and create private two-party communication channels.

- **Human URL:** [https://fdc3.finos.org/docs/api/spec](https://fdc3.finos.org/docs/api/spec)

### FDC3 App Directory API

The FDC3 App Directory (AppD) is a REST API standard for registering and discovering financial desktop applications. Desktop Agents query App Directories to resolve application definitions when launching apps or resolving intents. The v2 endpoints are the current standard, supporting retrieval of all app definitions and lookup by appId. Authentication is supported via HTTP Authorization Bearer JWT tokens.

- **Human URL:** [https://fdc3.finos.org/docs/app-directory/spec](https://fdc3.finos.org/docs/app-directory/spec)

### FDC3 Context Data

FDC3 Context Data defines a standard set of typed data structures used to carry information between financial applications when broadcasting or raising intents. Context types include instruments, positions, portfolios, contacts, organizations, orders, charts, country, currency, date range, email, and more. Each context type has a JSON schema definition.

- **Human URL:** [https://fdc3.finos.org/docs/context/spec](https://fdc3.finos.org/docs/context/spec)

### FDC3 Intents

FDC3 Intents are standardized verbs that applications use to request functionality from other applications on the financial desktop. Standard intents include ViewChart, ViewQuote, ViewNews, ViewAnalysis, ViewInstrument, ViewHoldings, ViewOrders, ViewResearch, ViewProfile, ViewInteractions, ViewMessages, ViewChat, StartCall, StartChat, StartEmail, CreateInteraction, and CreateOrUpdateProfile.

- **Human URL:** [https://fdc3.finos.org/docs/intents/spec](https://fdc3.finos.org/docs/intents/spec)

### FDC3 Desktop Agent Bridging

FDC3 Desktop Agent Bridging (DAB) is a wire protocol that enables multiple Desktop Agent implementations to interoperate, allowing applications running under different Desktop Agents to share context and raise intents with each other. The bridging specification defines a WebSocket-based protocol for agent-to-agent communication.

- **Human URL:** [https://fdc3.finos.org/docs/agent-bridging/spec](https://fdc3.finos.org/docs/agent-bridging/spec)

## Common Properties

| Type | URL |
|------|-----|
| Website | https://fdc3.finos.org |
| Documentation | https://fdc3.finos.org/docs/fdc3-intro |
| GitHubOrg | https://github.com/finos |
| GitHubRepository | https://github.com/finos/FDC3 |
| Slack | https://finos-lf.slack.com/messages/fdc3 |
| MailingList | mailto:fdc3+subscribe@finos.org |
| Community | https://www.finos.org/community |
| Blog | https://www.finos.org/blog |
| Changelog | https://github.com/finos/FDC3/blob/main/CHANGELOG.md |
| License | https://github.com/finos/FDC3/blob/main/LICENSE.md |
| Contributing | https://github.com/finos/FDC3/blob/main/CONTRIBUTING.md |
| Status | https://github.com/finos/FDC3/releases |
