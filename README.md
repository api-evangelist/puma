# Puma (puma)

Puma is a simple, fast, multi-threaded, and highly parallel HTTP 1.1 server for Ruby/Rack applications. It is the most popular Ruby web server and the default server for Ruby on Rails, supporting SSL, zero-downtime rolling restarts, and a built-in request bufferer. Puma is an open-source application server and not a hosted service, so it does not expose a public REST API; integration is through configuration, Rack middleware, and the Puma control application server.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/puma/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/puma/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Web Server
- Ruby
- Rack
- Application Server
- HTTP
- Open Source

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Puma Control/Status Application

Puma ships with an optional control/status HTTP application that can be bound to a local port or Unix socket and queried for runtime statistics (busy threads, worker status, backlog) and lifecycle control (stop, restart, halt). Authentication uses a shared control token passed via the `token` query parameter.

- **Human URL:** [https://github.com/puma/puma/blob/master/docs/restart.md](https://github.com/puma/puma/blob/master/docs/restart.md)
- **Base URL:** `http://127.0.0.1:9293`

#### Tags

- Control
- Status
- Operations
- Ruby

#### Properties

- [Documentation](https://github.com/puma/puma/blob/master/docs/restart.md)
- [Source  Code](https://github.com/puma/puma)
- [Postman Collection](collections/puma.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/puma.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/puma)
- [Website](https://puma.io)
- [Documentation](https://puma.io/puma/)
- [GitHub Organization](https://github.com/puma)
- [GitHub Repository](https://github.com/puma/puma)
- [Ruby Gems](https://rubygems.org/gems/puma)
- [Issues](https://github.com/puma/puma/issues)
- [Discussions](https://github.com/puma/puma/discussions)
- [License](https://github.com/puma/puma/blob/master/LICENSE)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
