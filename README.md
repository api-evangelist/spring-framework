# Spring Framework

The Spring Framework provides a comprehensive programming and configuration model for modern Java-based enterprise applications on any kind of deployment platform. Spring focuses on the "plumbing" of enterprise applications so teams can focus on application-level business logic, including modules for dependency injection, data access, web development, AOP, and more.

**URL:** https://spring.io/projects/spring-framework

## Tags

AOP, Dependency Injection, Enterprise, Framework, IoC, Java, Microservices, MVC, Spring Boot

## APIs

### Spring Initializr API

API for generating Spring Boot projects with customizable dependencies, build tool, language, and Java version. Provides metadata endpoints to discover available starters and configuration options.

**Human URL:** https://start.spring.io
**Base URL:** https://start.spring.io

**Tags:** Bootstrap, Code Generation, Configuration, Project Generation

**Properties:**
- [Documentation](https://github.com/spring-io/start.spring.io)
- [API Endpoint](https://start.spring.io/)
- [OpenAPI](openapi/spring-initializr-openapi.yml)
- [JSON Schema](json-schema/spring-framework-bean-definition-schema.json)
- [JSON Structure](json-structure/spring-framework-initializr-structure.json)

### Spring Boot Actuator API

Production-ready features for monitoring and managing Spring Boot applications. Exposes health checks, metrics, environment info, configuration properties, thread dumps, and logger configuration.

**Human URL:** https://docs.spring.io/spring-boot/docs/current/reference/html/actuator.html
**Base URL:** http://localhost:8080/actuator

**Tags:** Health, Management, Metrics, Monitoring

**Properties:**
- [Documentation](https://docs.spring.io/spring-boot/docs/current/actuator-api/htmlsingle/)
- [Reference](https://docs.spring.io/spring-boot/docs/current/reference/html/actuator.html)

### Spring MVC Web Framework

Model-View-Controller web framework built on the Servlet API. Supports annotation-driven controllers, content negotiation, validation, data binding, file uploads, CORS, and exception handling.

**Human URL:** https://docs.spring.io/spring-framework/docs/current/reference/html/web.html

**Tags:** Annotations, HTTP, MVC, REST, Web

**Properties:**
- [Documentation](https://docs.spring.io/spring-framework/docs/current/reference/html/web.html)
- [API Reference](https://docs.spring.io/spring-framework/docs/current/javadoc-api/)
- [Getting Started](https://spring.io/guides/gs/serving-web-content/)

### Spring WebFlux Reactive API

Reactive-stack web framework for building non-blocking, event-driven web applications on top of Project Reactor. Supports annotated controllers and functional endpoints.

**Human URL:** https://docs.spring.io/spring-framework/docs/current/reference/html/web-reactive.html

**Tags:** Non-Blocking, Reactive, Reactor, WebFlux

**Properties:**
- [Documentation](https://docs.spring.io/spring-framework/docs/current/reference/html/web-reactive.html)
- [Guide](https://spring.io/guides/gs/reactive-rest-service/)

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [spring-initializr-openapi.yml](openapi/spring-initializr-openapi.yml) | Spring Initializr project generation and metadata API |

### JSON Schemas

| Schema | Description |
|--------|-------------|
| [spring-framework-bean-definition-schema.json](json-schema/spring-framework-bean-definition-schema.json) | Spring bean definition and Initializr project config schema |

### JSON Structures

| Structure | Description |
|-----------|-------------|
| [spring-framework-initializr-structure.json](json-structure/spring-framework-initializr-structure.json) | Spring Initializr metadata and dependency structure |

### JSON-LD Contexts

| Context | Description |
|---------|-------------|
| [spring-framework-context.jsonld](json-ld/spring-framework-context.jsonld) | Spring Framework linked data context |

### Examples

| Example | Description |
|---------|-------------|
| [spring-framework-generate-project-example.json](examples/spring-framework-generate-project-example.json) | Generate Maven Spring Boot project with web, JPA, security starters |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [spring-framework-rules.yml](rules/spring-framework-rules.yml) | API design rules for Spring Framework conventions |

### Naftiko Capabilities

| Capability | Description |
|------------|-------------|
| [capabilities/project-bootstrapping.yaml](capabilities/project-bootstrapping.yaml) | Project bootstrapping workflow (discover options, generate projects) |
| [capabilities/shared/spring-initializr.yaml](capabilities/shared/spring-initializr.yaml) | Shared Spring Initializr consumer definition |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [spring-framework-vocabulary.yml](vocabulary/spring-framework-vocabulary.yml) | Spring Framework domain vocabulary and terminology |

## Common Properties

- [Website](https://spring.io/projects/spring-framework)
- [GitHub Organization](https://github.com/spring-projects)
- [GitHub Repository](https://github.com/spring-projects/spring-framework)
- [Blog](https://spring.io/blog)
- [Guides](https://spring.io/guides)
- [Quick Start](https://spring.io/quickstart)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/spring)
- [Twitter](https://twitter.com/springcentral)
- [YouTube](https://www.youtube.com/user/SpringSourceDev)
- [Maven Repository](https://mvnrepository.com/artifact/org.springframework/spring-framework)
- [Documentation](https://docs.spring.io/spring-framework/docs/current/reference/html/)

## Maintainers

**Name:** VMware Broadcom Spring Team  
**Email:** spring-projects@vmware.com  
**URL:** https://spring.io/team
