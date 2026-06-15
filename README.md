# Scalable Software and Systems (scalable-software-and-systems)

A topic collection exploring the APIs, design patterns, frameworks, and platforms that enable scalable software and systems engineering. Covers architectural patterns such as CQRS, event sourcing, saga, MACH architecture, API-first design, and modular monoliths, as well as the tooling ecosystems that support building maintainable, high-scale software. Relevant to software architects, platform teams, and senior engineers building enterprise-grade distributed systems.

## Scope

- **Type:** Index

## Tags

- API First
- Architecture Patterns
- CQRS
- Distributed Systems
- Enterprise
- Event Driven
- Microservices
- Scalable Architecture
- Software Engineering
- Systems Design

## Timestamps

- **Created:** 2025-01-20
- **Modified:** 2026-05-02

## APIs

### Backstage Software Catalog API

Backstage by Spotify provides a software catalog API and developer portal platform for managing all software components, services, websites, and infrastructure at scale. Its catalog API enables registering, tracking, and discovering software components across an organization.

- **Human URL:** [https://backstage.io/docs/features/software-catalog/software-catalog-api](https://backstage.io/docs/features/software-catalog/software-catalog-api)

#### Tags

- Developer Portal
- Internal Developer Platform
- Software Catalog
- Systems Design

#### Properties

- [Documentation](https://backstage.io/docs/features/software-catalog/software-catalog-api)
- [Git Hub](https://github.com/backstage/backstage)
- [Postman Collection](collections/scalable-software-and-systems.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-software-and-systems.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CloudEvents API

CloudEvents is a CNCF specification for describing event data in a common way. It defines a core data model and HTTP, AMQP, MQTT, and Kafka bindings enabling interoperable event-driven system design across cloud providers and middleware.

- **Human URL:** [https://cloudevents.io/](https://cloudevents.io/)

#### Tags

- CNCF
- Event Driven
- Events
- Integration
- Standards

#### Properties

- [Documentation](https://cloudevents.io/)
- [Git Hub](https://github.com/cloudevents/spec)
- [Specification](https://github.com/cloudevents/spec/blob/main/cloudevents/spec.md)
- [Postman Collection](collections/scalable-software-and-systems.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-software-and-systems.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache Kafka Admin API

Apache Kafka's Admin REST API enables creating and managing topics, partitions, consumer groups, and cluster configurations for high-throughput event streaming pipelines used in scalable, event-driven architectures.

- **Human URL:** [https://kafka.apache.org/documentation/](https://kafka.apache.org/documentation/)

#### Tags

- Event Driven
- Event Streaming
- High Throughput
- Messaging

#### Properties

- [Documentation](https://kafka.apache.org/documentation/)
- [Git Hub](https://github.com/apache/kafka)
- [Postman Collection](collections/scalable-software-and-systems.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-software-and-systems.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NATS Management API

NATS is a lightweight, high-performance messaging system for distributed applications. Its management API provides monitoring, subject inspection, and JetStream (persistent streams) management for building scalable event-driven systems.

- **Human URL:** [https://docs.nats.io/](https://docs.nats.io/)

#### Tags

- Cloud Native
- Event Driven
- High Performance
- Messaging
- Microservices

#### Properties

- [Documentation](https://docs.nats.io/)
- [Git Hub](https://github.com/nats-io/nats-server)
- [Postman Collection](collections/scalable-software-and-systems.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-software-and-systems.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Temporal API

Temporal is a durable execution platform that provides an API for defining and running long-running, fault-tolerant workflows. Implements the saga pattern with full activity retry semantics, enabling reliable orchestration in distributed systems.

- **Human URL:** [https://docs.temporal.io/](https://docs.temporal.io/)

#### Tags

- Distributed Systems
- Durable Execution
- Saga Pattern
- Workflow Orchestration

#### Properties

- [Documentation](https://docs.temporal.io/)
- [Git Hub](https://github.com/temporalio/temporal)
- [OpenAPI](https://github.com/temporalio/api/blob/master/openapi/openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/scalable-software-and-systems.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-software-and-systems.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dapr API

Dapr (Distributed Application Runtime) provides building block APIs for service invocation, pub/sub messaging, state management, bindings, actors, and distributed tracing. Abstracts away infrastructure complexity for portable, scalable software.

- **Human URL:** [https://docs.dapr.io/reference/api/](https://docs.dapr.io/reference/api/)

#### Tags

- Distributed Systems
- Event Driven
- Microservices
- Scalable Architecture

#### Properties

- [Documentation](https://docs.dapr.io/reference/api/)
- [Git Hub](https://github.com/dapr/dapr)
- [Postman Collection](collections/scalable-software-and-systems.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-software-and-systems.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenTelemetry API

OpenTelemetry provides vendor-neutral APIs, SDKs, and instrumentation for generating traces, metrics, and logs. Essential for observability in scalable distributed software systems, enabling performance analysis and root cause diagnosis.

- **Human URL:** [https://opentelemetry.io/docs/](https://opentelemetry.io/docs/)

#### Tags

- Distributed Tracing
- Logs
- Metrics
- Observability
- Telemetry

#### Properties

- [Documentation](https://opentelemetry.io/docs/)
- [Git Hub](https://github.com/open-telemetry/opentelemetry-specification)
- [Postman Collection](collections/scalable-software-and-systems.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-software-and-systems.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Argo CD API

Argo CD provides a declarative GitOps continuous delivery API for Kubernetes applications. Enables teams to manage application deployments at scale using Git as the source of truth for system state.

- **Human URL:** [https://argo-cd.readthedocs.io/en/stable/developer-guide/api-docs/](https://argo-cd.readthedocs.io/en/stable/developer-guide/api-docs/)

#### Tags

- CD
- GitOps
- Kubernetes
- Platform Engineering

#### Properties

- [Documentation](https://argo-cd.readthedocs.io/en/stable/developer-guide/api-docs/)
- [Git Hub](https://github.com/argoproj/argo-cd)
- [Postman Collection](collections/scalable-software-and-systems.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalable-software-and-systems.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Guide](https://microservices.io/patterns/data/cqrs.html)
- [Guide](https://microservices.io/patterns/data/event-sourcing.html)
- [Guide](https://microservices.io/patterns/data/saga.html)
- [Guide](https://www.cncf.io/projects/)
- [Guide](https://12factor.net/)
- [JSON Schema](https://github.com/api-evangelist/scalable-software-and-systems/blob/main/json-schema/scalable-software-and-systems-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://github.com/api-evangelist/scalable-software-and-systems/blob/main/json-structure/scalable-software-and-systems-event-structure.json)
- [J S O N L D Context](https://github.com/api-evangelist/scalable-software-and-systems/blob/main/json-ld/scalable-software-and-systems-context.jsonld)
- [Vocabulary](https://github.com/api-evangelist/scalable-software-and-systems/blob/main/vocabulary/scalable-software-and-systems-vocabulary.yml)
- [Examples](https://github.com/api-evangelist/scalable-software-and-systems/blob/main/examples/scalable-software-and-systems-order-placed-event-example.json)
- [Examples](https://github.com/api-evangelist/scalable-software-and-systems/blob/main/examples/scalable-software-and-systems-temporal-workflow-example.json)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
