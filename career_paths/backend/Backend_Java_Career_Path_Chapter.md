# Backend Java · Career Path Chapter

## Purpose

Provide a searchable English transcription of the criteria in the supplied Globant Backend Java
presentation dated 29 October 2026. Technical criteria below preserve the presentation's meaning;
the separate seniority pages add stakeholder-oriented explanations, not new assessment rules.

## Audience

Product Owner, Product Manager, Delivery Lead, and Technical Lead evaluating Academy contribution.
Backend Developer, Coach, and Mentor use the criteria for technical calibration.

## Overview

The presentation describes five levels across seven technical and behavioural areas. Pages 2–3
contain level criteria, page 4 contains promotion gates and evidence, and page 5 describes
cross-cutting expectations. Experience ranges are references, not automatic promotion dates.

[Profile overview](./README.md)

## L1: Junior

Reference experience: 0–12 months. Criteria: presentation pages 2–3.

### L1 role focus

Learn Java Backend fundamentals, work safely with guidance, and build reliable delivery habits.

### L1 Java and Spring

Modern Java basics, object-oriented programming, and collections. Exceptions, Optional, and basic
Streams. Spring Boot application structure.

### L1 concurrency and performance

Understand threads and shared state. Avoid unsafe concurrent changes. Measure before optimising.

### L1 engineering and security

Clean code and review basics. Secure coding: validate input and do not expose secrets. Document
relevant decisions.

### L1 APIs and testing

REST basics and simple controllers. Unit tests for business logic. Basic clean code and SOLID
awareness.

### L1 architecture and integration

Understand three-layer architecture, use basic REST clients, and recognise domain concepts.

### L1 data resilience and AI literacy

JPA/JDBC basics and simple queries. Relational tables and normalisation. Recognise agents, prompts,
and tools.

### L1 promotion gate

Reliable execution, basic Java/Spring and testing, clear communication, and working with guidance.
Evidence for L1 → L2: reliable delivery, unit/integration tests, and basic stack understanding.
Source: presentation page 4.

## L2: Jr Advance

Reference experience: 12–24 months. Criteria: presentation pages 2–3.

### L2 role focus

Deliver standard Backend work, use Spring Boot with limited guidance, and participate actively
in reviews.

### L2 Java and Spring

Streams and functional style. Configuration, profiles, and Maven. Validation, JSON, and Actuator
basics.

### L2 concurrency and performance

Use basic concurrency constructs. Understand blocking operations. Identify obvious bottlenecks.

### L2 engineering and security

Apply SOLID and patterns. OWASP basics: SQL injection, XSS, and CSRF. Communicate risks early.

### L2 APIs and testing

OpenAPI/Swagger and integration tests. API validation and standard errors. Use patterns with
guidance.

### L2 architecture and integration

Apply hexagonal and vertical-slice basics. Use RestClient or Feign with guidance. Learn DDD
vocabulary.

### L2 data resilience and AI literacy

Transactions, indexes, normalisation, and N+1. Use Flyway and feature flags. Understand RAG, MCP,
and skills.

### L2 promotion gate

Consistent delivery; standard APIs, JPA, Flyway, and CI/CD; basic risk and security awareness;
limited supervision. Evidence for L2 → L3: independent stories, API/data quality, standard CI/CD,
and security practices. Source: presentation page 4.

## L3: Semi Senior

Reference experience: 24–42 months. Criteria: presentation pages 2–3.

### L3 role focus

Own regular Backend scope, choose sound solutions, and work independently in the squad.

### L3 Java and Spring

Production-ready Spring Boot, dependency management, exception handling, and reusable patterns.

### L3 concurrency and performance

Apply concurrency safely. Use virtual threads when appropriate. Analyse latency and throughput.

### L3 engineering and security

Improve design and testability. Use Spring Security with OAuth2/JWT. Explain technical decisions.

### L3 APIs and testing

API First and Code First. Contract and E2E testing. ArchUnit and Karate in standard cases.

### L3 architecture and integration

Design maintainable boundaries. Apply DDD and design patterns. Use event-driven flows and listeners.

### L3 data resilience and AI literacy

Control SQL and locking. Apply circuit breakers, retries, and Redis. Use outbox, idempotency, and
eventual consistency.

### L3 promotion gate

Independent ownership, sound architecture and data decisions, contract/E2E/performance quality,
and active community contribution. Evidence for L3 → L4: owns Backend scope, improves architecture
and quality, mentors, and contributes to the community of practice. Source: presentation page 4.

## L4: SSR Advance

Reference experience: 42–60 months. Criteria: presentation pages 2–3.

### L4 role focus

Drive technical quality in the squad, mentor others, and influence design and delivery decisions.

### L4 Java and Spring

JVM memory, garbage collection, profiling, and tuning. Advanced Spring patterns. Version
compatibility and upgrades.

### L4 concurrency and performance

Review performance risks, tune critical paths, and explain trade-offs with evidence.

### L4 engineering and security

Drive practice improvements. Review dependencies, containers, and IAM. Mentor peers.

### L4 APIs and testing

Versioning, pagination, and idempotency. Performance and mutation testing. Make evidence-based
quality decisions.

### L4 architecture and integration

Own architecture for complex scope. Apply Volatility Architecture: Manager, Engine, Resource Access.
Make integration trade-offs.

### L4 data resilience and AI literacy

Design safe migrations and schema evolution. Handle dead-letter queues (DLQ), duplicates, and
message ordering. Evaluate AI outputs, privacy, and cost.

### L4 promotion gate

Technical influence, mentoring and standards, and ownership of resilience, cloud, security, and
observability. Evidence for L4 → L5: sets Backend standards, influences across teams, and
demonstrates sustained Senior impact. Source: presentation page 4.

## L5: Senior

Reference experience: 60+ months. Criteria: presentation pages 2–3.

### L5 role focus

Set Backend standards, shape capability growth, and act as a reference across products and suppliers.

### L5 Java and Spring

Define Java/Spring standards, guide platform evolution, and make performance and maintainability
trade-offs.

### L5 concurrency and performance

Define performance principles, guide capacity and scalability decisions, and mentor teams on safe
concurrency.

### L5 engineering and security

Define engineering and security standards, align teams and suppliers, and raise Backend capability.

### L5 APIs and testing

Own API governance and compatibility. Set testing strategy and quality criteria. Prevent low-value
or fragile automation.

### L5 architecture and integration

Set architecture direction, align patterns across domains, and review long-term evolution and
technical risk.

### L5 data resilience and AI literacy

Define persistence and resilience standards. Guide event/API schema evolution. Set responsible use
of agents, RPI, prompts, MCP, RAG, skills, and tools.

### L5 promotion gate

Backend reference, cross-team and supplier alignment, standards and capability growth, and
responsible AI literacy. Source: presentation page 4. No L6 progression is defined in this material.

## General promotion criteria

Promotion is based on demonstrated impact, not only tenure. Hard skills, autonomy, communication,
quality ownership, and safe use of the stack must be observable in real squad work. From
Semi-Senior onwards, community contribution, mentoring, and improvement proposals are expected.
At Senior, standards, alignment, and capability uplift extend across products and suppliers.
Source: presentation page 4.

## Cloud and delivery expectations

Progress from Docker, Docker Compose, Git, GitHub, Maven, and GitHub Actions basics to safe use of
ECS, Fargate, S3, ECR, CodeArtifact, API Gateway, SQS, SNS, EventBridge, RDS, Aurora, DynamoDB,
ElastiCache, AppConfig, Secrets Manager, and Parameter Store.

At Senior level, understand operational and security trade-offs in the approved AWS stack,
pipelines, credentials, and IAM roles and policies, without taking over Cloud Engineer
implementation work. Understand GitHub Flow and Gitflow and apply them according to team maturity.
Source: presentation page 5.

## Security expectations

Apply OAuth2 and JWT with Spring Security. OWASP Top 10 awareness includes SQL injection, XSS,
CSRF, and access control. Protect secrets and personal data.

Understand secure containers, dependency vulnerabilities, and supply-chain risks. Do not introduce
dependencies, credentials, APIs, or AWS services without understanding their security impact.
Source: presentation page 5.

## Observability expectations

Build services with useful metrics, logs, and distributed traces. Use OpenTelemetry and Dynatrace.
Understand dashboards, alerts, service-level indicators/objectives (SLI/SLO), and incident response.
Operational ownership grows with seniority: explain system behaviour, correlate signals, learn
from incidents, and improve observability as part of normal development.
Source: presentation page 5.

## AI and community expectations

AI literacy covers agents, prompts, MCP, RAG, skills, tools, and RPI as concepts. Evaluate outputs,
understand prompt injection, privacy, and cost, retain human judgement, and understand prompt/model
versioning. The presentation names RPI without expanding the acronym.

From Semi-Senior onwards, contribute to communities of practice, mentor peers, and propose
improvements to the Backend stack, quality, security, delivery, or observability model.
Source: presentation page 5.
