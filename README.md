# Apache Avro (avro)
Apache Avro is a data serialization system that provides rich data structures, a compact binary format, and container files for storing persistent data. Avro uses JSON for defining data types and protocols, and serializes data in a compact binary format.

**URL:** [https://avro.apache.org/](https://avro.apache.org/)

## Tags

 - Apache, Big Data, Binary Format, Data Serialization, Schema Evolution

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-19

## APIs

### Apache Avro Schema Format
JSON Schema for validating Apache Avro schema definitions. Covers all Avro types including primitive types (null, boolean, int, long, float, double, bytes, string), complex types (records, enums, arrays, maps, unions, fixed), logical types, and schema evolution features like aliases and default values.

**Human URL:** [https://avro.apache.org/docs/current/specification/](https://avro.apache.org/docs/current/specification/)

#### Tags

 - Data Serialization, JSON, Schema, Schema Evolution

#### Properties

- [Documentation](https://avro.apache.org/docs/current/specification/)
- [JSONSchema](json-schema/avro-schema.yml)

## Common Properties

- [Website](https://avro.apache.org/)
- [Documentation](https://avro.apache.org/docs/)
- [GitHubOrganization](https://github.com/apache/avro)

## Features

| Name | Description |
|------|-------------|
| Schema-First Design | Avro requires schemas to be defined in JSON before serialization, enabling strong typing and schema validation. |
| Schema Evolution | Avro supports backward, forward, and full schema compatibility through aliases, defaults, and type promotions. |
| Compact Binary Format | Avro serializes data in a compact binary format without field names, reducing payload size significantly. |
| Rich Type System | Supports primitive types, complex types (records, enums, arrays, maps, unions, fixed), and logical types (date, time, decimal, UUID). |
| Language Agnostic | Official implementations in Java, Python, C, C++, C#, PHP, Ruby, and Rust with broad ecosystem support. |
| Container Files | Avro Object Container Files (OCF) embed the schema with the data for self-describing data files. |
| RPC Support | Avro defines an RPC protocol mechanism using schemas for both request and response messages. |
| Kafka Native Format | Apache Kafka ecosystem uses Avro as a primary serialization format with the Confluent Schema Registry. |

## Use Cases

| Name | Description |
|------|-------------|
| Event Streaming | Serialize Kafka events with Avro schemas stored in a Schema Registry for high-throughput data pipelines. |
| Data Lake Storage | Store large datasets in Avro container files in Hadoop-compatible storage with embedded schema metadata. |
| Schema Registry Integration | Use Confluent Schema Registry to manage schema versions and enforce compatibility across producers and consumers. |
| Inter-Service Messaging | Define message contracts between microservices using Avro schemas for type-safe data exchange. |
| Batch Data Processing | Process large volumes of structured data with Apache Spark, Hive, or Flink using Avro as the interchange format. |

## Integrations

| Name | Description |
|------|-------------|
| Apache Kafka | Native serialization format for Kafka messages via the Confluent Schema Registry and Kafka clients. |
| Apache Spark | Spark SQL and DataFrames support reading and writing Avro files natively. |
| Apache Hive | Hive tables can be backed by Avro container files with schema stored in the Hive Metastore. |
| Confluent Schema Registry | Centralized schema management service for validating and evolving Avro schemas in Kafka ecosystems. |
| Apache Flink | Flink supports Avro for serialization and deserialization of streaming data. |
| Apache Hadoop | Avro is a native storage format supported by the Hadoop ecosystem for distributed processing. |

## Artifacts

### JSON Schema

- [Apache Avro Schema](json-schema/avro-schema.yml)

## Vocabulary

- [Apache Avro Vocabulary](vocabulary/avro-vocabulary.yaml) — Normative vocabulary mapping 8 resources, 6 actions, and core specification concepts

## Rules

- [Avro Spectral Rules](rules/avro-spectral-rules.yml) — 15 rules enforcing Apache Avro schema conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
