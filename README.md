# 123FormBuilder (123formbuilder)

123FormBuilder is an online form, survey, and workflow builder used to collect, route, and integrate submission data across websites, customer portals, and back-office systems with no-code design and HIPAA-ready configurations. The 123FormBuilder REST API v2 enables programmatic access to forms, fields, submissions, groups, users, and accounts. Clients authenticate by exchanging credentials at `POST /token` for a JWT and pass the token as a query parameter on subsequent requests. Separate US and EU regional base URLs are provided.

**URL:** [Visit APIs.json URL](https://www.123formbuilder.com/developer/api-v2/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- Online Forms, Form Builder, Surveys, Workflow, Data Collection, Submissions, Webhooks, HIPAA, GDPR, Payments

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-28

## APIs

### 123FormBuilder REST API v2

REST API v2 for managing forms, fields, submissions, groups, users, and accounts in 123FormBuilder. Requests authenticate with a JWT issued by `POST /token` and passed as the `JWT` query parameter on subsequent calls. Separate US (`api.123formbuilder.com`) and EU (`eu-api.123formbuilder.com`) regional base URLs are offered. The spec covers 26 operations across 5 tags (Login, Forms, Groups, Users, Accounts) and 14 schemas.

**Human URL:** [https://www.123formbuilder.com/developer/api-v2/](https://www.123formbuilder.com/developer/api-v2/)

**Base URL:** `https://api.123formbuilder.com/v2`

#### Tags

- Online Forms, Form Builder, Submissions, Webhooks, JWT, Forms, Groups, Users, Accounts

#### Properties

- [Documentation](https://www.123formbuilder.com/developer/api-v2/)
- [APIReference](https://www.123formbuilder.com/developer/api-v2-forms/)
- [Authentication](https://www.123formbuilder.com/developer/api-v2-authentication/)
- [Quickstart](https://www.123formbuilder.com/docs/how-to-retrieve-data-through-api/)
- [Errors](https://www.123formbuilder.com/docs/api-responses/)
- [Regions](https://www.123formbuilder.com/developer/api-v2/)
- [RateLimits](rate-limits/123formbuilder-rate-limits.yml)
- [OpenAPI](openapi/123formbuilder-rest-api-v2-openapi.yml)
- [NaftikoCapability — Forms](capabilities/forms.yaml)
- [NaftikoCapability — Groups](capabilities/groups.yaml)
- [NaftikoCapability — Users & Accounts](capabilities/users-accounts.yaml)

## Common Properties

- [Website](https://www.123formbuilder.com)
- [GitHubOrganization](https://github.com/123formbuilder)
- [DeveloperPortal](https://www.123formbuilder.com/developer/)
- [KnowledgeCenter](https://www.123formbuilder.com/docs/all-categories/developers/)
- [SignUp](https://www.123formbuilder.com/sign-up/)
- [Pricing](https://www.123formbuilder.com/pricing/) / [Plans (machine-readable)](plans/123formbuilder-plans-pricing.yml)
- [TermsOfService](https://www.123formbuilder.com/terms-of-service/) / [PrivacyPolicy](https://www.123formbuilder.com/privacy/)
- [Compliance](https://www.123formbuilder.com/gdpr-compliance/)
- [Blog](https://www.123formbuilder.com/blog/)
- [Support](https://www.123formbuilder.com/contact-us/)
- [Integrations](https://www.123formbuilder.com/integrations/)
- [LinkedIn](https://www.linkedin.com/company/123formbuilder)

## GitHub Repositories

| Repo | Language | Notes |
|------|----------|-------|
| [123contacform-api-v1-php](https://github.com/123FormBuilder/123contacform-api-v1-php) | PHP | Legacy v1 PHP samples (last updated 2017). |
| [wix-code](https://github.com/123FormBuilder/wix-code) | JavaScript | Pushing 123FormBuilder submissions to Wix Code databases. |

No official SDKs, MCP server, or Claude Code skill are published by the provider as of 2026-05-28. The community-maintained `@pipedream/a123formbuilder` package provides serverless connector components.

## Features

| Name | Description |
|------|-------------|
| No-Code Form Authoring | Drag-and-drop builder with 25+ field types including signature, file upload, formula, and product fields. |
| Multi-Page Forms | Break long surveys into multiple pages with conditional logic to control flow. |
| Conditional Logic | Show, hide, or branch fields based on respondent answers. |
| Webhooks | Forward submissions to external endpoints via group-level webhook URLs (max 10 per form). |
| Submission Approvals | Manually review and approve submissions before they continue downstream. |
| HIPAA-Ready Configurations | Diamond and Enterprise tiers offer HIPAA-eligible form configurations for healthcare data collection. |
| GDPR Controls | Built-in consent fields, data retention controls, and EU regional residency. |
| Regional Endpoints | Separate US (api.123formbuilder.com) and EU (eu-api.123formbuilder.com) base URLs. |
| Subuser Permissions | Granular per-subuser flags for create/duplicate/delete form, manage groups, and manage users. |
| White Label | Custom form domains, branding removal, and theme editing on Diamond and Enterprise. |
| Multi-Language Forms | Publish forms in multiple languages from a single source. |
| Payment Collection | Integrate PayPal, Stripe, Square, Authorize.Net, Braintree, and PayU as form fields. |

## Use Cases

| Name | Description |
|------|-------------|
| Lead Capture and CRM Sync | Capture leads from web forms and route them to CRMs via webhook or native integrations. |
| Customer Feedback and NPS | Run NPS, CSAT, and Likert-scale surveys with conditional follow-up questions. |
| Event Registration and Payment | Collect attendee data, accept payments, and trigger confirmation workflows. |
| HIPAA-Eligible Intake Forms | Capture patient intake data on Diamond/Enterprise configurations with HIPAA-ready settings. |
| Order and Quote Requests | Build product configurators with formula fields and route requests to sales teams. |
| Employee and Job Application Forms | Standardize HR intake with permission-gated subuser access to specific groups. |
| Survey Data Pipelines | Programmatically page submissions via REST API v2 into data warehouses and BI tools. |

## Integrations

Salesforce, HubSpot, Mailchimp, ActiveCampaign, Campaign Monitor, PayPal, Stripe, Square, Authorize.Net, Braintree, PayU, Zapier, Webhooks, Marketo, Google Sheets, Dropbox, Evernote, Smartsheet, Pipedrive, Zendesk, Wix, Shopify, NationBuilder, Pipedream.

## Solutions

| Name | Description |
|------|-------------|
| Healthcare Forms (HIPAA) | HIPAA-ready intake, consent, and patient-survey forms on Diamond/Enterprise. |
| Education Surveys | Quizzes, course evaluations, and admissions forms with multi-language support. |
| Nonprofit Donations | Donation forms with payment gateway integration and donor CRM sync. |
| Real Estate Lead Capture | Property inquiry forms with CRM and email-marketing integration. |
| Enterprise Workflow | SLA-backed Enterprise tier with SSO, dedicated account manager, and Virtual Database Manager. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [123FormBuilder REST API v2 (OpenAPI 3.0)](openapi/123formbuilder-rest-api-v2-openapi.yml) — 26 operations across Login, Forms, Groups, Users, and Accounts; converted from the provider's Swagger 2.0 spec at `https://www.123formbuilder.com/wp-content/uploads/sites/5/2024/01/swagger-4.json`.

### JSON Schema

- [Form](json-schema/123formbuilder-rest-api-v2-form-schema.json)
- [Field](json-schema/123formbuilder-rest-api-v2-field-schema.json)
- [Submission](json-schema/123formbuilder-rest-api-v2-submission-schema.json)
- [Group](json-schema/123formbuilder-rest-api-v2-group-schema.json)
- [User](json-schema/123formbuilder-rest-api-v2-user-schema.json)
- [Account](json-schema/123formbuilder-rest-api-v2-account-schema.json)

### JSON Structure

- [Form](json-structure/123formbuilder-rest-api-v2-form-structure.json)
- [Field](json-structure/123formbuilder-rest-api-v2-field-structure.json)
- [Submission](json-structure/123formbuilder-rest-api-v2-submission-structure.json)
- [Group](json-structure/123formbuilder-rest-api-v2-group-structure.json)
- [User](json-structure/123formbuilder-rest-api-v2-user-structure.json)
- [Account](json-structure/123formbuilder-rest-api-v2-account-structure.json)

### JSON-LD

- [123FormBuilder Context](json-ld/123formbuilder-context.jsonld)

### Examples

- [Form](examples/123formbuilder-rest-api-v2-form-example.json)
- [Field](examples/123formbuilder-rest-api-v2-field-example.json)
- [Submission](examples/123formbuilder-rest-api-v2-submission-example.json)
- [Group](examples/123formbuilder-rest-api-v2-group-example.json)
- [User](examples/123formbuilder-rest-api-v2-user-example.json)
- [Account](examples/123formbuilder-rest-api-v2-account-example.json)
- [Token](examples/123formbuilder-rest-api-v2-token-example.json)

## Capabilities

Naftiko capabilities organized as one self-contained file per business surface, each exposing both REST and MCP adapters.

| Capability | Operations | MCP Tools |
|------------|-----------|-----------|
| [Forms](capabilities/forms.yaml) | 11 — CRUD over forms, bulk delete, fields, and submissions lifecycle | 11 |
| [Groups](capabilities/groups.yaml) | 7 — group CRUD, group→forms listing, share/unshare with subusers | 7 |
| [Users & Accounts](capabilities/users-accounts.yaml) | 8 — login (token, refresh, invalidate), subuser CRUD, account provisioning | 8 |

## Vocabulary

- [123FormBuilder Vocabulary](vocabulary/123formbuilder-vocabulary.yaml) — Operational and capability taxonomy covering 7 resource families, 11 actions, JWT-query authentication, and 5 capability surfaces.

## Rules

- [123FormBuilder Spectral Rules](rules/123formbuilder-rules.yml) — Spectral ruleset enforcing 123FormBuilder REST API v2 conventions (info, servers, tags, operations, security, responses, paths, schemas).

## Plans, Rate Limits & FinOps

- [Plans & Pricing](plans/123formbuilder-plans-pricing.yml) — Free, Gold ($37/user/mo), Platinum ($49/user/mo), Diamond ($99/user/mo), and Enterprise (contract). Free plan is capped at 100 API calls/day.
- [Rate Limits](rate-limits/123formbuilder-rate-limits.yml) — Documented per-plan daily API quotas, 10-webhooks-per-form ceiling, HTTPS-only enforcement.
- [FinOps](finops/123formbuilder-finops.yml) — FOCUS-aligned cost allocation, unit economics (cost per submission, cost per active form, cost per API request), and optimization levers.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
