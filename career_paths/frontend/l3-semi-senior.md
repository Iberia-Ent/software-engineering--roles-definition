# Frontend Developer · L3 Semi-Senior

[Academy index](../README.md) · [Frontend overview](./README.md)

## Purpose

Explain the delivery judgement and ownership expected at L3, with direct references to the
technical and behavioural criteria used in assessment.

## Audience

Product Owner, Product Manager, Delivery Lead, and Technical Lead. Frontend Developer, Coach,
and Mentor review technical evidence against the chapter.

## Overview

L3 deepens design, architecture, and quality judgement in the assigned track. The source
combines advanced technical criteria with communication, flexibility, urgency, and ownership.
The person should be able to explain choices and carry work through to completion without the
lead having to chase status.

## Product-team context

An illustrative assignment is a customer-facing feature that combines state management, API
consumption, and accessible interactions. The Developer should clarify how the solution supports
the user journey and what quality risks remain. Technical depth should make the delivery easier
to reason about, not make the implementation harder for the team to maintain.

When scope changes or time pressure increases, stakeholders should continue receiving clear
updates and realistic alternatives. Ownership does not mean hiding difficulties or avoiding
technical review; it means keeping responsibility for moving the work forward and involving
others when their input is needed.

## Evidence stakeholders can discuss

Review a decision the Developer explained, a feature taken from clarification through delivery,
and an occasion when priorities or requirements changed. Pair those observations with technical
evidence such as tests, accessibility audits, and implementation review. This connects product
impact with demonstrated competence instead of relying on confidence in meetings.

## Individual criterion index

Each link jumps to the exact criterion text on this page.

| Area | Individual criterion |
| --- | --- |
| Common | [Advanced JavaScript](#item-l3-common-technical-criteria-both-tracks-advanced-javascript) |
| Common | [Advanced TypeScript](#item-l3-common-technical-criteria-both-tracks-advanced-typescript) |
| Common | [SOLID principles](#item-l3-common-technical-criteria-both-tracks-solid-principles) |
| Common | [GraphQL](#item-l3-common-technical-criteria-both-tracks-graphql) |
| Common | [Basic NestJS/Express](#item-l3-common-technical-criteria-both-tracks-basic-nestjsexpress) |
| Common | [Intermediate CI/CD](#item-l3-common-technical-criteria-both-tracks-intermediate-cicd) |
| Common | [OpenAPI/Swagger](#item-l3-common-technical-criteria-both-tracks-openapiswagger) |
| Common | [Accessibility](#item-l3-common-technical-criteria-both-tracks-a11y) |
| Track A | [React](#item-l3-track-a-spa-legacy-react) |
| Track A | [Angular](#item-l3-track-a-spa-legacy-angular) |
| Track B | [Astro](#item-l3-track-b-astro-aem-astro) |
| Track B | [AEM](#item-l3-track-b-astro-aem-aem) |
| Track B | [Universal Editor](#item-l3-track-b-astro-aem-ue) |
| Track B | [CSS layer strategy](#item-l3-track-b-astro-aem-css) |
| Track B | [Performance and RUM](#item-l3-track-b-astro-aem-performance-tuning-rum) |
| Track B | [Testing](#item-l3-track-b-astro-aem-testing) |
| Track B | [Accessibility audits](#item-l3-track-b-astro-aem-a11y) |
| Soft skills | [Communication](#item-l3-soft-skills-communication) |
| Soft skills | [Pressure Tolerance](#item-l3-soft-skills-pressure-tolerance) |
| Soft skills | [Flexibility](#item-l3-soft-skills-flexibility) |
| Soft skills | [Sense of Urgency](#item-l3-soft-skills-sense-of-urgency) |
| Soft skills | [Ownership](#item-l3-soft-skills-ownership) |

## Detailed criteria

The criteria below are reproduced from the English career-path chapter and grouped
by area. They describe technical expectations; the product interpretation explains
why they matter to delivery and does not add a separate promotion threshold.

### Common technical criteria (both tracks)

<a id="detail-l3-common"></a>

[Source criteria](./Frontend_Career_Path_Chapter.md#criteria-l3-common-technical-criteria-both-tracks)

For a feature spanning frontend behaviour and APIs, assess whether the Developer can explain
type and state boundaries, choose patterns that reduce coupling, document the API contract, and
maintain automated quality checks. Discuss the trade-offs and follow-up risks, not just
framework fluency.

- **Advanced JavaScript:** `this`, `call`/`apply`/`bind`, IIFE, prototypal inheritance, closures, event loop/call stack. <a id="item-l3-common-technical-criteria-both-tracks-advanced-javascript"></a>
- **Advanced TypeScript:** abstract classes, union/intersection types, `keyof`, type aliases, `unknown`. <a id="item-l3-common-technical-criteria-both-tracks-advanced-typescript"></a>
- **SOLID principles:** encapsulation, abstraction, 3+ design patterns (singleton, observer, strategy). <a id="item-l3-common-technical-criteria-both-tracks-solid-principles"></a>
- **GraphQL:** API design and consumption. <a id="item-l3-common-technical-criteria-both-tracks-graphql"></a>
- **Basic NestJS/Express:** server, database connections (MongoDB/PostgreSQL), JWT authentication. <a id="item-l3-common-technical-criteria-both-tracks-basic-nestjsexpress"></a>
- **Intermediate CI/CD:** ESLint/Prettier/SonarQube, CD to staging, automated tests. <a id="item-l3-common-technical-criteria-both-tracks-intermediate-cicd"></a>
- **OpenAPI/Swagger:** navigable technical documentation. <a id="item-l3-common-technical-criteria-both-tracks-openapiswagger"></a>
- **A11y:** axe audits, WCAG 2.1 level A, focus management in modals/forms. <a id="item-l3-common-technical-criteria-both-tracks-a11y"></a>

### Track-specific criteria

#### Track A (SPA Legacy)

<a id="detail-l3-track-a"></a>

[Source criteria](./Frontend_Career_Path_Chapter.md#criteria-l3-track-a-spa-legacy)

For React, examine state ownership, server-data handling, boundaries for failure, and whether
memoisation is justified. For Angular, discuss routing, change detection, state patterns, and
the practical risk of extending legacy code. The source expects informed evaluation, not
indiscriminate adoption of libraries.

- **React:** Redux/Zustand, Suspense, Error Boundaries, React Query, appropriate use of `useMemo`/`useCallback`, Storybook. <a id="item-l3-track-a-spa-legacy-react"></a>
- **Angular:** advanced routing (outlets, guards, lazy loading), custom pipes/directives, OnPush change detection, NgRx/NGXS, i18n, legacy app assessment. <a id="item-l3-track-a-spa-legacy-angular"></a>

#### Track B (Astro + AEM)

<a id="detail-l3-track-b"></a>

[Source criteria](./Frontend_Career_Path_Chapter.md#criteria-l3-track-b-astro-aem)

Discuss rendering and Core Web Vitals, complex content-fragment references and editor behaviour,
CSS layer ownership, real-user performance evidence, and parameterised tests. Technical
reviewers should connect each choice to measured product behaviour.

- **Astro:** streaming, CWV opt. <a id="item-l3-track-b-astro-aem-astro"></a>
- **AEM:** nested CFs, refs. <a id="item-l3-track-b-astro-aem-aem"></a>
- **UE:** complex editors. <a id="item-l3-track-b-astro-aem-ue"></a>
- **CSS:** layer strategy (L0–L3). <a id="item-l3-track-b-astro-aem-css"></a>
- Performance tuning (RUM). <a id="item-l3-track-b-astro-aem-performance-tuning-rum"></a>
- **Testing:** parametrize. <a id="item-l3-track-b-astro-aem-testing"></a>
- **A11y:** audits, keyboard nav. <a id="item-l3-track-b-astro-aem-a11y"></a>

### Soft skills

<a id="detail-l3-soft-skills"></a>

[Source criteria](./Frontend_Career_Path_Chapter.md#criteria-l3-soft-skills)

Use an end-to-end delivery example to assess clarity with less experienced colleagues, calm
communication during scope changes, urgency based on blockers, and ownership without status
chasing. Confirm that flexibility preserved the quality intent.

| Competency | Observable indicators |
| --- | --- |
| <a id="item-l3-soft-skills-communication"></a>**Communication** | Explains technical decisions clearly to Technical Leads and less experienced Developers. |
| <a id="item-l3-soft-skills-pressure-tolerance"></a>**Pressure Tolerance** | Maintains quality and communication during critical sprints or scope changes. |
| <a id="item-l3-soft-skills-flexibility"></a>**Flexibility** | Adapts solutions when requirements change without prolonged blockers. |
| <a id="item-l3-soft-skills-sense-of-urgency"></a>**Sense of Urgency** | Prioritises correctly, identifies blockers, and addresses them first. |
| <a id="item-l3-soft-skills-ownership"></a>**Ownership** | Owns tasks from start to finish without requiring the lead to chase status updates. |

## Promotion gate

The [L3 promotion gate](./Frontend_Career_Path_Chapter.md#criteria-l3-promotion-gate) specifies
80% hard skills and 100% soft skills under the general assessment criteria. Discuss whether the
evidence is consistent across real work, and distinguish technical judgement from simply
completing a larger volume of tasks.

## Source and navigation

[Frontend source chapter](./Frontend_Career_Path_Chapter.md)

[Previous level: L2](./l2-jr-advanced.md) · [Frontend overview](./README.md) ·
[Next level: L4](./l4-ssr-advanced.md)
