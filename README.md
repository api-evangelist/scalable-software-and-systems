# Scalable Software and Systems

A topic collection exploring the APIs, design patterns, frameworks, and platforms that enable scalable software and systems engineering. Covers architectural patterns such as CQRS, event sourcing, saga, MACH architecture, API-first design, and modular monoliths, as well as the tooling ecosystems that support building maintainable, high-scale software.

**Type:** Topic Collection
**Tags:** API First, Architecture Patterns, CQRS, Distributed Systems, Enterprise, Event Driven, Microservices, Scalable Architecture, Software Engineering, Systems Design

## APIs

### Backstage Software Catalog API
Spotify's developer portal platform providing a software catalog API for managing all software components, services, websites, and infrastructure at scale.

- **Documentation:** [https://backstage.io/docs/features/software-catalog/software-catalog-api](https://backstage.io/docs/features/software-catalog/software-catalog-api)
- **GitHub:** [https://github.com/backstage/backstage](https://github.com/backstage/backstage)

### CloudEvents API
CNCF specification for describing event data in a common way, defining a core data model and HTTP, AMQP, MQTT, and Kafka bindings for interoperable event-driven system design.

- **Documentation:** [https://cloudevents.io/](https://cloudevents.io/)
- **Specification:** [https://github.com/cloudevents/spec/blob/main/cloudevents/spec.md](https://github.com/cloudevents/spec/blob/main/cloudevents/spec.md)
- **GitHub:** [https://github.com/cloudevents/spec](https://github.com/cloudevents/spec)

### Apache Kafka Admin API
Admin REST API for creating and managing topics, partitions, consumer groups, and cluster configurations for high-throughput event streaming pipelines.

- **Documentation:** [https://kafka.apache.org/documentation/](https://kafka.apache.org/documentation/)
- **GitHub:** [https://github.com/apache/kafka](https://github.com/apache/kafka)

### NATS Management API
Lightweight, high-performance messaging system API for monitoring, subject inspection, and JetStream management for scalable event-driven systems.

- **Documentation:** [https://docs.nats.io/](https://docs.nats.io/)
- **GitHub:** [https://github.com/nats-io/nats-server](https://github.com/nats-io/nats-server)

### Temporal API
Durable execution platform providing an API for long-running, fault-tolerant workflows implementing the saga pattern with full activity retry semantics.

- **Documentation:** [https://docs.temporal.io/](https://docs.temporal.io/)
- **OpenAPI:** [https://github.com/temporalio/api/blob/master/openapi/openapi.yml](https://github.com/temporalio/api/blob/master/openapi/openapi.yml)
- **GitHub:** [https://github.com/temporalio/temporal](https://github.com/temporalio/temporal)

### Dapr API
Distributed Application Runtime building block APIs for service invocation, pub/sub messaging, state management, bindings, actors, and distributed tracing.

- **Documentation:** [https://docs.dapr.io/reference/api/](https://docs.dapr.io/reference/api/)
- **GitHub:** [https://github.com/dapr/dapr](https://github.com/dapr/dapr)

### OpenTelemetry API
Vendor-neutral APIs, SDKs, and instrumentation for generating traces, metrics, and logs. Essential for observability in scalable distributed software systems.

- **Documentation:** [https://opentelemetry.io/docs/](https://opentelemetry.io/docs/)
- **GitHub:** [https://github.com/open-telemetry/opentelemetry-specification](https://github.com/open-telemetry/opentelemetry-specification)

### Argo CD API
Declarative GitOps continuous delivery API for Kubernetes applications. Manages application deployments at scale using Git as the source of truth.

- **Documentation:** [https://argo-cd.readthedocs.io/en/stable/developer-guide/api-docs/](https://argo-cd.readthedocs.io/en/stable/developer-guide/api-docs/)
- **GitHub:** [https://github.com/argoproj/argo-cd](https://github.com/argoproj/argo-cd)

## Artifacts

### JSON Schema
- [Domain Event Schema](json-schema/scalable-software-and-systems-event-schema.json) — CloudEvents-based schema for domain events in event-sourced and event-driven systems.

### JSON Structure
- [Domain Event Structure](json-structure/scalable-software-and-systems-event-structure.json) — Structural documentation for domain events.

### JSON-LD Context
- [Scalable Software and Systems Context](json-ld/scalable-software-and-systems-context.jsonld) — Linked data context for distributed systems and software architecture vocabulary.

### Vocabulary
- [Scalable Software and Systems Vocabulary](vocabulary/scalable-software-and-systems-vocabulary.yml) — Domain vocabulary covering CQRS, Event Sourcing, Saga Pattern, GitOps, MACH Architecture, Observability, and more.

### Examples
- [Order Placed Domain Event](examples/scalable-software-and-systems-order-placed-event-example.json) — Example CloudEvents-compliant domain event with event sourcing metadata.
- [Temporal Order Saga Workflow](examples/scalable-software-and-systems-temporal-workflow-example.json) — Temporal durable workflow implementing the saga pattern for order fulfillment with compensating transactions.

## Common Resources

- [CQRS Pattern](https://microservices.io/patterns/data/cqrs.html)
- [Event Sourcing Pattern](https://microservices.io/patterns/data/event-sourcing.html)
- [Saga Pattern](https://microservices.io/patterns/data/saga.html)
- [CNCF Projects Landscape](https://www.cncf.io/projects/)
- [The Twelve-Factor App](https://12factor.net/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
