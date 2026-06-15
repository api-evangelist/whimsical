# Whimsical (whimsical)

Whimsical is a visual workspace for boards, mind maps, flowcharts, wireframes, and documents. The Whimsical API is in limited beta with read-only endpoints for users, teams, comments, and files; user provisioning is exposed only through SCIM 2.0.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/whimsical/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/whimsical/refs/heads/main/apis.yml)

## Tags

- Collaboration
- Diagramming
- Flowcharts
- Wireframes
- Mind Maps

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Whimsical API (Beta)

Limited-beta REST API. Endpoints are read-oriented and use POST verbs: `users.get`, `teams.list`, `comments.list`, `files.list`, `files.get`. Authentication is OAuth 2.1, with credentials issued by Whimsical support to approved beta participants.

- **Human URL:** [https://whimsical.com/learn/integrations/api](https://whimsical.com/learn/integrations/api)
- **Base URL:** `https://whimsical.com/api`

#### Tags

- REST
- Beta
- Read Only
- OAuth 2.1

#### Properties

- [Documentation](https://whimsical.com/learn/integrations/api)
- [Authentication](https://whimsical.com/learn/integrations/api)
- [Postman Collection](collections/whimsical.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/whimsical.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Whimsical SCIM 2.0 API

Whimsical exposes SCIM 2.0 (and only SCIM) for programmatic user provisioning; there is no separate REST endpoint for user management. Available on plans with SCIM support (Enterprise).

- **Human URL:** [https://whimsical.com/help](https://whimsical.com/help)
- **Base URL:** `https://whimsical.com/api/scim/v2`

#### Tags

- SCIM
- User Provisioning
- Identity

#### Properties

- [Documentation](https://whimsical.com/help)
- [Postman Collection](collections/whimsical.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/whimsical.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/whimsicalcode)
- [LinkedIn](https://www.linkedin.com/company/whimsical)
- [Website](https://whimsical.com/)
- [Pricing](https://whimsical.com/pricing)
- [Integrations](https://help.whimsical.com/integrations)
- [Plans](plans/whimsical-plans-pricing.yml)
- [Rate Limits](rate-limits/whimsical-rate-limits.yml)
- [Fin Ops](finops/whimsical-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
