# Tillo

Tillo is an award-winning gift card API platform connecting businesses to 4,000+ global brands across 37 markets and 16 currencies. The REST API supports digital and physical gift card issuance, balance checking, float management, and brand catalog access. Authentication uses HMAC-SHA256 signatures.

**Human URL:** https://www.tillo.io/gift-card-api

## APIs

| Name | Description |
|---|---|
| [Tillo Gift Card API](https://tillo.tech/v2_docs/) | Digital and physical gift card issuance and management |
| [Tillo Float Management API](https://tillo.tech/v2_docs/floats.html) | Float account balance and payment transfer management |

## OpenAPI Specifications

| Specification | Description |
|---|---|
| [Tillo Gift Card API](openapi/tillo-gift-card-openapi.yml) | Brands, issuance, balance, orders, and float endpoints |

## Capabilities

| Capability | APIs Used | Description |
|---|---|---|
| [Gift Card Rewards](capabilities/gift-card-rewards.yaml) | Gift Card API | Full rewards delivery workflow for loyalty and incentive programs |

### Shared API Definitions

| Shared Definition | Description |
|---|---|
| [gift-card-api.yaml](capabilities/shared/gift-card-api.yaml) | Tillo Gift Card API consumed definition |

## Rules

| Ruleset | Description |
|---|---|
| [tillo-rules.yml](rules/tillo-rules.yml) | Spectral ruleset for Tillo API conventions |

## Schemas

| Schema | Description |
|---|---|
| [tillo-brand-schema.json](json-schema/tillo-brand-schema.json) | JSON Schema for Tillo gift card brand |
| [tillo-gift-card-schema.json](json-schema/tillo-gift-card-schema.json) | JSON Schema for issued Tillo gift card |

## Structures

| Structure | Description |
|---|---|
| [tillo-brand-structure.json](json-structure/tillo-brand-structure.json) | Brand object field structure |

## JSON-LD

| Context | Description |
|---|---|
| [tillo-context.jsonld](json-ld/tillo-context.jsonld) | JSON-LD context mapping to schema.org |

## Examples

| Example | Description |
|---|---|
| [List Brands](examples/tillo-listBrands-example.json) | Example brand catalog response |
| [Issue Digital Card](examples/tillo-issueDigitalCard-example.json) | Example gift card issuance |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [tillo-vocabulary.yml](vocabulary/tillo-vocabulary.yml) | Tillo gift card platform vocabulary |

## Common Properties

- **Website:** https://www.tillo.io/
- **Documentation:** https://tillo.tech/v2_docs/
- **GitHub:** https://github.com/tilloops
- **Blog:** https://www.tillo.io/blog
- **Authentication:** https://tillo.tech/v2_docs/authentication.html

## Maintainers

**Kin Lane** (kin@apievangelist.com)
