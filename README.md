# Warner Bros. Discovery

Warner Bros. Discovery is a leading global media and entertainment company that creates and distributes branded content across television, film, and streaming. WBD operates Max, HBO, Warner Bros. Pictures, CNN, Discovery, TNT, TBS, and many other brands. The company provides content partner APIs for media supply chain integration.

- **Website:** [https://www.wbd.com/](https://www.wbd.com/)
- **Content Partner Hub:** [https://partnerhub.warnermedia.com/](https://partnerhub.warnermedia.com/)
- **GitHub (WarnerMedia):** [https://github.com/WarnerMedia](https://github.com/WarnerMedia)
- **GitHub (Warner Bros.):** [https://github.com/warnerbros](https://github.com/warnerbros)

## APIs

### Warner Bros. Discovery Content Partner API

API for content partners to deliver media assets and metadata to WBD's media supply chain. Supports Automated Content Delivery (ACD) using MovieLabs Media Manifest Core (MMC).

- **Base URL:** `https://api.warnermediasupplychain.com`
- **Authentication:** OAuth 2.0 Client Credentials
- **Partner Hub:** [https://partnerhub.warnermedia.com/specifications-and-guides](https://partnerhub.warnermedia.com/specifications-and-guides)

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [warner-bros-discovery-content-partner-openapi.yml](openapi/warner-bros-discovery-content-partner-openapi.yml) | Content Partner API — deliveries, metadata, assets, validation |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [warner-bros-discovery-rules.yml](rules/warner-bros-discovery-rules.yml) | Spectral ruleset for WBD API conventions |

### Naftiko Capabilities

#### Shared Per-API Definitions

| File | Description |
|------|-------------|
| [capabilities/shared/content-partner.yaml](capabilities/shared/content-partner.yaml) | WBD Content Partner API definition |

#### Workflow Capabilities

| Workflow | Description | Tools |
|----------|-------------|-------|
| [content-delivery.yaml](capabilities/content-delivery.yaml) | Content delivery and supply chain operations | 6 tools |

### JSON Schemas

| Schema | Description |
|--------|-------------|
| [warner-bros-discovery-content-schema.json](json-schema/warner-bros-discovery-content-schema.json) | Content delivery data schema |

### JSON Structures

| Structure | Description |
|-----------|-------------|
| [warner-bros-discovery-content-structure.json](json-structure/warner-bros-discovery-content-structure.json) | Content delivery structure documentation |

### JSON-LD Contexts

| Context | Description |
|---------|-------------|
| [warner-bros-discovery-context.jsonld](json-ld/warner-bros-discovery-context.jsonld) | JSON-LD context (schema.org + MovieLabs aligned) |

### Examples

| Example | Description |
|---------|-------------|
| [warner-bros-discovery-listDeliveries-example.json](examples/warner-bros-discovery-listDeliveries-example.json) | List deliveries request/response example |

### Vocabulary

| File | Description |
|------|-------------|
| [warner-bros-discovery-vocabulary.yml](vocabulary/warner-bros-discovery-vocabulary.yml) | WBD content delivery vocabulary |

## Open Source Projects

- [gimme-aws-creds](https://github.com/WarnerMedia/gimme-aws-creds) — Python CLI for obtaining AWS credentials via Okta
- [antiope-aws-module](https://github.com/WarnerMedia/antiope-aws-module) — AWS inventory and security tooling
- [mux.js](https://github.com/warnerbros/mux.js) — JavaScript library for video segment parsing

## Maintainers

**Kin Lane** — [kin@apievangelist.com](mailto:kin@apievangelist.com)
