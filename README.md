# Energy API Specification

This repository contains the public OpenAPI 3.0 specification for the Energy API.

## Purpose

This spec is published from a private backend repository to enable:
- API documentation tools (Swagger UI, Redoc)
- Code generation for clients
- Third-party integrations (e.g., Lovable, Postman)

## Usage

### Raw URL (for tools)

```
https://raw.githubusercontent.com/nmoorcroft/energy-api-spec/main/openapi.yaml
```

### Pin to a version

```
https://raw.githubusercontent.com/nmoorcroft/energy-api-spec/v1.0.0/openapi.yaml
```

### View documentation

You can paste the raw URL into:
- [Swagger Editor](https://editor.swagger.io/)
- [Redoc Demo](https://redocly.github.io/redoc/)

## Versioning

Tags follow semantic versioning (`v1.0.0`, `v1.1.0`, etc.) and match the `info.version` field in the spec.

## Updates

This repository is automatically updated when the spec changes in the source repository. Do not edit `openapi.yaml` directly—changes will be overwritten.

---

*This is a read-only, auto-published repository.*
