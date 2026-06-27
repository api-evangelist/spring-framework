---
title: "MongoDB-backed Spring Batch jobs and more in Spring Boot 4.1"
url: "https://spring.io/blog/2026/06/21/spring-boot-41-and-spring-batch"
date: "2026-06-21"
author: "joshlong"
feed_url: "https://spring.io/blog.atom"
---
Spring Boot 4.1 adds MongoDB support for Spring Batch's JobRepository, removing the need for a separate SQL database to store batch metadata. The walkthrough builds a complete example storing batch metadata in MongoDB while reading from a CSV file and writing to PostgreSQL, covering infrastructure setup, tasklet and chunk-based step configuration, plus bonus sections on GraalVM native image compilation and lazy datasource connections.
