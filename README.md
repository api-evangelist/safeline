# SafeLine (safeline)

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
