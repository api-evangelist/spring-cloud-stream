---
title: "MongoDB-backed Spring Batch jobs and more in Spring Boot 4.1"
url: "https://spring.io/blog/2026/06/21/spring-boot-41-and-spring-batch"
date: "2026-06-21"
author: "joshlong"
feed_url: "https://spring.io/blog.atom"
---
Spring Boot 4.1 introduces MongoDB support for Spring Batch's JobRepository, eliminating the requirement for a separate SQL database. The post walks through a small but complete example that stores batch metadata in MongoDB while reading from CSV and writing to PostgreSQL, including GraalVM native image support.
