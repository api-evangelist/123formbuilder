# 123FormBuilder

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

123FormBuilder is an online form, survey, and workflow builder used to collect, route, and
integrate submission data across websites, customer portals, and back-office systems with
no-code design and HIPAA-ready configurations. The 123FormBuilder REST API v2 enables
programmatic access to forms, fields, submissions, groups, users, and accounts. Clients
authenticate by exchanging credentials at POST /token for a JWT and pass the token as a
query parameter on subsequent requests. Separate US and EU regional base URLs are provided.

**Areas:** Online Forms · Form Builder · Surveys · Workflows · Data Collection · Submissions · Webhook · HIPAA · GDPR · Payments

## 123FormBuilder on APIs.io

Everything profiled for 123FormBuilder is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/123formbuilder/](https://apis.io/providers/123formbuilder/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [123FormBuilder Accounts API](https://apis.io/apis/123formbuilder/123formbuilder-accounts-api/) — Create and update billable accounts.
- [123FormBuilder Forms API](https://apis.io/apis/123formbuilder/123formbuilder-forms-api/) — Create, list, read, update, and delete forms, fields, and submissions.
- [123FormBuilder Groups API](https://apis.io/apis/123formbuilder/123formbuilder-groups-api/) — Organize forms into groups and share groups with subusers.
- [123FormBuilder Login API](https://apis.io/apis/123formbuilder/123formbuilder-login-api/) — JWT issuance, refresh, and invalidation.
- [123FormBuilder Users API](https://apis.io/apis/123formbuilder/123formbuilder-users-api/) — Manage subusers, their permissions, and master account info.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (6)

Multi-step workflows that chain operations into a business task.

- [123FormBuilder Authenticate and List Forms](https://apis.io/arazzos/123formbuilder/123formbuilder-authenticate-and-list-forms-workflow/)
- [123FormBuilder Browse a Group's Forms](https://apis.io/arazzos/123formbuilder/123formbuilder-browse-group-forms-workflow/)
- [123FormBuilder Create a Form Inside a New Group](https://apis.io/arazzos/123formbuilder/123formbuilder-create-form-in-group-workflow/)
- [123FormBuilder Inspect a Form End to End](https://apis.io/arazzos/123formbuilder/123formbuilder-inspect-form-workflow/)
- [123FormBuilder Moderate a Submission](https://apis.io/arazzos/123formbuilder/123formbuilder-moderate-submission-workflow/)
- [123FormBuilder Review a Form Submission](https://apis.io/arazzos/123formbuilder/123formbuilder-review-submission-workflow/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [123Formbuilder Agentic Access](https://apis.io/agentic-access/123formbuilder/123formbuilder-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [Account](https://apis.io/schemas/123formbuilder/123formbuilder-rest-api-v2-account/)
- [Field](https://apis.io/schemas/123formbuilder/123formbuilder-rest-api-v2-field/)
- [Form](https://apis.io/schemas/123formbuilder/123formbuilder-rest-api-v2-form/)
- [Group](https://apis.io/schemas/123formbuilder/123formbuilder-rest-api-v2-group/)
- [Submission](https://apis.io/schemas/123formbuilder/123formbuilder-rest-api-v2-submission/)
- [User](https://apis.io/schemas/123formbuilder/123formbuilder-rest-api-v2-user/)

#### JSON Structure (6)

Data models expressed in JSON Structure.

- [123Formbuilder Rest Api V2 Account Structure](https://apis.io/json-structure/123formbuilder/123formbuilder-rest-api-v2-account-structure/)
- [123Formbuilder Rest Api V2 Field Structure](https://apis.io/json-structure/123formbuilder/123formbuilder-rest-api-v2-field-structure/)
- [123Formbuilder Rest Api V2 Form Structure](https://apis.io/json-structure/123formbuilder/123formbuilder-rest-api-v2-form-structure/)
- [123Formbuilder Rest Api V2 Group Structure](https://apis.io/json-structure/123formbuilder/123formbuilder-rest-api-v2-group-structure/)
- [123Formbuilder Rest Api V2 Submission Structure](https://apis.io/json-structure/123formbuilder/123formbuilder-rest-api-v2-submission-structure/)
- [123Formbuilder Rest Api V2 User Structure](https://apis.io/json-structure/123formbuilder/123formbuilder-rest-api-v2-user-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [123Formbuilder Context](https://apis.io/jsonld/123formbuilder/123formbuilder-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [123Formbuilder Vocabulary](https://apis.io/vocabularies/123formbuilder/123formbuilder-vocabulary/)

#### Examples (7)

Example requests and responses.

- [123Formbuilder Rest Api V2 Account Example](https://apis.io/examples/123formbuilder/123formbuilder-rest-api-v2-account-example/)
- [123Formbuilder Rest Api V2 Field Example](https://apis.io/examples/123formbuilder/123formbuilder-rest-api-v2-field-example/)
- [123Formbuilder Rest Api V2 Form Example](https://apis.io/examples/123formbuilder/123formbuilder-rest-api-v2-form-example/)
- [123Formbuilder Rest Api V2 Group Example](https://apis.io/examples/123formbuilder/123formbuilder-rest-api-v2-group-example/)
- [123Formbuilder Rest Api V2 Submission Example](https://apis.io/examples/123formbuilder/123formbuilder-rest-api-v2-submission-example/)
- [123Formbuilder Rest Api V2 Token Example](https://apis.io/examples/123formbuilder/123formbuilder-rest-api-v2-token-example/)
- [123Formbuilder Rest Api V2 User Example](https://apis.io/examples/123formbuilder/123formbuilder-rest-api-v2-user-example/)

#### Collections (7)

Postman and Open Collection request collections.

- [123FormBuilder REST API v2 Accounts API](https://apis.io/collections/123formbuilder/open-123formbuilder-accounts-api/)
- [123FormBuilder REST API v2 Accounts Forms API](https://apis.io/collections/123formbuilder/open-123formbuilder-forms-api/)
- [123FormBuilder REST API v2 Accounts Groups API](https://apis.io/collections/123formbuilder/open-123formbuilder-groups-api/)
- [123FormBuilder REST API v2 Accounts Login API](https://apis.io/collections/123formbuilder/open-123formbuilder-login-api/)
- [123FormBuilder REST API v2](https://apis.io/collections/123formbuilder/open-123formbuilder-rest-api-v2/)
- [123FormBuilder REST API v2 Accounts Users API](https://apis.io/collections/123formbuilder/open-123formbuilder-users-api/)
- [123FormBuilder REST API v2](https://apis.io/collections/123formbuilder/postman-123formbuilder-rest-api-v2/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [123FormBuilder — jsonschema rules](https://apis.io/rules/123formbuilder/123formbuilder-jsonschema-spectral-rules/)
- [123FormBuilder API Rules](https://apis.io/rules/123formbuilder/123formbuilder-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [123Formbuilder Authentication](https://apis.io/security/123formbuilder/123formbuilder-authentication/)
- [123Formbuilder Domain Security](https://apis.io/security/123formbuilder/123formbuilder-domain-security/)
- [123Formbuilder Vulnerability Disclosure](https://apis.io/security/123formbuilder/123formbuilder-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [123Formbuilder Plans Pricing](https://apis.io/plans/123formbuilder/123formbuilder-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [123Formbuilder Rate Limits](https://apis.io/rate-limits/123formbuilder/123formbuilder-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [123Formbuilder Finops](https://apis.io/finops/123formbuilder/123formbuilder-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.123formbuilder.com)
- [Documentation](https://www.123formbuilder.com/developer/api-v2/)
- [Pricing](https://www.123formbuilder.com/pricing/)
- [Support](https://www.123formbuilder.com/contact-us/)
- [Blog](https://www.123formbuilder.com/blog/)
- [Compliance](https://www.123formbuilder.com/gdpr-compliance/)
- [Terms of service](https://www.123formbuilder.com/terms-of-service/)
- [Privacy policy](https://www.123formbuilder.com/privacy/)
- [GitHub](https://github.com/123formbuilder)

## API Evangelist rating

**Kin Score 52.5** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 68.6 |
| Contract governance | 27.3 |
| Operational transparency | 21.1 |
| Developer ergonomics | 53.6 |
| Access clarity | 53.9 |

**Agent readiness 30.9** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
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
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 32.1** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/123formbuilder/](https://apis.io/providers/123formbuilder/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for 123FormBuilder: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/123formbuilder/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
