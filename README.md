<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" alt="Mosiur Zzaman, backend engineer. Java, Spring Boot, event-driven systems." width="100%">
</picture>

I build backend systems at [Rokomari.com](https://www.rokomari.com), Bangladesh's largest e-commerce platform. Most of my work is the part customers never see: stock that doesn't oversell, events that don't get lost, and reports that finish before anyone gives up waiting.

**2+ years in production** · **11 features shipped end to end** · **3,500+ algorithm problems solved** · **ICPC Asia Dhaka Regional, 2021 and 2022**

### What I've built at Rokomari

| The problem | What I built |
|---|---|
| Limited-stock products were overselling | Order-based inventory locking with first-come, first-served reservation |
| The business needed to track user activity as it happened | Kafka pipeline tracking product views, cart events and wishlist activity |
| Product specs were unstructured and full of duplicates | Schema-driven spec model with unit normalization, which enabled automated cross-sell and up-sell |
| Access was granted by hand | Self-service role management, so managers grant and revoke permissions themselves |
| Dashboard reports ran over 1M+ rows | Rewrote the SQL behind them to return fast, accurate numbers |

Also: zero-downtime image migration to Cloudflare R2, a Redis-backed personalized home page, and a RabbitMQ event logging service.

### Projects you can read

- **[Real-Time Score Broadcaster](https://github.com/Mosiur99/Real_Time_Score_Broadcaster)**: pushes live scores to every browser across multiple app servers, using RabbitMQ fanout and WebSocket/STOMP. Scores are stored as an append-only event log.
- **[MicroURL](https://github.com/Mosiur99/URL_Shortener)**: URL shortener with click analytics on Redis, SHA-256 deduplication, and integration tests with Testcontainers. [Live demo](https://url-shortener-jp2d.onrender.com)
- **[SmartTour](https://github.com/Mosiur99/Smart_Tour)**: tour planner for all 64 districts of Bangladesh, with a budget calculator and PDF export. [Live demo](https://smart-tour-700j.onrender.com)

### What I work with

**Main:** Java, Spring Boot, Hibernate, MySQL, Redis, Kafka, RabbitMQ  
**Also:** MongoDB, Elasticsearch, Docker, JUnit 5, Testcontainers, Amazon S3, Cloudflare R2

### Competitive programming

ICPC Asia Dhaka Regional contestant in 2021 and 2022, two 1st places at university contests in 2022, and problem setter for NSTU contests.

[LinkedIn](https://www.linkedin.com/in/md-mosiur-zzaman-4008951b1/) · [Codeforces](https://codeforces.com/profile/mosiur_zaman) · [LeetCode](https://leetcode.com/mosiur) · mosiurzzaman99@gmail.com
