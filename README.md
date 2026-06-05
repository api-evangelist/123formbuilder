# 123FormBuilder (123formbuilder)

123FormBuilder is an online form, survey, and workflow builder used to collect, route, and
integrate submission data across websites, customer portals, and back-office systems with
no-code design and HIPAA-ready configurations. The 123FormBuilder REST API v2 enables
programmatic access to forms, fields, submissions, groups, users, and accounts. Clients
authenticate by exchanging credentials at POST /token for a JWT and pass the token as a
query parameter on subsequent requests. Separate US and EU regional base URLs are provided.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/123formbuilder/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/123formbuilder/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Online Forms
- Form Builder
- Surveys
- Workflow
- Data Collection
- Submissions
- Webhooks
- HIPAA
- GDPR
- Payments

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-28

## APIs

### 123FormBuilder REST API v2

REST API v2 for managing forms, fields, submissions, groups, users, and accounts in
123FormBuilder. Requests authenticate with a JWT issued by POST /token and passed as the
JWT query parameter on subsequent calls. Separate US (api.123formbuilder.com) and EU
(eu-api.123formbuilder.com) regional base URLs are offered; account region determines
which to use. Common workflows include listing and filtering forms, paging submissions,
bulk-deleting forms, registering group-level webhooks, and provisioning subusers with
fine-grained permission flags.

- **Human URL:** [https://www.123formbuilder.com/developer/api-v2/](https://www.123formbuilder.com/developer/api-v2/)
- **Base URL:** `https://api.123formbuilder.com/v2`

#### Tags

- Online Forms
- Form Builder
- Submissions
- Webhooks
- JWT
- Forms
- Groups
- Users
- Accounts

#### Properties

- [Documentation](https://www.123formbuilder.com/developer/api-v2/)
- [API Reference](https://www.123formbuilder.com/developer/api-v2-forms/)
- [Authentication](https://www.123formbuilder.com/developer/api-v2-authentication/)
- [Quickstart](https://www.123formbuilder.com/docs/how-to-retrieve-data-through-api/)
- [Knowledge Center](https://www.123formbuilder.com/docs/apidocumentation/)
- [Errors](https://www.123formbuilder.com/docs/api-responses/)
- [Regions](https://www.123formbuilder.com/developer/api-v2/)
- [Rate Limits](rate-limits/123formbuilder-rate-limits.yml)
- [OpenAPI](openapi/123formbuilder-rest-api-v2-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/123formbuilder-rest-api-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/123formbuilder-rest-api-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/123formbuilder-rest-api-v2-form-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/123formbuilder-rest-api-v2-field-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/123formbuilder-rest-api-v2-submission-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/123formbuilder-rest-api-v2-group-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/123formbuilder-rest-api-v2-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/123formbuilder-rest-api-v2-account-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/123formbuilder-rest-api-v2-form-structure.json)
- [JSON Structure](json-structure/123formbuilder-rest-api-v2-field-structure.json)
- [JSON Structure](json-structure/123formbuilder-rest-api-v2-submission-structure.json)
- [JSON Structure](json-structure/123formbuilder-rest-api-v2-group-structure.json)
- [JSON Structure](json-structure/123formbuilder-rest-api-v2-user-structure.json)
- [JSON Structure](json-structure/123formbuilder-rest-api-v2-account-structure.json)
- [Example](examples/123formbuilder-rest-api-v2-form-example.json)
- [Example](examples/123formbuilder-rest-api-v2-field-example.json)
- [Example](examples/123formbuilder-rest-api-v2-submission-example.json)
- [Example](examples/123formbuilder-rest-api-v2-group-example.json)
- [Example](examples/123formbuilder-rest-api-v2-user-example.json)
- [Example](examples/123formbuilder-rest-api-v2-account-example.json)
- [Example](examples/123formbuilder-rest-api-v2-token-example.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Website](https://www.123formbuilder.com)
- [GitHub Organization](https://github.com/123formbuilder)
- [GitHub Repository](https://github.com/123FormBuilder/123contacform-api-v1-php)
- [GitHub Repository](https://github.com/123FormBuilder/wix-code)
- [LinkedIn](https://www.linkedin.com/company/123formbuilder)
- [Developer Portal](https://www.123formbuilder.com/developer/)
- [Documentation](https://www.123formbuilder.com/developer/api-v2/)
- [Knowledge Center](https://www.123formbuilder.com/docs/all-categories/developers/)
- [Sign Up](https://www.123formbuilder.com/sign-up/)
- [Login](https://www.123formbuilder.com/login/)
- [Pricing](https://www.123formbuilder.com/pricing/)
- [Plans](plans/123formbuilder-plans-pricing.yml)
- [Terms of Service](https://www.123formbuilder.com/terms-of-service/)
- [Privacy Policy](https://www.123formbuilder.com/privacy/)
- [Compliance](https://www.123formbuilder.com/gdpr-compliance/)
- [Blog](https://www.123formbuilder.com/blog/)
- [Support](https://www.123formbuilder.com/contact-us/)
- [Integrations](https://www.123formbuilder.com/integrations/)
- [JSON-LD](json-ld/123formbuilder-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/123formbuilder-rules.yml)
- [Vocabulary](vocabulary/123formbuilder-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
