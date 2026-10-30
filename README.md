# FDC3

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

**Areas:** Financial Services · Fintech · Desktop Interoperability · Open Standard · FINOS · Context Sharing · Intents

## FDC3 on APIs.io

Everything profiled for FDC3 is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/fdc3/](https://apis.io/providers/fdc3/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [FDC3 Desktop Agent API](https://apis.io/apis/fdc3/desktop-agent-api/) — The FDC3 Desktop Agent API is the primary interface for application interoperability on the financial desktop. It provides a JavaScript/TypeScript API that…
- [FDC3 App Directory API](https://apis.io/apis/fdc3/app-directory-api/) — The FDC3 App Directory (AppD) is a REST API standard for registering and discovering financial desktop applications. Desktop Agents query App Directories to…
- [FDC3 Context Data](https://apis.io/apis/fdc3/context-data/) — FDC3 Context Data defines a standard set of typed data structures used to carry information between financial applications when broadcasting or raising…
- [FDC3 Intents](https://apis.io/apis/fdc3/intents/) — FDC3 Intents are standardized verbs that applications use to request functionality from other applications on the financial desktop. Standard intents…
- [FDC3 Desktop Agent Bridging](https://apis.io/apis/fdc3/desktop-agent-bridging/) — FDC3 Desktop Agent Bridging (DAB) is a wire protocol that enables multiple Desktop Agent implementations to interoperate, allowing applications running…
- [FDC3 Application API](https://apis.io/apis/fdc3/fdc3-application-api/) — The Application API from FDC3 — 5 operation(s) for application.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Fdc3 Agentic Access](https://apis.io/agentic-access/fdc3/fdc3-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [Appd.Schema](https://apis.io/schemas/fdc3/appd.schema/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Fdc3 Context](https://apis.io/jsonld/fdc3/fdc3-context/)

#### Examples (1)

Example requests and responses.

- [Fdc3 Workbench App](https://apis.io/examples/fdc3/fdc3-workbench-app/)

#### Collections (1)

Postman and Open Collection request collections.

- [FDC3 Directory Application API](https://apis.io/collections/fdc3/open-fdc3-application-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [FDC3 — jsonschema rules](https://apis.io/rules/fdc3/fdc3-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Fdc3 Authentication](https://apis.io/security/fdc3/fdc3-authentication/)
- [Fdc3 Domain Security](https://apis.io/security/fdc3/fdc3-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Fdc3 Plans Pricing](https://apis.io/plans/fdc3/fdc3-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Fdc3 Rate Limits](https://apis.io/rate-limits/fdc3/fdc3-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Fdc3 Finops](https://apis.io/finops/fdc3/fdc3-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://fdc3.finos.org)
- [Documentation](https://fdc3.finos.org/docs/fdc3-intro)
- [Changelog](https://github.com/finos/FDC3/blob/main/CHANGELOG.md)
- [Blog](https://www.finos.org/blog)
- [Terms of service](https://github.com/finos/FDC3/blob/main/LICENSE.md)

## API Evangelist rating

**Kin Score 36.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 55.0 |
| Contract governance | 9.8 |
| Operational transparency | 39.5 |
| Developer ergonomics | 33.3 |
| Access clarity | 18.4 |

**Agent readiness 26.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 20.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/fdc3/](https://apis.io/providers/fdc3/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for FDC3: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/fdc3/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
