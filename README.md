# Hi, I'm Kalabe Kebede

## Senior Software Engineer | Forward Deployed Engineer

**Java · Distributed Systems · AWS · Applied AI**

**Portfolio:** [developer-portfolio-iota-ten.vercel.app](https://developer-portfolio-iota-ten.vercel.app/)

I'm a software engineer with **6+ years** building and modernizing enterprise systems across **banking, financial services, insurance and analytics**.

My core is **Java/Spring Boot and distributed systems**, with **AWS and data engineering** experience and recent **Forward Deployed Engineering** work in **Python/FastAPI, RAG and applied AI**.

I'm most effective on inherited systems: tracing how real workflows behave, finding architecture, security and reliability gaps, and shipping verified changes without replacing what already works.

---

## Featured projects

The [portfolio](https://developer-portfolio-iota-ten.vercel.app/projects) has the full case studies. Short versions:

### Northbank — personal flagship project
**Distributed Systems & Financial Engineering**

[View repository](https://github.com/Kalab21/banking-platform)

An event-driven retail banking platform covering accounts, transfers, cards, loans, credit applications and staff review.

- **11 Spring Boot business services** plus an API gateway and Eureka (13 backend processes), each service owning its PostgreSQL database, with Redis and Kafka events
- Money movement built on **row locking, idempotency keys and a transactional outbox**, with shared ownership checks across services
- **Next.js backend-for-frontend**, so the browser never holds a bearer token
- **1,482 application tests in CI**; the AWS architecture is **modeled in Terraform**, not deployed

`Java 21` `Spring Boot` `Kafka` `PostgreSQL` `Redis` `AWS` `Next.js`

---

### Meridian Lending — team / FDE project
**Forward Deployed Engineering & Applied AI**

[View repository](https://github.com/2463-FDE/KK-meridian-lending)

Team brownfield modernization of a consumer-lending platform across **eight FastAPI backend services**: origination, decisioning, disclosures, servicing, payments and reconciliation.

- **Grounded RAG** policy assistant and a **bounded LangChain/AWS Bedrock agent** with one read-only policy tool, both advisory and staff-only
- **Deterministic LangGraph orchestration** for credit decisions and disclosure assembly; lending decisions stay deterministic and authoritative
- **LangSmith tracing**, plus RBAC, maker-checker servicing, payments and reconciliation controls

`Python` `FastAPI` `RAG` `LangChain` `LangGraph` `AWS Bedrock` `LangSmith` `Next.js`

---

### Policy RAG Platform — secure retrieval / applied AI project

[View repository](https://github.com/Kalab21/policy-rag-platform)

A FastAPI service that answers questions over policy documents, retrieving only from documents the caller is authorized to read.

- **PostgreSQL + pgvector** with HNSW; semantic, full-text and hybrid retrieval, with optional cross-encoder reranking
- **Retrieval-time authorization**, a LangGraph evidence gate, citations or a refusal, and read-only **MCP** tools
- **OpenTelemetry**, held-out retrieval evaluation in CI, and AWS infrastructure **modeled in Terraform**

`Python` `FastAPI` `PostgreSQL` `pgvector` `Hybrid Retrieval` `LangGraph` `MCP` `OpenTelemetry`

---

### Rev-Eval — team / FDE project
**Full-Stack FDE & Platform Engineering**

My work: [kalabek integration branch](https://github.com/RevatureFDEPEP/rev-eval/tree/kalabek) · Organization repository: [RevatureFDEPEP/rev-eval](https://github.com/RevatureFDEPEP/rev-eval)

My contributions live on the `kalabek` branch, not on the organization's main.

A FastAPI and Next.js multi-service assessment platform with trainer and participant workflows.

- Scoring with **idempotent submissions and row locking**, plus reporting and analytics
- **JWT/RBAC** re-verified in each service, record ownership and a trainer-only question bank
- Request-ID propagation, PostgreSQL integration tests and CI

`Python` `FastAPI` `Next.js` `React` `TypeScript` `PostgreSQL` `MongoDB` `Docker`

---

### MarketHub — personal project
**Java full-stack**

[View repository](https://github.com/Kalab21/markethub)

A server-rendered marketplace with Admin, Seller and Buyer workflows, record ownership checks and CSRF protection, built with Spring Boot, Spring MVC, Spring Security, MySQL and Thymeleaf. **87 automated tests**, including 38 authorization tests through the real Spring Security filter chain.

`Java 17` `Spring Boot` `Spring Security` `MySQL` `Thymeleaf`

---

## Skills

- **Backend & distributed systems:** Java 8–21 · Spring Boot · Spring Security · REST APIs · Microservices · Kafka · Event-Driven Architecture · Idempotency
- **Cloud & data:** AWS · ECS/Fargate · Lambda · S3 · RDS · MSK · Glue · Athena · PostgreSQL · MongoDB · Redis · SQL
- **Applied AI & retrieval:** Python · FastAPI · RAG · LangChain · LangGraph · AWS Bedrock · LangSmith · pgvector · Hybrid Retrieval · MCP · AI Evaluation
- **Frontend:** React · Next.js · TypeScript
- **Platform, security & testing:** Docker · Kubernetes · Terraform · GitHub Actions · Jenkins · JWT · RBAC · OpenTelemetry · Prometheus · Grafana · JUnit 5 · Pytest · Playwright · Testcontainers

---

## Contact

- **Email:** [kalabkebe12@gmail.com](mailto:kalabkebe12@gmail.com)
- **Portfolio:** [developer-portfolio-iota-ten.vercel.app](https://developer-portfolio-iota-ten.vercel.app/)
- **GitHub:** [github.com/Kalab21](https://github.com/Kalab21)
- **Location:** Maryland, USA

**Currently focused on:** Java & Spring Engineering · Distributed Systems & Cloud · Applied AI, RAG & Agents
