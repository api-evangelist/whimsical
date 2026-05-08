# Whimsical (whimsical)

Whimsical is a visual workspace for boards, mind maps, flowcharts, wireframes, and documents. The Whimsical API is in limited beta with read-only endpoints for users, teams, comments, and files; user provisioning is exposed only through SCIM 2.0.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/whimsical/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=whimsical-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## APIs
- **Whimsical API (Beta)** - Limited-beta REST. Endpoints: `users.get`, `teams.list`, `comments.list`, `files.list`, `files.get`. OAuth 2.1; credentials issued by Whimsical support.
- **Whimsical SCIM 2.0 API** - User provisioning at `/api/scim/v2`. Enterprise plan only.

## Tags
- Collaboration, Diagramming, Flowcharts, Wireframes, Mind Maps

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Common Properties
- [Website](https://whimsical.com/)
- [Pricing](https://whimsical.com/pricing)
- [Integrations](https://help.whimsical.com/integrations)
- [Plans](plans/whimsical-plans-pricing.yml)
- [RateLimits](rate-limits/whimsical-rate-limits.yml)
- [FinOps](finops/whimsical-finops.yml)

## Notes
- Pricing reconciled (research): Free $0/editor (3 boards, 100 AI actions); Pro $10/editor (unlimited boards, 500 AI/mo); Business $15/editor (SAML/SSO); Enterprise $20/editor (SCIM, dedicated success manager). 17% annual discount; viewers always free.
- API is **beta and read-only** — capabilities limited; new features pending. For AI integration, Whimsical recommends their desktop MCP rather than the API.
- User management is SCIM-only; there is no general REST endpoint for user CRUD.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
