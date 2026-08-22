# SafeLine (safeline)

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

SafeLine is an open-source self-hosted Web Application Firewall (WAF) and reverse proxy developed by Chaitin Technology that protects web applications and APIs from attacks including SQL injection, XSS, code injection, OS command injection, SSRF, path traversal, and RCE. With over 180,000 installations protecting more than 1 million websites, SafeLine handles over 30 billion HTTP requests daily. It provides rate limiting, anti-bot defenses, dynamic code protection, and integrates with API gateways including Apache APISIX and Kong. SafeLine exposes a management API on port 9443 and supports MCP server implementations for AI-assisted management.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/safeline/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/safeline/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Proxy
- WAF
- Security
- Open Source
- Reverse Proxy
- API Gateway

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-19

## APIs

### SafeLine Management API

SafeLine Management API provides programmatic control of the SafeLine WAF including application management, security rule configuration, attack event analysis, IP allowlist/blocklist management, and traffic monitoring. The management API is exposed on port 9443 and supports authentication via API tokens.

- **Human URL:** [https://waf.chaitin.com/](https://waf.chaitin.com/)

#### Tags

- Proxy
- WAF
- Security
- REST
- Open Source

#### Properties

- [Documentation](https://docs.waf.chaitin.com/)
- [Getting Started](https://docs.waf.chaitin.com/en/getting-started)
- [GitHub Repository](https://github.com/chaitin/SafeLine)
- [OpenAPI](openapi/safeline-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/safeline-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/safeline-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SafeLine MCP Server

SafeLine provides two MCP (Model Context Protocol) Server implementations for AI-assisted WAF management: a Python MCP Server for tool-based API management and a Go MCP Server for high-performance management. These servers expose tools for application management, security rule configuration, and attack event analysis.

- **Human URL:** [https://github.com/chaitin/SafeLine](https://github.com/chaitin/SafeLine)

#### Tags

- WAF
- MCP
- AI
- Security

#### Properties

- [GitHub Repository](https://github.com/chaitin/SafeLine)
- [Postman Collection](collections/safeline-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/safeline-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://waf.chaitin.com/)
- [Documentation](https://docs.waf.chaitin.com/)
- [GitHub Organization](https://github.com/chaitin/SafeLine)
- [Demo](https://demo.waf.chaitin.com/)
- [OpenAPI](openapi/safeline-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral Rules](rules/safeline-rules.yml)
- [JSON Schema](json-schema/safeline-website-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/safeline-acl-rule-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/safeline-website-structure.json)
- [JSON Structure](json-structure/safeline-acl-rule-structure.json)
- [J S O N L D Context](json-ld/safeline-context.jsonld)
- [Vocabulary](vocabulary/safeline-vocabulary.yml)
- [Capabilities](capabilities/waf-protection-management.yaml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
