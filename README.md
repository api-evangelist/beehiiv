# beehiiv (beehiiv)

beehiiv is an NYC-based newsletter publishing platform founded in 2021 by former Morning Brew operators. The v2 REST API at `https://api.beehiiv.com/v2` covers publications, posts, subscriptions, automations, segments, custom fields, tiers, polls, referral program, newsletter lists, and webhooks. Bearer-token authentication and a per-organization rate limit of 180 requests/minute apply.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/beehiiv/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=beehiiv-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## Tags
- Newsletter, Creator, Email, Subscription, Publishing, Media, Advertising

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-25

## APIs
- **beehiiv Publications API** — Read publication metadata and configuration.
- **beehiiv Subscriptions API** — Create, list, and manage subscribers; bulk operations; per-subscriber tags.
- **beehiiv Posts API** — Create, update, and retrieve newsletter posts; aggregate stats; templates.
- **beehiiv Automations API** — Manage automations and enroll/track subscribers in journeys and emails.
- **beehiiv Custom Fields API** — Manage custom subscriber data attributes.
- **beehiiv Segments API** — Create, recalculate, and read subscriber segments.
- **beehiiv Tiers API** — Manage paid subscription tiers and prices.
- **beehiiv Polls API** — Manage polls and retrieve poll responses.
- **beehiiv Webhooks API** — Subscribe to real-time platform events.
- **beehiiv Newsletter Lists API** — Manage newsletter lists and per-list subscriptions.
- **beehiiv Referral Program API** — Read referral program configuration and progress.
- **beehiiv OAuth2 API** — OAuth2 authorization and token management for partner integrations.

## OpenAPI
Canonical spec at [`openapi/beehiiv-openapi.yml`](openapi/beehiiv-openapi.yml) — 50 paths across 23 subpackage tag groups. Sourced from beehiiv's published OpenAPI document.

## JSON Schema
- [`json-schema/beehiiv-subscription-schema.json`](json-schema/beehiiv-subscription-schema.json)
- [`json-schema/beehiiv-post-schema.json`](json-schema/beehiiv-post-schema.json)

## JSON-LD
- [`json-ld/beehiiv-context.jsonld`](json-ld/beehiiv-context.jsonld) — schema.org-aligned context for Publication, Subscription, Post, Tier, Segment, and Webhook.

## Naftiko Capabilities
24 per-subpackage capability files under [`capabilities/`](capabilities/) covering publications, subscriptions, posts, automations, segments, tiers, polls, webhooks, newsletter lists, referral program, custom fields, condition sets, engagements, data deletion, authors, post templates, bulk operations, OAuth users, and workspaces.

## Plans, Rate Limits, FinOps
- [Plans](plans/beehiiv-plans-pricing.yml) — Launch (free, 2,500 subs), Scale ($43/mo, 100k subs), Max ($96/mo, premium), Enterprise (Send API, dedicated IPs, SSO).
- [Rate Limits](rate-limits/beehiiv-rate-limits.yml) — 180 req/min per organization, 429 throttled, RateLimit-* headers.
- [FinOps](finops/beehiiv-finops.yml) — Flat-rate subscription, FOCUS-aligned; subscriber count is the gating meter.

## Documentation
- [Developer Docs](https://developers.beehiiv.com/)
- [API Reference](https://developers.beehiiv.com/api-reference)
- [Getting Started](https://developers.beehiiv.com/welcome/getting-started)
- [Rate Limiting](https://developers.beehiiv.com/welcome/rate-limiting)
- [LLMs.txt](https://developers.beehiiv.com/llms.txt) / [LLMs Full](https://developers.beehiiv.com/llms-full.txt)
- [MCP Server](https://developers.beehiiv.com/_mcp/server)

## SDKs and Tooling
- [TypeScript SDK](https://github.com/beehiiv/typescript-sdk)
- [GTM Event Tag](https://github.com/beehiiv/gtm-beehiiv-pixel-event)
- [GTM Ad Network Pixel](https://github.com/beehiiv/gtm-beehiiv-pixel-v2)

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
