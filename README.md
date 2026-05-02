# SafeLine

SafeLine is an open-source self-hosted Web Application Firewall (WAF) and reverse proxy developed by Chaitin Technology that protects web applications and APIs from attacks including SQL injection, XSS, code injection, OS command injection, SSRF, path traversal, and RCE. With over 180,000 installations protecting more than 1 million websites, SafeLine handles over 30 billion HTTP requests daily.

**URL:** [https://waf.chaitin.com/](https://waf.chaitin.com/)

**GitHub:** [https://github.com/chaitin/SafeLine](https://github.com/chaitin/SafeLine)

## APIs

### SafeLine Management API
SafeLine Management API provides programmatic control of the SafeLine WAF including application management, security rule configuration, attack event analysis, IP allowlist/blocklist management, and traffic monitoring. The management API is exposed on port 9443 and supports authentication via API tokens.

**Human URL:** [https://waf.chaitin.com/](https://waf.chaitin.com/)

#### Tags
- Proxy, WAF, Security, REST, Open Source

#### Properties
- [Documentation](https://docs.waf.chaitin.com/)
- [Getting Started](https://docs.waf.chaitin.com/en/getting-started)
- [GitHub Repository](https://github.com/chaitin/SafeLine)
- [OpenAPI](openapi/safeline-management-openapi.yml)

### SafeLine MCP Server
SafeLine provides MCP (Model Context Protocol) Server implementations for AI-assisted WAF management including Python and Go server implementations.

**Human URL:** [https://github.com/chaitin/SafeLine](https://github.com/chaitin/SafeLine)

## Common Properties

- [Website](https://waf.chaitin.com/)
- [Documentation](https://docs.waf.chaitin.com/)
- [GitHub Organization](https://github.com/chaitin/SafeLine)
- [Demo](https://demo.waf.chaitin.com/)
- [OpenAPI](openapi/safeline-management-openapi.yml)
- [SpectralRules](rules/safeline-rules.yml)
- [JSONSchema](json-schema/safeline-website-schema.json)
- [JSONSchema](json-schema/safeline-acl-rule-schema.json)
- [JSONStructure](json-structure/safeline-website-structure.json)
- [JSONStructure](json-structure/safeline-acl-rule-structure.json)
- [JSONLDContext](json-ld/safeline-context.jsonld)
- [Vocabulary](vocabulary/safeline-vocabulary.yml)
- [Capabilities](capabilities/waf-protection-management.yaml)

## Capabilities

### Shared Definitions
- [safeline-management](capabilities/shared/safeline-management.yaml) — SafeLine WAF Management API

### Workflows
- [waf-protection-management](capabilities/waf-protection-management.yaml) — Unified WAF protection management workflow (15 MCP tools)

## Artifacts

| Type | File |
|---|---|
| OpenAPI | [openapi/safeline-management-openapi.yml](openapi/safeline-management-openapi.yml) |
| Spectral Rules | [rules/safeline-rules.yml](rules/safeline-rules.yml) |
| JSON Schema | [json-schema/safeline-website-schema.json](json-schema/safeline-website-schema.json) |
| JSON Schema | [json-schema/safeline-acl-rule-schema.json](json-schema/safeline-acl-rule-schema.json) |
| JSON Structure | [json-structure/safeline-website-structure.json](json-structure/safeline-website-structure.json) |
| JSON Structure | [json-structure/safeline-acl-rule-structure.json](json-structure/safeline-acl-rule-structure.json) |
| JSON-LD Context | [json-ld/safeline-context.jsonld](json-ld/safeline-context.jsonld) |
| Vocabulary | [vocabulary/safeline-vocabulary.yml](vocabulary/safeline-vocabulary.yml) |
| Examples | [examples/](examples/) |

## Maintainers

**Email:** kin@apievangelist.com
