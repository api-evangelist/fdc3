# FDC3 (fdc3)

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
