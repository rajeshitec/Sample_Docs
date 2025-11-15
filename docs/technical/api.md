# API reference

Base URL:

```text
https://api.project.internal.corp/v1
```

All endpoints require a Bearer token:

```http
Authorization: Bearer <access_token>
```

## GET /clients

Returns a paginated list of clients.

Query params: `q`, `status`, `page`, `size`.

## POST /clients

Creates a new client. Requires `ROLE_OPS_ANALYST`.

