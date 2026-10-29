# Chord

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

Chord is a New York / Santa Barbara-based commerce data and AI platform founded in 2021 by Bryan Mahoney (CEO) and Henry Davis (President & Chairman), both former Glossier executives. Chord began as a headless commerce backbone built on top of Solidus — the open-source Spree Commerce fork written in Ruby on Rails — and has since evolved into an AI-native commerce data platform with three layers: a Data Foundation that unifies sources such as Shopify, ad platforms, and CDPs; a Context Stack that grounds AI in store-specific business context; and a set of Agents that take action across the commerce stack. Its current product surface includes Chord OMS (a Solidus-based order management system covering orders, products, promotions, subscriptions, affiliates, gift cards, returns, shipping, tax, and digital products documented at chord.stoplight.io), Chord CDP (customer data platform with identity resolution, RFM scoring, customer lifetime revenue, and destination activations), Chord Event Tracking (client- and server-side eventing with Shopify Web Pixel integration and consent management via OneTrust and Shopify Customer Privacy API), Chord Data Platform (analytics, predictive modeling, attribution, recommendations, Fivetran ingestion, GA4 compatibility), and Chord AI / Copilot Chat, powered by Anthropic Claude (Opus 4.5 for SQL generation, Haiku 4.5 for response generation and classification) with charts, monitors, context modeling, and natural-language data querying. Chord's GitHub org (github.com/chordcommerce) maintains a fleet of Solidus extensions (solidus_stripe, solidus_braintree, solidus_paypal_braintree, solidus_subscriptions, solidus_virtual_gift_card, solidus_importer, solidus_avatax_certified), a consent-manager TypeScript library, a Jitsu fork for event ingestion, and example repos for eventing and analytics. Notable customers include Sonos, Blue Bottle Coffee, Rodan + Fields, MrBeast, and Ritual. Funding has come from M13 Ventures, Equal Ventures, Act One Ventures, Chingona Ventures, and CEAS Investments, with an $18M Series A reported by TechCrunch in 2021. The commercial model is sales-led with custom enterprise pricing gated behind a demo request.

**Areas:** Commerce · Composable Commerce · Headless Commerce · Order Management · OMS · Customer Data Platform · CDP · Event Tracking · Commerce Analytics · Customer Lifetime Value · AI Agents · Commerce Copilot

## Chord on APIs.io

Everything profiled for Chord is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/chord-commerce/](https://apis.io/providers/chord-commerce/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [Chord MCP](https://apis.io/apis/chord-commerce/chord-mcp/) — Chord's hosted Model Context Protocol server — a remote, OAuth-protected, read-only window into a customer's Chord data warehouse. Fourteen documented tools…
- [Chord CDP Ingest API](https://apis.io/apis/chord-commerce/chord-cdp-ingest-api/) — The HTTP ingest surface of the Chord customer data platform. Backend systems POST track and identify events to /api/track and /api/identify, authenticated…
- [Chord Audiences API](https://apis.io/apis/chord-commerce/chord-audiences-api/) — Read API for activated audiences. Once the Dynamic Audiences API destination is enabled on an account, a sync mirrors a custom audience into the API and a…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Chord Commerce Events](https://apis.io/asyncapis/chord-commerce/chord-commerce-events/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [chord-copilot](https://apis.io/servers/chord-commerce/chord-copilot/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Chord Commerce Authentication](https://apis.io/security/chord-commerce/chord-commerce-authentication/)
- [Chord Commerce Domain Security](https://apis.io/security/chord-commerce/chord-commerce-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Chord Commerce Scopes](https://apis.io/scopes/chord-commerce/chord-commerce-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Chord Commerce Plans Pricing](https://apis.io/plans/chord-commerce/chord-commerce-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Chord Commerce Rate Limits](https://apis.io/rate-limits/chord-commerce/chord-commerce-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.chordcommerce.com)
- [Documentation](https://docs.chord.co)
- [Getting started](https://docs.chord.co/analytics-developer-docs)
- [API reference](https://docs.chord.co/sdk-api-reference)
- [Pricing](https://www.chordcommerce.com/request-a-demo)
- [Support](https://www.chordcommerce.com/faq)
- [Blog](https://www.chordcommerce.com/resources/insights)
- [Terms of service](https://www.chordcommerce.com/legal/terms-of-service)
- [Privacy policy](https://www.chordcommerce.com/legal/privacy-policy)
- [GitHub](https://github.com/chordcommerce)
- [Status](https://status.chord.co)

## API Evangelist rating

**Kin Score 48.9** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 80.0 |
| Contract quality | 39.0 |
| Contract governance | 18.2 |
| Operational transparency | 42.1 |
| Developer ergonomics | 61.9 |
| Access clarity | 38.2 |

**Agent readiness 53.6** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 38.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/chord-commerce/](https://apis.io/providers/chord-commerce/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Chord: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/chord-commerce/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
