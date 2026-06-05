# Debezium (debezium)

Debezium is an open source distributed platform for change data capture (CDC) that converts changes in existing databases into event streams, enabling applications to detect and respond to row-level changes in databases in real time.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/debezium/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/debezium/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Apache Kafka
- CDC
- Change Data Capture
- Databases
- Event Streaming
- Open Source

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-19

## APIs

### Debezium Kafka Connect REST API

Debezium runs as Kafka Connect source connectors. This API manages Debezium CDC connectors, their configurations, tasks, and offsets via the standard Kafka Connect REST interface.

- **Human URL:** [https://debezium.io/documentation/reference/stable/connectors/index.html](https://debezium.io/documentation/reference/stable/connectors/index.html)
- **Base URL:** `http://localhost:8083`

#### Tags

- CDC
- Connectors
- Kafka Connect
- REST API

#### Properties

- [Documentation](https://debezium.io/documentation/reference/stable/connectors/index.html)
- [OpenAPI](openapi/debezium-connect.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/debezium-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/debezium-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/debezium-change-event.json) — [JSON Schema](https://json-schema.org/specification)
- [Rules](rules/debezium-kafka-connect-api-rules.yml)
- [Capabilities](capabilities/debezium-kafka-connect-api-capabilities.yml)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/debezium)
- [Website](https://debezium.io/)
- [Documentation](https://debezium.io/documentation/)
- [Getting Started](https://debezium.io/documentation/reference/stable/tutorial.html)
- [Git Hub](https://github.com/debezium/debezium)
- [Blog](https://debezium.io/blog/)
- [Community](https://debezium.io/community/)
- [License](https://www.apache.org/licenses/LICENSE-2.0)
- [JSON-LD](json-ld/debezium-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/debezium-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
