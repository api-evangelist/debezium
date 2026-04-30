# Debezium (debezium)

Debezium is an open source distributed platform for change data capture (CDC) that converts changes in existing databases into event streams, enabling applications to detect and respond to row-level changes in databases in real time.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/debezium/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **x-type:** opensource

## Tags

- Apache Kafka, CDC, Change Data Capture, Databases, Event Streaming, Open Source

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-04-28

## APIs

### Debezium Kafka Connect REST API

Debezium runs as Kafka Connect source connectors. This API manages Debezium CDC connectors, their configurations, tasks, and offsets via the standard Kafka Connect REST interface.

- **Base URL:** http://localhost:8083
- **Human URL:** https://debezium.io/documentation/reference/stable/connectors/index.html

#### Properties

- [Documentation](https://debezium.io/documentation/reference/stable/connectors/index.html)
- [OpenAPI](openapi/debezium-connect.yml)
- [JSONSchema - Change Event](json-schema/debezium-change-event.json)
- [Rules](rules/debezium-kafka-connect-api-rules.yml)
- [Capabilities](capabilities/debezium-kafka-connect-api-capabilities.yml)

## Common Properties

- [Website](https://debezium.io/)
- [Documentation](https://debezium.io/documentation/)
- [Getting Started](https://debezium.io/documentation/reference/stable/tutorial.html)
- [GitHub](https://github.com/debezium/debezium)
- [Blog](https://debezium.io/blog/)
- [Community](https://debezium.io/community/)
- [License - Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)
- [JSON-LD](json-ld/debezium-context.jsonld)
- [Vocabulary](vocabulary/debezium-vocabulary.yml)

## Maintainers

- **Kin Lane** - kin@apievangelist.com
