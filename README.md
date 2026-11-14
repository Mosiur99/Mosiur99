<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" alt="Mosiur Zzaman, backend engineer. Java, Spring Boot, event-driven systems, AI-automated workflows." width="100%">
</picture>

I'm a backend engineer at [Rokomari.com](https://www.rokomari.com), building Java and Spring Boot systems for a large-scale e-commerce platform. I care most about correctness under concurrency, reliable event-driven processing and fast data access. I run my day-to-day engineering through AI agents, so planning, coding, testing and reviews move faster without cutting corners.

**2+ years in production** · **3,500+ algorithm problems solved** · **ICPC Asia Dhaka Regional, 2021 and 2022**

### How I work

I own features from requirement to production. I break the requirement down, check its business impact, and decide whether to ship it all at once or in phases. Then I build it, test it, get sign-off from the people who will use it, release it, and watch it in production with a rollback ready.

AI is part of that loop. I use Claude Code with custom skills and agentic workflows to draft plans, generate and refactor code, write tests and review changes, and Cursor and ChatGPT for exploration. I still review every line, and the design decisions stay mine.

### What I build

| Area | Approach |
|---|---|
| Concurrency | Inventory reservation with row-level locking and transactional control |
| Event-driven processing | Pipelines and asynchronous consumers with Kafka and RabbitMQ |
| Data modeling | Normalized, schema-driven models |
| Performance | Redis caching, query and index tuning, keyset pagination, chunked batch processing |
| Access control | Self-service role-based access control |
| Data consistency | After-commit index updates, database constraints, atomic updates, Liquibase migrations |
| Reliability | Log-driven diagnosis, production monitoring, rollback plans |
| AI-automated engineering | Custom Claude Code skills and agent workflows for planning, coding, testing and review |

### Projects you can read

- **[PayLedger](https://github.com/Mosiur99/payledger)**: a double-entry ledger and payments backend in two services. Transfers stay correct under concurrency and retries: accounts are locked in a fixed order, idempotency keys commit with the money, and a transactional outbox publishes every movement to Kafka for an idempotent consumer with a dead-letter topic. Secured with Keycloak, observed with Prometheus, Grafana and tracing, tested with Testcontainers, and shipped with GitHub Actions and a Helm chart.
- **[Real-Time Score Broadcaster](https://github.com/Mosiur99/Real_Time_Score_Broadcaster)**: pushes live scores to every browser across multiple app servers, using RabbitMQ fanout and WebSocket/STOMP. Scores are stored as an append-only event log.
- **[SmartTour](https://github.com/Mosiur99/Smart_Tour)**: trip planner for all 64 districts of Bangladesh, with a budget calculator and PDF export. [Live demo](https://smart-tour-700j.onrender.com)

### What I work with

**Main:** Java, Spring Boot, Hibernate, MySQL, PostgreSQL, Redis, Kafka, RabbitMQ  
**Also:** MongoDB, Elasticsearch, Liquibase, Flyway, Spring Security, Keycloak, Docker, Kubernetes, Helm, GitHub Actions, GitLab CI, Prometheus, Grafana, JUnit 5, Mockito, Testcontainers, Amazon S3  
**AI-assisted development:** Claude Code (custom skills, agentic workflows), Cursor, ChatGPT

### Competitive programming

ICPC Asia Dhaka Regional contestant in 2021 and 2022, two 1st places at university contests in 2022, and problem setter for NSTU contests.

[LinkedIn](https://www.linkedin.com/in/md-mosiur-zzaman-4008951b1/) · [Codeforces](https://codeforces.com/profile/mosiur_zaman) · [LeetCode](https://leetcode.com/mosiur) · mosiurzzaman99@gmail.com
