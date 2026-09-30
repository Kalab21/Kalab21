# Hi, I'm Kalabe Kebede

## Senior Software Engineer | Forward Deployed Engineer

**Portfolio:** [developer-portfolio-iota-ten.vercel.app](https://developer-portfolio-iota-ten.vercel.app/)

I'm a software engineer with **6+ years of experience** building and modernizing enterprise systems across **banking, financial services, insurance, analytics, and AI-enabled applications**.

My core is **Java, Spring Boot, distributed systems, Kafka, SQL and AWS**. More recently I've worked in **Python/FastAPI, RAG and data engineering**, and I build full-stack with **Next.js / React / TypeScript** on top of my own Java services.

I'm most useful on existing systems: understanding the business problem, tracing how a distributed workflow really behaves, finding the architecture and security risks, and fixing them without replacing what already works.

---

## Featured projects

The [portfolio](https://developer-portfolio-iota-ten.vercel.app/) has the full case studies. Short versions:

### Northbank — personal flagship project
**Distributed Systems & Financial Engineering · Java full-stack**

[View repository](https://github.com/Kalab21/banking-platform)

An event-driven retail banking platform covering accounts, transfers, cards, loans, credit applications and staff review.

- **11 Spring Boot business services** plus an **API Gateway and Eureka** (13 backend processes in total), with a database per service on PostgreSQL, Redis, and Kafka events
- Money movement built around **row locking, idempotency keys, a transactional outbox** and reconciliation of unknown outcomes
- **JWT/RBAC** with TOTP two-factor login, shared ownership checks, and card numbers masked at the API boundary
- **Next.js / TypeScript console** using a server-side BFF, so the browser never holds a bearer token
- **1,482 automated tests in CI** (backend, frontend and offline Playwright), plus 46 live-stack Playwright tests and 200 full-stack assertions that run on demand
- Docker Compose for the full stack; Terraform describes an **AWS reference architecture that is not deployed**
- Runs on synthetic data only; no real money moves

`Java 17` `Spring Boot` `Kafka` `PostgreSQL` `Redis` `Next.js` `TypeScript` `Docker` `Terraform` `Playwright`

---

### Meridian Lending — team / FDE project
**Forward Deployed Engineering & Applied AI**

[View repository](https://github.com/2463-FDE/KK-meridian-lending)

Team brownfield modernization of a consumer-lending platform: origination, decisioning, disclosures, servicing, payments and reconciliation, across eight FastAPI services.

- Added a **staff-only, read-only RAG policy assistant**. It is advisory: the deterministic decisioning service stays the system of record and the assistant never makes the lending decision
- Strengthened RBAC and service ownership, decision finality, idempotency and auditability
- Worked on the append-only servicing ledger, maker-checker approvals and payment reconciliation
- Wrote specs and ADRs, added automated verification of TILA/APR calculations, and added metrics and tracing
- Fictional demo data and a mocked card processor; no compliance certification is claimed

`Python` `FastAPI` `PostgreSQL` `Redis` `Next.js` `RAG` `Docker` `GitHub Actions`

---

### Rev-Eval — team / FDE project
**Full-Stack FDE & Platform Engineering**

My work: [kalabek integration branch](https://github.com/RevatureFDEPEP/rev-eval/tree/kalabek) · Organization repository: [RevatureFDEPEP/rev-eval](https://github.com/RevatureFDEPEP/rev-eval)

My contributions live on the `kalabek` branch, not on the organization's main.

- Scoring engine with idempotent submissions and locking
- Timed quiz UX with autosave and a submit state machine
- Reporting & Analytics service with aggregate and ranking endpoints
- JWT verification and service-level RBAC; request-ID tracing across services
- PostgreSQL integration tests and Playwright end-to-end coverage

`Python` `FastAPI` `Next.js` `TypeScript` `PostgreSQL` `MongoDB` `Docker` `GitHub Actions`

---

### MarketHub — personal project
**Java full-stack**

[View repository](https://github.com/Kalab21/markethub)

A Java full-stack marketplace with Admin, Seller and Buyer workflows: seller approval, a product catalogue, cart and order checkout. Built with Spring Boot, Spring MVC, Spring Security, JPA/MySQL, Thymeleaf, Docker and GitHub Actions, with 39 automated tests. Checkout creates orders; there is no external payment processor.

`Java 17` `Spring Boot` `Spring Security` `Spring Data JPA` `MySQL` `Docker`

---

## Skills

- **Software & distributed systems:** Java 8–21, Spring Boot, Spring MVC, Spring Security, Spring Data JPA, REST APIs, Microservices, Kafka, API Gateway
- **Data engineering:** Advanced SQL, PostgreSQL, Oracle, MySQL, MongoDB, Redis, ETL/ELT, AWS Athena/Glue/S3, data modeling, Power BI
- **Cloud & DevOps:** AWS, Docker, Kubernetes, GitHub Actions, Jenkins, Maven, CI/CD
- **AI & FDE:** Python, FastAPI, RAG, LLM integration, AI evaluation, Human-in-the-Loop, brownfield analysis, requirements synthesis, ADRs
- **Security & testing:** OAuth2/OIDC, JWT, RBAC, OWASP concepts, JUnit 5, Mockito, Testcontainers, Pytest, Playwright

---

## Contact

- **Email:** [kalabkebe12@gmail.com](mailto:kalabkebe12@gmail.com)
- **GitHub:** [github.com/Kalab21](https://github.com/Kalab21)
- **Portfolio:** [developer-portfolio-iota-ten.vercel.app](https://developer-portfolio-iota-ten.vercel.app/)
- **Location:** Maryland, USA

**Currently focused on:** distributed systems · Forward Deployed Engineering · applied AI
