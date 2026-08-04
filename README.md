# Spring Cloud Stream

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

Spring Cloud Stream is a framework for building event-driven microservices connected with shared messaging systems. It provides a flexible programming model built on established Spring idioms and best practices, including support for persistent pub/sub semantics, consumer groups, and stateful partitions with Apache Kafka and RabbitMQ binders.

**URL:** https://spring.io/projects/spring-cloud-stream

## Tags

Apache Kafka, AsyncAPI, Event-Driven, Java, Messaging, Microservices, RabbitMQ, Spring Framework, Stream Processing

## APIs

### Spring Cloud Stream Core API

Core programmatic API for building message-driven microservice applications. Provides functional programming model with java.util.function.Function, Consumer and Supplier bindings, binding lifecycle management, and integration with Spring Integration for message transformation and routing.

**Human URL:** https://spring.io/projects/spring-cloud-stream

**Tags:** Bindings, Consumer Groups, Event-Driven, Functional Programming, Messaging, Microservices

**Properties:**
- [Documentation](https://docs.spring.io/spring-cloud-stream/docs/current/reference/html/)
- [API Documentation](https://docs.spring.io/spring-cloud-stream/docs/current/api/)
- [Getting Started](https://spring.io/projects/spring-cloud-stream#learn)
- [GitHub](https://github.com/spring-cloud/spring-cloud-stream)
- [Maven Repository](https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-stream)
- [Samples](https://github.com/spring-cloud/spring-cloud-stream-samples)
- [Releases](https://github.com/spring-cloud/spring-cloud-stream/releases)
- [Issues](https://github.com/spring-cloud/spring-cloud-stream/issues)
- [JSON Schema](json-schema/spring-cloud-stream-binding-schema.json)
- [JSON Structure](json-structure/spring-cloud-stream-binding-structure.json)
- [JSON-LD Context](json-ld/spring-cloud-stream-context.jsonld)

### Spring Cloud Stream Kafka Binder

Apache Kafka binder for Spring Cloud Stream providing Kafka producer and consumer binding configuration, Kafka Streams support, partitioning, transaction management, error handling, and dead-letter queues.

**Human URL:** https://docs.spring.io/spring-cloud-stream-binder-kafka/docs/current/reference/html/

**Tags:** Apache Kafka, Binder, Event Streaming, Kafka Streams, Messaging

**Properties:**
- [Documentation](https://docs.spring.io/spring-cloud-stream-binder-kafka/docs/current/reference/html/)
- [GitHub](https://github.com/spring-cloud/spring-cloud-stream-binder-kafka)
- [Maven Repository](https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-stream-binder-kafka)

### Spring Cloud Stream RabbitMQ Binder

RabbitMQ binder for Spring Cloud Stream providing AMQP-based messaging with support for exchanges, queues, routing keys, dead-letter exchanges, consumer groups, and AMQP transaction management.

**Human URL:** https://docs.spring.io/spring-cloud-stream-binder-rabbit/docs/current/reference/html/

**Tags:** AMQP, Binder, Messaging, RabbitMQ

**Properties:**
- [Documentation](https://docs.spring.io/spring-cloud-stream-binder-rabbit/docs/current/reference/html/)
- [GitHub](https://github.com/spring-cloud/spring-cloud-stream-binder-rabbit)
- [Maven Repository](https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-stream-binder-rabbit)

## Artifacts

### JSON Schemas

| Schema | Description |
|--------|-------------|
| [spring-cloud-stream-binding-schema.json](json-schema/spring-cloud-stream-binding-schema.json) | Binding configuration properties schema for Kafka and RabbitMQ binders |

### JSON Structures

| Structure | Description |
|-----------|-------------|
| [spring-cloud-stream-binding-structure.json](json-structure/spring-cloud-stream-binding-structure.json) | Binding, consumer, and producer properties structure documentation |

### JSON-LD Contexts

| Context | Description |
|---------|-------------|
| [spring-cloud-stream-context.jsonld](json-ld/spring-cloud-stream-context.jsonld) | Spring Cloud Stream linked data context |

### Examples

| Example | Description |
|---------|-------------|
| [spring-cloud-stream-kafka-binding-example.json](examples/spring-cloud-stream-kafka-binding-example.json) | Kafka binder configuration with consumer groups and partitioning |
| [spring-cloud-stream-rabbitmq-binding-example.json](examples/spring-cloud-stream-rabbitmq-binding-example.json) | RabbitMQ binder configuration with dead-letter queue |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [spring-cloud-stream-vocabulary.yml](vocabulary/spring-cloud-stream-vocabulary.yml) | Spring Cloud Stream domain vocabulary and terminology |

## Common Properties

- [Website](https://spring.io/projects/spring-cloud-stream)
- [Documentation](https://docs.spring.io/spring-cloud-stream/docs/current/reference/html/)
- [GitHub](https://github.com/spring-cloud/spring-cloud-stream)
- [GitHub Organization](https://github.com/spring-cloud)
- [Blog](https://spring.io/blog/category/cloud)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/spring-cloud-stream)
- [Support](https://spring.io/support)

## Maintainers

**Name:** VMware Tanzu (Spring Team)  
**Email:** spring-cloud@vmware.com  
**URL:** https://spring.io/team
