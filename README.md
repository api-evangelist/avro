# Apache Avro (avro)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
