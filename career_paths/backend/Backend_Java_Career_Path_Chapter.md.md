# Backend Java · Career Path Chapter

**Globant Academy · Iberia**  
**Source:** Backend Java Career Path presentation, dated 29 October 2026

## Purpose

Provide a searchable English Markdown companion to the supplied Backend Java career-path
presentation. The criteria in this document represent the material described in the PDF. This
document is intended to make that material easier to navigate and reference; it does not replace
the original presentation or create additional assessment rules.

## Audience

The primary audience is the Product Owner, Product Manager, Delivery Lead, and Technical Lead
working with Academy Backend Developers. Backend Developers, Coaches, Mentors, and technical
reviewers use the criteria for technical calibration.

Product stakeholders can discuss observable delivery outcomes, communication, and how risks were
handled. Specialist reviewers validate the underlying technical proficiency.

## Overview

The presentation describes five career levels across seven technical and behavioural areas:

1. Role focus.
2. Java and Spring.
3. Concurrency and performance.
4. Engineering and security.
5. APIs and testing.
6. Architecture and integration.
7. Data, resilience, and AI literacy.

It also includes promotion gates, general promotion expectations, and cross-cutting expectations
for cloud and delivery, security, observability, AI, and community contribution.

The experience ranges below are references, not automatic promotion dates. Promotion should be
discussed against demonstrated contribution, autonomy, impact, and the person's opportunity to
show the relevant criteria.

[Backend profile overview](./README.md) ·
[Original Backend Java Career Path presentation](./Backend_Java_Career_Path_-_Globant.pdf)

## Career levels

| Level | Name in source | Experience reference |
| --- | --- | --- |
| L1 | Junior | 0–12 months |
| L2 | Jr Advance | 12–24 months |
| L3 | Semi-Senior | 24–42 months |
| L4 | SSR Advance | 42–60 months |
| L5 | Senior | 60+ months |

The source defines levels L1–L5. It does not define an L6 Backend progression in this material.

## L1 · Junior

**Experience reference:** 0–12 months  
**Source location:** presentation pages 2–4

### Role focus

Learn Java Backend fundamentals, work safely with guidance, and build reliable delivery habits.

### Java and Spring

Understand modern Java basics, object-oriented programming, and collections. Use exceptions,
`Optional`, and basic Streams. Understand Spring Boot application structure.

### Concurrency and performance

Understand threads and shared state. Avoid unsafe concurrent changes. Measure before
optimising.

### Engineering and security

Follow clean-code and review basics. Validate input, do not expose secrets, and document
relevant decisions.

### APIs and testing

Understand REST basics and simple controllers. Write unit tests for business logic. Build basic
clean-code and SOLID awareness.

### Architecture and integration

Understand three-layer architecture, use basic REST clients, and recognise domain concepts.

### Data, resilience, and AI literacy

Understand JPA/JDBC basics and simple queries. Recognise relational tables and normalisation.
Recognise the concepts of agents, prompts, and tools.

### Promotion gate and evidence

The source describes reliable execution, basic Java/Spring and testing knowledge, clear
communication, and working with guidance.

For the L1 → L2 transition, the presentation identifies reliable delivery, unit and integration
tests, and basic understanding of the stack as evidence.

## L2 · Jr Advance

**Experience reference:** 12–24 months  
**Source location:** presentation pages 2–4

### Role focus

Deliver standard Backend work, use Spring Boot with limited guidance, and participate actively
in reviews.

### Java and Spring

Use Streams and functional style. Understand configuration, profiles, and Maven. Apply
validation and JSON handling, and understand Actuator basics.

### Concurrency and performance

Use basic concurrency constructs. Understand blocking operations and identify obvious
bottlenecks.

### Engineering and security

Apply SOLID principles and patterns. Understand OWASP basics, including SQL injection, XSS, and
CSRF. Communicate risks early.

### APIs and testing

Use OpenAPI/Swagger and integration tests. Apply API validation and standard error handling.
Use patterns with guidance.

### Architecture and integration

Understand and apply the basics of hexagonal architecture and vertical slices. Use RestClient or
Feign with guidance. Learn DDD vocabulary.

### Data, resilience, and AI literacy

Understand transactions, indexes, normalisation, and N+1 issues. Use Flyway and feature flags.
Understand RAG, MCP, and skills as concepts.

### Promotion gate and evidence

The source describes consistent delivery; use of standard APIs, JPA, Flyway, and CI/CD; basic
risk and security awareness; and work with limited supervision.

For the L2 → L3 transition, the presentation identifies independent stories, API and data
quality, standard CI/CD, and security practices as evidence.

## L3 · Semi-Senior

**Experience reference:** 24–42 months  
**Source location:** presentation pages 2–4

### Role focus

Own regular Backend scope, choose sound solutions, and work independently within the squad.

### Java and Spring

Build production-ready Spring Boot services. Manage dependencies and exception handling, and use
reusable patterns.

### Concurrency and performance

Apply concurrency safely. Use virtual threads when appropriate. Analyse latency and throughput.

### Engineering and security

Improve design and testability. Use Spring Security with OAuth2/JWT. Explain technical
decisions.

### APIs and testing

Understand API First and Code First approaches. Apply contract and end-to-end testing. Use
ArchUnit and Karate in standard cases.

### Architecture and integration

Design maintainable boundaries. Apply DDD and design patterns. Understand event-driven flows
and listeners.

### Data, resilience, and AI literacy

Control SQL and locking. Apply circuit breakers, retries, and Redis. Understand outbox,
idempotency, and eventual consistency.

### Promotion gate and evidence

The source describes independent ownership, sound architecture and data decisions, contract,
end-to-end and performance quality, and active community contribution.

For the L3 → L4 transition, the presentation identifies ownership of Backend scope, architecture
and quality improvement, mentoring, and contribution to the community of practice as evidence.

## L4 · SSR Advance

**Experience reference:** 42–60 months  
**Source location:** presentation pages 2–4

### Role focus

Drive technical quality in the squad, mentor others, and influence design and delivery
decisions.

### Java and Spring

Understand JVM memory, garbage collection, profiling, and tuning. Apply advanced Spring
patterns. Manage version compatibility and upgrades.

### Concurrency and performance

Review performance risks, tune critical paths, and explain trade-offs with evidence.

### Engineering and security

Drive practice improvements. Review dependencies, containers, and IAM. Mentor peers.

### APIs and testing

Apply versioning, pagination, and idempotency. Use performance and mutation testing. Make
evidence-based quality decisions.

### Architecture and integration

Own architecture for complex scope. Apply Volatility Architecture: Manager, Engine, and
Resource Access. Make integration trade-offs.

### Data, resilience, and AI literacy

Design safe migrations and schema evolution. Handle dead-letter queues (DLQ), duplicates, and
message ordering. Evaluate AI outputs, privacy, and cost.

### Promotion gate and evidence

The source describes technical influence, mentoring and standards, and ownership of resilience,
cloud, security, and observability.

For the L4 → L5 transition, the presentation identifies setting Backend standards, influencing
across teams, and demonstrating sustained Senior impact as evidence.

## L5 · Senior

**Experience reference:** 60+ months  
**Source location:** presentation pages 2–4

### Role focus

Set Backend standards, shape capability growth, and act as a reference across products and
suppliers.

### Java and Spring

Define Java/Spring standards, guide platform evolution, and make performance and maintainability
trade-offs.

### Concurrency and performance

Define performance principles, guide capacity and scalability decisions, and mentor teams on
safe concurrency.

### Engineering and security

Define engineering and security standards, align teams and suppliers, and raise Backend
capability.

### APIs and testing

Own API governance and compatibility. Set testing strategy and quality criteria. Prevent
low-value or fragile automation.

### Architecture and integration

Set architecture direction, align patterns across domains, and review long-term evolution and
technical risk.

### Data, resilience, and AI literacy

Define persistence and resilience standards. Guide event and API schema evolution. Set
responsible use of agents, RPI, prompts, MCP, RAG, skills, and tools.

### Promotion gate and evidence

The source describes a Backend reference, cross-team and supplier alignment, standards and
capability growth, and responsible AI literacy.

## General promotion criteria

The presentation states that:

- Promotion is based on demonstrated impact, not only tenure.
- Hard skills should be demonstrated consistently.
- Soft skills should be observable in real squad behaviour.
- Autonomy should already be visible at the next level.
- Quality ownership should be demonstrated in practice.
- Automation and AI should be used responsibly.
- Community contribution, mentoring, and improvement proposals are expected from Semi-Senior
  onwards.
- At Senior level, standards, alignment, and capability uplift extend across products and
  suppliers.

These statements summarise the source and should be considered alongside the level-specific
criteria and the relevant company assessment process.

## Cross-cutting expectations

The presentation also describes expectations that apply across levels and technical areas.
The following sections make those expectations searchable without replacing the original PDF.

### Cloud and delivery

The source describes progression from foundational delivery tools to broader AWS awareness.

Foundational tools and practices include:

- Docker and Docker Compose.
- Git and GitHub.
- Maven.
- GitHub Actions.

The AWS services named in the presentation include:

- ECS, Fargate, S3, and ECR.
- CodeArtifact and API Gateway.
- SQS, SNS, and EventBridge.
- RDS, Aurora, DynamoDB, and ElastiCache.
- AppConfig, Secrets Manager, and Parameter Store.

At Senior level, understand operational and security trade-offs in the approved AWS stack,
pipelines, credentials, and IAM roles and policies. Apply GitHub Flow or Gitflow according to
the maturity and practices of the team.

Cloud awareness does not transfer Cloud Engineer implementation responsibilities to the Backend
Developer. The expected contribution is to understand the service context, collaborate
effectively, and make decisions appropriate to the role.

### Security

The presentation names the following security expectations:

- Apply OAuth2 and JWT with Spring Security.
- Understand OWASP Top 10 risks, including SQL injection, XSS, CSRF, and access control.
- Protect secrets and personal data.
- Understand secure containers, dependency vulnerabilities, and supply-chain risks.
- Consider the security impact of dependencies, credentials, APIs, and AWS services.

Security criteria should be validated by appropriate technical reviewers and applied in the
context of the service and its data.

### Observability

The source expects Backend services to provide useful metrics, logs, and distributed traces. It
names OpenTelemetry and Dynatrace and describes familiarity with:

- Dashboards and alerts.
- Service-level indicators and objectives (SLIs/SLOs).
- Incident response.
- Correlating signals to explain system behaviour.
- Learning from incidents and improving observability as part of normal development.

Operational ownership grows with seniority. This does not imply that every Backend Developer
replaces an SRE or Operations specialist.

### AI literacy and community

The presentation names agents, prompts, MCP, RAG, skills, tools, and RPI as AI-related concepts.
It expects Developers to evaluate outputs and consider prompt injection, privacy, cost, human
judgement, and prompt/model versioning. The presentation names RPI without expanding the
acronym; this document therefore preserves it without inferring a definition.

From Semi-Senior onwards, the source expects contribution to communities of practice, mentoring
peers, and proposals to improve the Backend stack, quality, security, delivery, or observability
model.

## Source and scope

This Markdown chapter is a searchable companion to the supplied
[Backend Java Career Path presentation](./Backend_Java_Career_Path_-_Globant.pdf). When
interpreting the source or resolving wording questions, consult the presentation directly.

Individual seniority pages with additional product-team context may be added later. They should
link to the criteria in this chapter and must not silently introduce new promotion gates.

[Return to the Backend overview](./README.md) · [Academy index](../README.md)
