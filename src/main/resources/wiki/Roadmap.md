## Version 1.0 - First Alpha - March 30th, 2026 :seedling:

The goal of this version is to deliver a MVP to enable common AI integration use cases and grow our community.

### Rightsize AI context
- [x] Declarative applied capability exposing Agent Skills
- [x] Declarative MCP exposing Resources and Prompts (Tools only so far)

### Enable API reuse
- [x] Support for lookups as part of API call steps
- [x] Authenticate API and MCP Server consumers and manage permissions
- [x] Reusable source HTTP adapter declaration across capabilities
  - [x] Declarative applied capabilities with reused source capabilities

### Core developer experience
- [x] Publish FAQ in the wiki
- [ ] Publish Naftiko Skill based on Naftiko CLI
- [ ] Publish Maven Artifacts to [Maven Central](https://central.sonatype.com/)
- [ ] Publish Javadocs to [Javadoc.io](https://javadoc.io)
- [ ] Publish Docker Image to [Docker Hub](https://hub.docker.com/)
- [ ] Provide GitHub Action template based on [Super Linter](https://github.com/super-linter/super-linter)
- [ ] Publish Naftiko JSON Structure

## Version 1.0 - Second Alpha - May 11th :deciduous_tree:

The goal of this version is to deliver a MVP to enable common AI integration use cases and grow our community.

- [ ] Enable agent orchestration use case
  - [ ] Declarative applied capability exposing A2A
- [ ] Provide enhanced security
  - [ ] Add support for authentication in the MCP server adapter
  - [ ] Facilitate integration with various API/MCP/AI gateways
  - [ ] Facilitate integration with Keycloak, OpenFGA
- [ ] Enhance API reusability
  - [ ] Factorize capability core with "aggregates" of functions initially, entities and events later
  - [ ] Add conditional steps, for-each steps, parallel-join
  - [ ] Add support for gRPC and tRPC as server adapters
  - [ ] Add support for resiliency patterns (retry, circuit breaker, rate limiter, time limiter, bulkhead, cache, fallback)
- [ ] Provide per-capability Control API and MCP adapters, aligned with CLI
- [ ] Provide Control webapp (per Capability)
- [ ] Publish Docker Desktop Extension to Docker Hub
- [ ] Fabric discovery of published capabilities for consumers

## Version 1.0 - First Beta - June :blossom:

The goal of this version is to deliver a stable MVP, including a stable Naftiko Specification

- [ ] Enhance API reusability
- [ ] Incorporate community feedback
- [ ] Solidify the existing alpha version scope
- [ ] Increase test coverage and overall quality

## Version 1.0 - General Availability - September :apple:

The goal of this version is to release our first version ready for production.

- [ ] Incorporate community feedback
- [ ] Solidify the existing beta version scope
- [ ] Increase test coverage and overall quality
- [ ] Publish JSON Schema to [JSON Schema Store](https://www.schemastore.org/)
