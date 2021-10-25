# Items API

This is an OpenAPI specification of the Items API.

## 1. OpenAPI Specification

The entry point of the specification is in `src/index.yaml`

## 2. Tools

### 2.1. Validate specification

```
swagger-cli validate src/index.yaml
```

### 2.2. Bundle specification into a single file

```
swagger-cli bundle --outfile items-api.yaml src/index.yaml
```
