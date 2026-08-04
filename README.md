# Spring Framework (spring-framework)

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

The Spring Framework provides a comprehensive programming and configuration model for modern Java-based enterprise applications on any kind of deployment platform. A key element of Spring is infrastructural support at the application level: Spring focuses on the "plumbing" of enterprise applications so that teams can focus on application-level business logic, without unnecessary ties to specific deployment environments. It includes modules for dependency injection, data access, web development, aspect-oriented programming, and more.

**APIs.json:** [https://spring.io/projects/spring-framework](https://spring.io/projects/spring-framework)

## Scope

- **Type:** Index

## Tags

- AOP
- Dependency Injection
- Enterprise
- Framework
- IoC
- Java
- Microservices
- MVC
- Spring Boot

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Spring Initializr API

API for generating Spring Boot projects with customizable dependencies, build tool, language, and Java version. Provides metadata endpoints to discover available starters and configuration options.

- **Human URL:** [https://start.spring.io](https://start.spring.io)
- **Base URL:** `https://start.spring.io`

#### Tags

- Bootstrap
- Code Generation
- Configuration
- Project Generation

#### Properties

- [Documentation](https://github.com/spring-io/start.spring.io)
- [A P I  Endpoint](https://start.spring.io/)
- [OpenAPI](openapi/spring-initializr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spring-initializr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-initializr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring Boot Actuator API

Production-ready features for monitoring and managing Spring Boot applications. Exposes health checks, metrics, environment info, configuration properties, thread dumps, heap dumps, and logger configuration via HTTP endpoints.

- **Human URL:** [https://docs.spring.io/spring-boot/docs/current/reference/html/actuator.html](https://docs.spring.io/spring-boot/docs/current/reference/html/actuator.html)
- **Base URL:** `http://localhost:8080/actuator`

#### Tags

- Health
- Management
- Metrics
- Monitoring

#### Properties

- [Documentation](https://docs.spring.io/spring-boot/docs/current/actuator-api/htmlsingle/)
- [Reference](https://docs.spring.io/spring-boot/docs/current/reference/html/actuator.html)
- [Postman Collection](collections/spring-initializr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-initializr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring MVC Web Framework

Model-View-Controller web framework built on the Servlet API. Supports annotation-driven controllers, content negotiation, validation, data binding, file uploads, CORS, and exception handling in a flexible servlet container.

- **Human URL:** [https://docs.spring.io/spring-framework/docs/current/reference/html/web.html](https://docs.spring.io/spring-framework/docs/current/reference/html/web.html)
- **Base URL:** `http://localhost:8080`

#### Tags

- Annotations
- HTTP
- MVC
- REST
- Web

#### Properties

- [Documentation](https://docs.spring.io/spring-framework/docs/current/reference/html/web.html)
- [API Reference](https://docs.spring.io/spring-framework/docs/current/javadoc-api/)
- [Getting Started](https://spring.io/guides/gs/serving-web-content/)
- [Postman Collection](collections/spring-initializr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-initializr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Spring WebFlux Reactive API

Reactive-stack web framework for building non-blocking, event-driven web applications on top of Project Reactor. Supports annotated controllers and functional endpoints with reactive programming model.

- **Human URL:** [https://docs.spring.io/spring-framework/docs/current/reference/html/web-reactive.html](https://docs.spring.io/spring-framework/docs/current/reference/html/web-reactive.html)
- **Base URL:** `http://localhost:8080`

#### Tags

- Non-Blocking
- Reactive
- Reactor
- WebFlux

#### Properties

- [Documentation](https://docs.spring.io/spring-framework/docs/current/reference/html/web-reactive.html)
- [API Reference](https://docs.spring.io/spring-framework/docs/current/javadoc-api/)
- [Guide](https://spring.io/guides/gs/reactive-rest-service/)
- [Postman Collection](collections/spring-initializr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-initializr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://spring.io/projects/spring-framework)
- [GitHub Organization](https://github.com/spring-projects)
- [GitHub Repository](https://github.com/spring-projects/spring-framework)
- [Blog](https://spring.io/blog)
- [Guides](https://spring.io/guides)
- [Quick  Start](https://spring.io/quickstart)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/spring)
- [Twitter](https://twitter.com/springcentral)
- [YouTube](https://www.youtube.com/user/SpringSourceDev)
- [Maven  Repository](https://mvnrepository.com/artifact/org.springframework/spring-framework)
- [Releases](https://github.com/spring-projects/spring-framework/releases)
- [Documentation](https://docs.spring.io/spring-framework/docs/current/reference/html/)

## Maintainers

**FN:** VMware Broadcom Spring Team
**Email:** spring-projects@vmware.com
**URL:** https://spring.io/team
