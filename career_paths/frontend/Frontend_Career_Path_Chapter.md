# Frontend Developer · Career Path Chapter

**Globant Academy · Iberia**

**Coexisting tracks:** A (SPA Legacy) + B (Astro + AEM)

## Purpose

This document provides the professional growth framework for Frontend Developers in Globant
Academy Iberia. It aligns expectations across Technical Leads, Product Owners, Coaches,
Managers, and Developers, and provides clear, objective criteria for promotion decisions.

> A criterion is considered consolidated when the Developer demonstrates it consistently in
> daily work, not just occasionally or in isolated conversations.

## Audience

The primary readers are product-team stakeholders: Product Owner, Product Manager, Delivery Lead,
and Technical Lead. Coach, Mentor, and Frontend Developer use this chapter to validate the
technical evidence behind delivery observations.

The criteria below are an English translation of the supplied chapter. The separate level pages
explain their product context.

## Overview

Read technical and behavioural expectations together. For example, an accessible interface or a
reliable pipeline matters because it supports usable, maintainable product delivery.
Stakeholders should discuss those outcomes and the support needed, while technical reviewers
determine whether the implementation demonstrates the specified skill.

The two tracks describe different technology contexts, not competing career ladders. Confirm
the assigned track and the relevant project opportunities before judging gaps.

The transition rules below are source requirements. The explanatory prose does not create
additional promotion rules.

## Contents

- [Technical tracks](#technical-tracks)
- [Track transition: A to B](#track-transition-a-to-b)
- [Promotion criteria](#promotion-criteria)
- [L1: Junior](#l1-junior)
- [L2: Jr Advanced](#l2-jr-advanced)
- [L3: Semi-Senior](#l3-semi-senior)
- [L4: SSR Advanced](#l4-ssr-advanced)
- [L5: Senior](#l5-senior)
- [Glossary](#glossary)

## Technical tracks

The v2 career path defines two tracks that coexist in client projects.

| Dimension | Track A — SPA Legacy | Track B — Astro + AEM Headless |
| --- | --- | --- |
| Projects | BKI, MMB, CKI, Ancillanes | Iberia Digital Platform, marketing sites |
| Rendering | CSR | SSR |
| Backend | REST APIs | RAC proxy |
| CMS | WCS/Drupal | AEM Content Fragments |
| Stack | React/Angular/AngularJS | Astro + AEM Headless |
| Editor | Not specified | Universal Editor |

## Track transition: A to B

**Migration:** A Track A Developer starting an Astro + AEM project moves to
**L2.5 (intermediate)** for 6–12 months.

The Developer advances to **Track B Full** when maintaining **80%+ of Track A criteria**
and demonstrating **60%+ of Track B criteria**.

The Track A requirement preserves strong React/Angular capability. The Track B requirement
validates the new technical context rather than assuming that existing framework expertise
automatically transfers.

> [!IMPORTANT]
> Soft skills carry over, including communication and problem-solving.
> They do not accelerate technical progression. Track B hard skills must be
> validated independently.

## Promotion criteria

### General criteria

- **80% Hard Skills:** Demonstrated in daily work, 80%+ of the time.
- **100% Soft Skills:** Demonstrated or In progress, with zero Not observed.
- **Evaluation:** Coach for technical evidence, Technical Lead for behaviour,
  Mentor for career development, and Architect for L4+.

### Quick ready-for-promotion checklist

| Transition | Key criteria |
| --- | --- |
| L1 → L2 | Advanced CSS; Event Loop; custom hooks/DI; E2E tests; code reviews; goal orientation |
| L2 → L3 | Advanced TypeScript; SOLID; state management; accessibility audits; architecture proposals; communication |
| L3 → L4 | Security expertise; performance optimisation; active mentoring; visible leadership |
| L4 → L5 | Technical vision; mastery in 2+ areas; mentoring 2+ seniors; business acumen; organisational influence; CTO approval |

> [!WARNING]
> The L5 source gate remains pending final calibration with Technical Leads
> and the client. The checklist above must not be interpreted as a final
> approval mechanism while that calibration is unresolved.

## L1: Junior

[Read the L1 product-team interpretation](./l1-junior.md)

<a id="criteria-l1-common-technical-criteria-both-tracks"></a>

### Common technical criteria — both tracks

- **HTML/CSS ES6+:** semantic HTML, Flexbox/Grid, responsive design, media queries. <a id="item-l1-common-technical-criteria-both-tracks-htmlcss-es6"></a>
- **JavaScript ES6+:** types, functions, modules, async/await, fetch + REST APIs. <a id="item-l1-common-technical-criteria-both-tracks-javascript-es6"></a>
- **Basic TypeScript:** interfaces, types, avoiding `any`. <a id="item-l1-common-technical-criteria-both-tracks-basic-typescript"></a>
- **Git:** clone/add/commit/push, Conventional Commits, basic Gitflow. <a id="item-l1-common-technical-criteria-both-tracks-git"></a>
- **jest/vitest:** basic unit tests with simple mocks. <a id="item-l1-common-technical-criteria-both-tracks-jestvitest"></a>
- **Tooling:** `.env`, `tsconfig`, `vite.config`, `.eslintrc`, `localStorage`, CORS. <a id="item-l1-common-technical-criteria-both-tracks-tooling"></a>
- **Accessibility:** semantic HTML, screen readers, basic awareness. <a id="item-l1-common-technical-criteria-both-tracks-a11y"></a>
- **Cloud:** cloud computing fundamentals and conceptual knowledge of AWS services: EC2, S3, IAM, Lambda. <a id="item-l1-common-technical-criteria-both-tracks-cloud"></a>

### Track-specific criteria

<a id="criteria-l1-track-a-spa-legacy"></a>

#### Track A — SPA Legacy

- **React:** functional components, JSX/TSX, props vs state, `useState`, `useEffect`, React Router. <a id="item-l1-track-a-spa-legacy-react"></a>
- **Angular:** CLI, property/event/two-way binding, HttpClient, template-driven forms, basic Observables. <a id="item-l1-track-a-spa-legacy-angular"></a>

<a id="criteria-l1-track-b-astro-aem"></a>

#### Track B — Astro + AEM

- Vanilla HTML/CSS without a framework. <a id="item-l1-track-b-astro-aem-vanilla-htmlcss-without-a-framework"></a>
- TypeScript for framework-free frontend. <a id="item-l1-track-b-astro-aem-typescript-framework-free-frontend"></a>
- **Astro:** Page, Section, Partial. <a id="item-l1-track-b-astro-aem-astro"></a>
- Basic `@layer` CSS system. <a id="item-l1-track-b-astro-aem-basic-layer-css-system"></a>
- `fetch()` via RAC. <a id="item-l1-track-b-astro-aem-fetch-via-rac"></a>

<a id="criteria-l1-soft-skills"></a>

### Soft skills

| Competency | Observable indicators |
| --- | --- |
| <a id="item-l1-soft-skills-aptitude"></a>**Aptitude** | Learns quickly and retains new concepts. |
| <a id="item-l1-soft-skills-attitude"></a>**Attitude** | Is punctual, meets short deadlines, and asks for help promptly when blocked. |
| <a id="item-l1-soft-skills-reporting"></a>**Reporting** | Communicates clearly in standups without omitting blockers. |
| <a id="item-l1-soft-skills-creative"></a>**Creative** | Suggests simple alternatives to a problem, even without making the final decision. |
| <a id="item-l1-soft-skills-team-player"></a>**Team Player** | Collaborates smoothly and accepts feedback without becoming defensive. |

<a id="criteria-l1-promotion-gate"></a>

### Promotion gate

**80% Hard Skills · 100% Soft Skills**, interpreted through the general criteria.

## L2: Jr Advanced

[Read the L2 product-team interpretation](./l2-jr-advanced.md)

<a id="criteria-l2-common-technical-criteria-both-tracks"></a>

### Common technical criteria — both tracks

- **Advanced CSS:** appropriate use of Sass or Tailwind, atomic design, basic SEO. <a id="item-l2-common-technical-criteria-both-tracks-advanced-css"></a>
- **Event Loop:** debugging in DevTools: breakpoints, call stack, watchers. <a id="item-l2-common-technical-criteria-both-tracks-event-loop"></a>
- **JavaScript:** rest/spread, destructuring, robust error handling. <a id="item-l2-common-technical-criteria-both-tracks-javascript"></a>
- **Basic Node.js:** scripts using `fs`/`dotenv`, project npm scripts. <a id="item-l2-common-technical-criteria-both-tracks-basic-nodejs"></a>
- **Cypress:** basic E2E tests, conceptual understanding of TDD. <a id="item-l2-common-technical-criteria-both-tracks-cypress"></a>
- **Advanced Git:** conflict resolution, constructive code reviews, strategic branching. <a id="item-l2-common-technical-criteria-both-tracks-advanced-git"></a>
- **Basic CI/CD:** reading and debugging GitHub Actions failures. <a id="item-l2-common-technical-criteria-both-tracks-basic-cicd"></a>
- **Accessibility:** basic ARIA attributes, WCAG AA contrast, keyboard navigation, axe DevTools. <a id="item-l2-common-technical-criteria-both-tracks-a11y"></a>

### Track-specific criteria

<a id="criteria-l2-track-a-spa-legacy"></a>

#### Track A — SPA Legacy

- **React:** HOC, custom hooks, `useCallback`, `useContext`, `useReducer`, React Testing Library, problematic re-renders. <a id="item-l2-track-a-spa-legacy-react"></a>
- **Angular:** lazy-loaded modules, dependency injection, reactive forms, RxJS: `map`, `filter`, `switchMap`, `takeUntil`; TestBed. <a id="item-l2-track-a-spa-legacy-angular"></a>

<a id="criteria-l2-track-b-astro-aem"></a>

#### Track B — Astro + AEM

- **TypeScript:** unions, generics. <a id="item-l2-track-b-astro-aem-typescript"></a>
- Five-state management for Sections. <a id="item-l2-track-b-astro-aem-5-states-management-section"></a>
- Custom hooks in React / Partials using the `_prefix` convention. <a id="item-l2-track-b-astro-aem-custom-hooks-reactpartials-prefix-convention"></a>
- AEM Content Fragment models and hydration. <a id="item-l2-track-b-astro-aem-aem-cf-models-hydration"></a>
- **Universal Editor:** `rendererJs`, `component-def`. <a id="item-l2-track-b-astro-aem-ue"></a>
- Design tokens vs hardcoded values. <a id="item-l2-track-b-astro-aem-design-tokens-vs-hardcode"></a>
- DOM budget awareness. <a id="item-l2-track-b-astro-aem-dom-budget-awareness"></a>

<a id="criteria-l2-soft-skills"></a>

### Soft skills

| Competency | Observable indicators |
| --- | --- |
| <a id="item-l2-soft-skills-goal-oriented"></a>**Goal Oriented** | Understands each task's purpose and adapts execution to achieve the outcome. |
| <a id="item-l2-soft-skills-problem-solving"></a>**Problem Solving** | Investigates before escalating and suggests at least one solution when asking for help. |
| <a id="item-l2-soft-skills-analytical"></a>**Analytical** | Breaks complex problems into manageable parts and reviews others' code with sound judgement. |
| <a id="item-l2-soft-skills-documentary"></a>**Documentary** | Provides README files, relevant comments, and clear PR descriptions. |
| <a id="item-l2-soft-skills-initiative"></a>**Initiative** | Takes action to avoid remaining blocked and anticipates impediments. |

<a id="criteria-l2-promotion-gate"></a>

### Promotion gate

**80% Hard Skills · 100% Soft Skills**, interpreted through the general criteria.

## L3: Semi-Senior

[Read the L3 product-team interpretation](./l3-semi-senior.md)

<a id="criteria-l3-common-technical-criteria-both-tracks"></a>

### Common technical criteria — both tracks

- **Advanced JavaScript:** `this`, `call`/`apply`/`bind`, IIFE, prototypal inheritance, closures, event loop/call stack. <a id="item-l3-common-technical-criteria-both-tracks-advanced-javascript"></a>
- **Advanced TypeScript:** abstract classes, union/intersection types, `keyof`, type aliases, `unknown`. <a id="item-l3-common-technical-criteria-both-tracks-advanced-typescript"></a>
- **SOLID principles:** encapsulation, abstraction, three or more design patterns, including singleton, observer, and strategy. <a id="item-l3-common-technical-criteria-both-tracks-solid-principles"></a>
- **GraphQL:** API design and consumption. <a id="item-l3-common-technical-criteria-both-tracks-graphql"></a>
- **Basic NestJS/Express:** server, database connections using MongoDB/PostgreSQL, JWT authentication. <a id="item-l3-common-technical-criteria-both-tracks-basic-nestjsexpress"></a>
- **Intermediate CI/CD:** ESLint/Prettier/SonarQube, continuous delivery to staging, automated tests. <a id="item-l3-common-technical-criteria-both-tracks-intermediate-cicd"></a>
- **OpenAPI/Swagger:** navigable technical documentation. <a id="item-l3-common-technical-criteria-both-tracks-openapiswagger"></a>
- **Accessibility:** axe audits, WCAG 2.1 level A, focus management in modals/forms. <a id="item-l3-common-technical-criteria-both-tracks-a11y"></a>

### Track-specific criteria

<a id="criteria-l3-track-a-spa-legacy"></a>

#### Track A — SPA Legacy

- **React:** Redux/Zustand, Suspense, Error Boundaries, React Query, appropriate use of `useMemo`/`useCallback`, Storybook. <a id="item-l3-track-a-spa-legacy-react"></a>
- **Angular:** advanced routing with outlets, guards, and lazy loading; custom pipes/directives; OnPush change detection; NgRx/NGXS; i18n; legacy application assessment. <a id="item-l3-track-a-spa-legacy-angular"></a>

<a id="criteria-l3-track-b-astro-aem"></a>

#### Track B — Astro + AEM

- **Astro:** streaming, Core Web Vitals optimisation. <a id="item-l3-track-b-astro-aem-astro"></a>
- **AEM:** nested Content Fragments and references. <a id="item-l3-track-b-astro-aem-aem"></a>
- **Universal Editor:** complex editors. <a id="item-l3-track-b-astro-aem-ue"></a>
- **CSS:** layer strategy, L0–L3. <a id="item-l3-track-b-astro-aem-css"></a>
- Performance tuning using Real User Monitoring. <a id="item-l3-track-b-astro-aem-performance-tuning-rum"></a>
- **Testing:** parameterisation. <a id="item-l3-track-b-astro-aem-testing"></a>
- **Accessibility:** audits and keyboard navigation. <a id="item-l3-track-b-astro-aem-a11y"></a>

<a id="criteria-l3-soft-skills"></a>

### Soft skills

| Competency | Observable indicators |
| --- | --- |
| <a id="item-l3-soft-skills-communication"></a>**Communication** | Explains technical decisions clearly to Technical Leads and less experienced Developers. |
| <a id="item-l3-soft-skills-pressure-tolerance"></a>**Pressure Tolerance** | Maintains quality and communication during critical sprints or scope changes. |
| <a id="item-l3-soft-skills-flexibility"></a>**Flexibility** | Adapts solutions when requirements change without prolonged blockers. |
| <a id="item-l3-soft-skills-sense-of-urgency"></a>**Sense of Urgency** | Prioritises correctly, identifies blockers, and addresses them first. |
| <a id="item-l3-soft-skills-ownership"></a>**Ownership** | Owns tasks from start to finish without requiring the lead to chase status updates. |

<a id="criteria-l3-promotion-gate"></a>

### Promotion gate

**80% Hard Skills · 100% Soft Skills**, interpreted through the general criteria.

## L4: SSR Advanced

[Read the L4 product-team interpretation](./l4-ssr-advanced.md)

<a id="criteria-l4-common-technical-criteria-both-tracks"></a>

### Common technical criteria — both tracks

- **Expert TypeScript:** production generics, utility types, basic conditional types, modules and libraries with clean public APIs. <a id="item-l4-common-technical-criteria-both-tracks-expert-typescript"></a>
- **Event loop, closures and memory management:** explanation and practical debugging. <a id="item-l4-common-technical-criteria-both-tracks-event-loop-closures-and-memory-management"></a>
- **OAuth 2.0 / OIDC:** implementation in a production application. <a id="item-l4-common-technical-criteria-both-tracks-oauth-20-oidc"></a>
- **Web security:** XSS, CSRF, CORS misconfiguration, TLS certificates in deployment. <a id="item-l4-common-technical-criteria-both-tracks-web-security"></a>
- **AWS:** EC2, S3, SNS, IAM; least-privilege roles and policies. <a id="item-l4-common-technical-criteria-both-tracks-aws"></a>
- **Advanced CI/CD:** pipelines with lint → test → build → deploy stages, feature flags, coverage gates. <a id="item-l4-common-technical-criteria-both-tracks-advanced-cicd"></a>
- **Package publishing:** Nexus or private npm, semantic versioning, reproducible documentation. <a id="item-l4-common-technical-criteria-both-tracks-package-publishing"></a>
- **Accessibility:** Lighthouse and axe, systematic WCAG 2.1 AA, accessibility-first design, mentoring Juniors. <a id="item-l4-common-technical-criteria-both-tracks-a11y"></a>

### Track-specific criteria

<a id="criteria-l4-track-a-spa-legacy"></a>

#### Track A — SPA Legacy

- **React:** `useRef`, portals with focus management and modals, React Profiler and Chrome Performance tab, component architecture for medium-to-large features. <a id="item-l4-track-a-spa-legacy-react"></a>
- **Angular:** reusable Angular libraries, advanced lazy loading, bundle optimisation, Angular Signals vs Zone.js. <a id="item-l4-track-a-spa-legacy-angular"></a>

<a id="criteria-l4-track-b-astro-aem"></a>

#### Track B — Astro + AEM

- **Astro:** scalable architecture. <a id="item-l4-track-b-astro-aem-astro"></a>
- **AEM:** complex models. <a id="item-l4-track-b-astro-aem-aem"></a>
- **CSS:** evolution of design tokens. <a id="item-l4-track-b-astro-aem-css"></a>
- **Security:** Content Security Policy and RAC audit. <a id="item-l4-track-b-astro-aem-security"></a>
- **DevOps:** blue-green deployments. <a id="item-l4-track-b-astro-aem-devops"></a>
- Visible technical leadership. <a id="item-l4-track-b-astro-aem-visible-technical-leadership"></a>

<a id="criteria-l4-soft-skills"></a>

### Soft skills

| Competency | Observable indicators |
| --- | --- |
| <a id="item-l4-soft-skills-autonomy"></a>**Autonomy** | Delivers 1–2 week features without daily check-ins and makes technical decisions within scope. |
| <a id="item-l4-soft-skills-negotiation"></a>**Negotiation** | Negotiates scope, deadlines, or technical debt with stakeholders using clear arguments and alternatives. |
| <a id="item-l4-soft-skills-conflict-resolution"></a>**Conflict Resolution** | Guides technical disagreements towards documented, agreed decisions. |
| <a id="item-l4-soft-skills-visibility"></a>**Visibility** | Creates visible team or product impact beyond individual tasks. |

<a id="criteria-l4-promotion-gate"></a>

### Promotion gate

**80% Hard Skills · 100% Soft Skills**, interpreted through the general criteria.

## L5: Senior

[Read the L5 product-team interpretation](./l5-senior.md)

<a id="criteria-l5-common-technical-criteria-both-tracks"></a>

### Common technical criteria — both tracks

- **JavaScript/TypeScript:** iterators, generators, practical V8 optimisation, library APIs designed for the team's developer experience. <a id="item-l5-common-technical-criteria-both-tracks-javascripttypescript"></a>
- **Design Systems at scale:** compound components, cross-platform tokens, design system governance. <a id="item-l5-common-technical-criteria-both-tracks-design-systems-at-scale"></a>
- **Security leadership:** threat modelling, OWASP Top 10 in code reviews, TLS certificate management. <a id="item-l5-common-technical-criteria-both-tracks-security-leadership"></a>
- **Advanced Scrum:** critical judgement, facilitating ceremonies, identifying systemic technical debt with remediation plans and return-on-investment considerations. <a id="item-l5-common-technical-criteria-both-tracks-advanced-scrum"></a>
- **Accessibility:** defining and defending project standards, cross-cutting WCAG 2.1 AA, understanding AAA and when to pursue it. <a id="item-l5-common-technical-criteria-both-tracks-a11y"></a>
- **Active mentoring:** a growth plan for at least one Developer, active follow-up, structured knowledge transfer. <a id="item-l5-common-technical-criteria-both-tracks-active-mentoring"></a>

### Track-specific criteria

<a id="criteria-l5-track-a-spa-legacy"></a>

#### Track A — SPA Legacy

- **React:** Profiler for re-renders, scalable design systems, appropriate use of React Server Components. <a id="item-l5-track-a-spa-legacy-react"></a>
- **Angular:** SSR with Angular Universal, AngularJS → Angular migration, module architecture for large teams; legacy AngularJS knowledge including `$scope`, digest cycle, and directives. <a id="item-l5-track-a-spa-legacy-angular"></a>

<a id="criteria-l5-track-b-astro-aem"></a>

#### Track B — Astro + AEM

- AEM at scale. <a id="item-l5-track-b-astro-aem-aem-at-scale"></a>
- Content strategy leadership. <a id="item-l5-track-b-astro-aem-content-strategy-leadership"></a>
- Security leadership. <a id="item-l5-track-b-astro-aem-security-leadership"></a>
- Performance expertise using Real User Monitoring. <a id="item-l5-track-b-astro-aem-performance-expert-rum"></a>
- Vision setting. <a id="item-l5-track-b-astro-aem-vision-setting"></a>
- Organisational influence. <a id="item-l5-track-b-astro-aem-org-influence"></a>

<a id="criteria-l5-soft-skills"></a>

### Soft skills

| Competency | Observable indicators |
| --- | --- |
| <a id="item-l5-soft-skills-responsibility"></a>**Responsibility** | Takes responsibility for technical decisions and end-to-end ownership of the area they lead. |
| <a id="item-l5-soft-skills-coaching"></a>**Coaching** | Develops a growth plan for at least one Developer and follows up actively. |
| <a id="item-l5-soft-skills-security-leadership"></a>**Security Leadership** | Leads security reviews and applies OWASP Top 10 in code reviews. |
| <a id="item-l5-soft-skills-vision-setting"></a>**Vision Setting** | Sets technical direction and influences architecture and product decisions. |
| <a id="item-l5-soft-skills-influence"></a>**Influence** | Creates impact beyond the immediate team and acts as an organisational reference. |

<a id="criteria-l5-promotion-gate"></a>

### Promotion gate

> [!WARNING]
> **Work in Progress**
> Pending final calibration with Technical Leads and the client.

The quick checklist and the detailed criteria support discussion, but they must not be used
to invent a final approval mechanism while this calibration remains unresolved.

## Glossary

| Term | Definition |
| --- | --- |
| Track A | React/Angular SPA, REST APIs, client-side rendering |
| Track B | Astro + AEM Headless, Content Fragments, RAC |
| AEM CF | Adobe Experience Manager Content Fragment: a structured content model |
| RAC | Resource Access Content, described in the source as an API proxy/authentication layer |
| UE | Universal Editor for in-context authoring |
| AuWrapper | Astro component that injects `data-aue-*` attributes for Universal Editor |
| DOM Budget | Maximum DOM nodes stated in the source: L2 200; L3 150; L3 Partial 50 |
| `@layer` | CSS layering for reset, bootstrap, overrides, and project styles |
| Demonstrated | Consistent in daily work, 80%+ of the time |
| In progress | Actively developing the skill |
| Not observed | No evidence of the skill |
| Soft Skills | Behavioural capabilities such as communication, ownership, and leadership |
| Hard Skills | Technical capabilities involving frameworks, tools, and patterns |
| SSR | Server-side rendering in rendering discussions; advanced Semi-Senior in level names |
| CSR | Client-side rendering |
| CWV | Core Web Vitals |
| RUM | Real User Monitoring |
| DX | Developer experience |
| L1–L5 | Career levels from Junior to Senior |

[Return to the Frontend overview](./README.md) ·
[Return to the Academy index](../README.md)
