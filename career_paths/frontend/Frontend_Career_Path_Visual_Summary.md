# Frontend Developer · Career Path Visual Summary

**Globant Academy · Iberia · v2.0 · November 2026**  
**Coexisting tracks:** A (SPA Legacy) and B (Astro + AEM)

This document presents in searchable Markdown the information shown in the Frontend career path
visual summary. It is intended for product stakeholders and complements the
[technical career path chapter](./Frontend_Career_Path_Chapter.md), which remains the detailed
reference for the criteria.

The summaries below reproduce the source expectations. Contextual explanations are intended to
help product teams discuss them; they do not add new assessment or promotion requirements.

## Purpose

This career path establishes a shared reference for the professional growth of Frontend
Developers in Globant Academy Iberia. It aligns expectations among Technical Leads, Product
Owners, Coaches, Managers, and Developers, and provides criteria to support promotion decisions.

A criterion is considered consolidated when the Developer demonstrates it consistently in daily
work, rather than only occasionally or in isolated conversations.

## Audience and use

The primary audience is the Product Owner, Product Manager, Delivery Lead, and Technical Lead
working with Academy Frontend Developers. Coaches and technical reviewers validate the technical
evidence; product stakeholders contribute observations about delivery, collaboration, and
customer outcomes.

Use the person's actual project context and assigned technical track when discussing evidence.
The two tracks describe different technology environments; strength in one does not automatically
demonstrate proficiency in the other.

The [detailed career path chapter](./Frontend_Career_Path_Chapter.md) contains the source criteria
with direct links to each level and competency. The level pages provide additional product-team
context:

- [L1 · Junior](./l1-junior.md)
- [L2 · Jr Advanced](./l2-jr-advanced.md)
- [L3 · Semi-Senior](./l3-semi-senior.md)
- [L4 · SSR Advanced](./l4-ssr-advanced.md)
- [L5 · Senior](./l5-senior.md)

## Technical tracks (v2)

The source defines two tracks that coexist across client projects.

| Area | Track A — SPA Legacy | Track B — Astro + AEM Headless |
| --- | --- | --- |
| Projects | BKI, MMB, CKI, Ancillanes | Iberia Digital Platform, marketing sites |
| Rendering | CSR | SSR |
| Backend | REST APIs | RAC (proxy) |
| CMS | WCS/Drupal | AEM CF |
| Stack | React, Angular, AngularJS | Not specified as a framework stack |
| Editor | Not applicable | Universal Editor |

The acronyms and track terminology are defined in the
[chapter glossary](./Frontend_Career_Path_Chapter.md#glossary).

## Track transition: A to B

When a Track A Developer starts work on an Astro + AEM project, the source describes a transition
period at **L2.5 (intermediate)** for **6–12 months**.

The Developer moves to **Track B Full** when both conditions are met:

- Maintains **80% or more of Track A criteria**, including strong React/Angular skills.
- Demonstrates **60% or more of Track B criteria** while ramping up in Astro.

Soft skills, such as communication and problem-solving, carry over. They do **not** accelerate
the transition: Track B hard skills must be validated independently.

These percentages and the transition period are specific to the source's Track A-to-B migration
guidance. They should not be generalised into new rules for other track changes or promotion
decisions.

## Promotion criteria

### General criteria

The source describes the following general assessment criteria:

- **80% Hard Skills:** demonstrated in daily work (80% or more of the time).
- **100% Soft Skills:** demonstrated or in progress, with none marked "Not observed".
- **Evaluation:** Coach (technical), Technical Lead (behaviour), Mentor (career), and Architect
  for L4 and above.

The source describes a criterion as consolidated when it is demonstrated consistently in daily
work. Reviewers should consider actual opportunities to demonstrate the skill and the level of
support provided.

### Quick readiness checklist

| Transition | Criteria highlighted in the source |
| --- | --- |
| L1 → L2 | Advanced CSS; Event Loop; custom hooks/DI; E2E tests; code reviews; goal orientation |
| L2 → L3 | Advanced TypeScript; SOLID; state management; A11y audits; architecture proposals; communication |
| L3 → L4 | Security expertise; performance optimisation; active mentoring; visible leadership |
| L4 → L5 | Technical vision; mastery in 2+ areas; mentoring 2+ seniors; business acumen; organisational influence; CTO approval |

The checklist is a summary, not a replacement for the detailed criteria. The L5 checklist refers
to mentoring two or more seniors, while the detailed L5 criteria specify a growth plan for at
least one Developer. The final L5 gate is marked as work in progress, pending calibration with
Technical Leads and the client. This difference should be resolved through calibration rather
than treated as an additional approved requirement.

## L1 · Junior

### Common technical criteria — both tracks

- **HTML/CSS ES6+:** semantic HTML, Flexbox/Grid, responsive design, and media queries.
- **JavaScript ES6+:** types, functions, modules, async/await, fetch, and REST APIs.
- **Basic TypeScript:** interfaces and types; avoid `any`.
- **Git:** clone, add, commit, and push; Conventional Commits; basic Gitflow.
- **jest/vitest:** basic unit tests with simple mocks.
- **Tooling:** `.env`, `tsconfig`, `vite.config`, `.eslintrc`, `localStorage`, and CORS.
- **Accessibility (A11y):** semantic HTML, screen readers, and basic awareness.
- **Cloud:** cloud computing fundamentals and conceptual knowledge of AWS services such as EC2,
  S3, IAM, and Lambda.

### Track A — SPA Legacy

- **React:** functional components, JSX/TSX, props versus state, `useState`, `useEffect`, and
  React Router.
- **Angular:** CLI, property/event/two-way binding, HttpClient, template-driven forms, and basic
  Observables.

### Track B — Astro + AEM

- Vanilla HTML/CSS without a framework.
- TypeScript for framework-free frontend development.
- **Astro:** Page, Section, and Partial.
- Basic `@layer` CSS system.
- `fetch()` via RAC.

### Soft skills

| Competency | Observable indicators |
| --- | --- |
| Aptitude | Learns quickly and retains new concepts. |
| Attitude | Is punctual, meets short deadlines, and asks for help promptly when blocked. |
| Reporting | Communicates clearly in stand-ups without omitting blockers. |
| Creative | Suggests simple alternatives to a problem, even without making the final decision. |
| Team Player | Collaborates smoothly and accepts feedback without becoming defensive. |

**Promotion gate:** 80% Hard Skills · 100% Soft Skills.

## L2 · Jr Advanced

### Common technical criteria — both tracks

- **Advanced CSS:** appropriate use of Sass or Tailwind, atomic design, and basic SEO.
- **Event Loop:** debugging in DevTools using breakpoints, call stack, and watchers.
- **JavaScript:** rest/spread, destructuring, and robust error handling.
- **Basic Node.js:** scripts using `fs` and `dotenv`, plus project npm scripts.
- **Cypress:** basic E2E tests and conceptual understanding of TDD.
- **Advanced Git:** conflict resolution, constructive code reviews, and strategic branching.
- **Basic CI/CD:** reading and debugging GitHub Actions failures.
- **Accessibility (A11y):** basic ARIA attributes, WCAG AA contrast, keyboard navigation, and
  axe DevTools.

### Track A — SPA Legacy

- **React:** HOC, custom hooks, `useCallback`, `useContext`, `useReducer`, React Testing Library,
  and problematic re-renders.
- **Angular:** lazy-loaded modules, dependency injection, reactive forms, RxJS (`map`, `filter`,
  `switchMap`, `takeUntil`), and TestBed.

### Track B — Astro + AEM

- **TypeScript:** unions and generics.
- Five states management (Section).
- Custom hooks (React) / Partials using the `_prefix` convention.
- AEM Content Fragment (CF) models and hydration.
- **Universal Editor (UE):** `rendererJs` and `component-def`.
- Design tokens instead of hardcoded values.
- DOM budget awareness.

### Soft skills

| Competency | Observable indicators |
| --- | --- |
| Goal Oriented | Understands each task's purpose and adapts execution to achieve the outcome. |
| Problem Solving | Investigates before escalating and suggests at least one solution when asking for help. |
| Analytical | Breaks complex problems into manageable parts and reviews others' code with sound judgement. |
| Documentary | Provides README files, relevant comments, and clear PR descriptions. |
| Initiative | Takes action to avoid remaining blocked and anticipates impediments. |

**Promotion gate:** 80% Hard Skills · 100% Soft Skills.

## L3 · Semi-Senior

### Common technical criteria — both tracks

- **Advanced JavaScript:** `this`, `call`/`apply`/`bind`, IIFE, prototypal inheritance, closures,
  event loop, and call stack.
- **Advanced TypeScript:** abstract classes, union/intersection types, `keyof`, type aliases,
  and `unknown`.
- **SOLID principles:** encapsulation, abstraction, and three or more design patterns, such as
  Singleton, Observer, and Strategy.
- **GraphQL:** API design and consumption.
- **Basic NestJS/Express:** server, database connections (MongoDB/PostgreSQL), and JWT
  authentication.
- **Intermediate CI/CD:** ESLint/Prettier/SonarQube, CD to staging, and automated tests.
- **OpenAPI/Swagger:** navigable technical documentation.
- **Accessibility (A11y):** axe audits, WCAG 2.1 level A, and focus management in modals/forms.

### Track A — SPA Legacy

- **React:** Redux/Zustand, Suspense, Error Boundaries, React Query, appropriate use of
  `useMemo`/`useCallback`, and Storybook.
- **Angular:** advanced routing (outlets, guards, lazy loading), custom pipes/directives, OnPush
  change detection, NgRx/NGXS, i18n, and legacy-app assessment.

### Track B — Astro + AEM

- **Astro:** streaming and Core Web Vitals optimisation.
- **AEM:** nested Content Fragments and references.
- **Universal Editor:** complex editors.
- **CSS:** layer strategy (L0–L3).
- Performance tuning using RUM.
- **Testing:** parameterisation.
- **Accessibility:** audits and keyboard navigation.

### Soft skills

| Competency | Observable indicators |
| --- | --- |
| Communication | Explains technical decisions clearly to Technical Leads and less experienced Developers. |
| Pressure Tolerance | Maintains quality and communication during critical sprints or scope changes. |
| Flexibility | Adapts solutions when requirements change without prolonged blockers. |
| Sense of Urgency | Prioritises correctly, identifies blockers, and addresses them first. |
| Ownership | Owns tasks from start to finish without requiring the lead to chase status updates. |

**Promotion gate:** 80% Hard Skills · 100% Soft Skills.

## L4 · SSR Advanced

### Common technical criteria — both tracks

- **Expert TypeScript:** production generics (utility types, basic conditional types), modules,
  and libraries with clean public APIs.
- **Event loop, closures, and memory management:** explanation and practical debugging.
- **OAuth 2.0 / OIDC:** implementation in a production application.
- **Web security:** XSS, CSRF, CORS misconfiguration, and TLS certificates in deployment.
- **AWS:** EC2, S3, SNS, and IAM; least-privilege roles and policies.
- **Advanced CI/CD:** pipelines with lint → test → build → deploy stages, feature flags, and
  coverage gates.
- **Package publishing:** Nexus or private npm, semver, and reproducible documentation.
- **Accessibility (A11y):** Lighthouse + axe, systematic WCAG 2.1 AA, accessibility-first
  design, and mentoring Juniors.

### Track A — SPA Legacy

- **React:** `useRef`, portals (focus management, modals), React Profiler + Chrome Performance
  tab, and component architecture for medium-to-large features.
- **Angular:** reusable Angular libraries, advanced lazy loading, bundle optimisation, and
  Angular Signals versus Zone.js.

### Track B — Astro + AEM

- **Astro:** scalable architecture.
- **AEM:** complex models.
- **CSS:** token evolution.
- **Security:** CSP and RAC audit.
- **DevOps:** blue-green deployments.
- Visible technical leadership.

### Soft skills

| Competency | Observable indicators |
| --- | --- |
| Autonomy | Delivers 1–2 week features without daily check-ins and makes technical decisions within scope. |
| Negotiation | Negotiates scope, deadlines, or technical debt with stakeholders using clear arguments and alternatives. |
| Conflict Resolution | Guides technical disagreements towards documented, agreed decisions. |
| Visibility | Creates visible team or product impact beyond individual tasks. |

**Promotion gate:** 80% Hard Skills · 100% Soft Skills.

## L5 · Senior

### Common technical criteria — both tracks

- **JavaScript/TypeScript:** iterators, generators, practical V8 optimisation, and library APIs
  designed for the team's Developer Experience (DX).
- **Design Systems at scale:** compound components, cross-platform tokens, and design-system
  governance.
- **Security leadership:** threat modelling, OWASP Top 10 in code reviews, and TLS certificate
  management.
- **Advanced Scrum:** critical judgement, facilitating ceremonies, identifying systemic
  technical debt, and creating remediation plans with ROI.
- **Accessibility (A11y):** defining and defending project standards, cross-cutting WCAG 2.1 AA,
  understanding AAA, and knowing when to pursue it.
- **Active mentoring:** a growth plan for at least one Developer, active follow-up, and
  structured knowledge transfer.

### Track A — SPA Legacy

- **React:** Profiler for re-renders, scalable design systems, and appropriate use of React
  Server Components.
- **Angular:** SSR with Angular Universal, AngularJS → Angular migration, module architecture
  for large teams, and legacy AngularJS knowledge (`$scope`, digest cycle, directives).

### Track B — Astro + AEM

- AEM at scale.
- Content strategy leadership.
- Security leadership.
- Performance expertise using RUM.
- Vision setting.
- Organisational influence.

### Soft skills

| Competency | Observable indicators |
| --- | --- |
| Responsibility | Takes responsibility for technical decisions and end-to-end ownership of the area they lead. |
| Coaching | Develops a growth plan for at least one Developer and follows up actively. |
| Security Leadership | Leads security reviews and applies OWASP Top 10 in code reviews. |
| Vision Setting | Sets technical direction and influences architecture and product decisions. |
| Influence | Creates impact beyond the immediate team and acts as an organisational reference. |

**Promotion gate:** Work in progress — pending final calibration with Technical Leads and the
client.

## Interpreting the criteria in product teams

The level summaries are intended to help stakeholders connect Frontend work to delivery and
customer outcomes:

- At **L1**, discuss how clear requirements, useful feedback, and accessible foundations support
  small, guided changes.
- At **L2**, discuss whether the Developer understands the task outcome, investigates blockers,
  and provides reviewable changes.
- At **L3**, discuss ownership of a feature, quality trade-offs, communication during change,
  and evidence behind technical decisions.
- At **L4**, discuss autonomy within scope, negotiation of delivery trade-offs, and visible
  technical influence.
- At **L5**, discuss technical direction, mentoring, security and accessibility standards, and
  influence beyond one team.

These are discussion prompts, not additional promotion gates. Technical reviewers must validate
the detailed criteria in the
[career path chapter](./Frontend_Career_Path_Chapter.md).

## Glossary

| Term | Definition |
| --- | --- |
| Track A | React/Angular SPA, REST APIs, CSR; BKI, MMB, CKI, and Ancillanes projects. |
| Track B | Astro + AEM Headless, Content Fragments (AEM data model), and RAC. |
| RAC | Resource Access Content, described in the source as an API proxy/auth layer. |
| UE | Universal Editor; in-context authoring. |
| AuWrapper | Astro component that injects `data-aue-*` for Universal Editor. |
| DOM Budget | Maximum DOM nodes stated by the source: L2: 200; L3: 150; L3 Partial: 50. |
| `@layer` | CSS layering (reset, bootstrap, overrides, project). |
| Demonstrated | Consistent in daily work (80%+ of the time). |
| In progress | Actively developing the skill. |
| Not observed | No evidence of the skill. |
| Soft Skills | Behavioural capabilities, including communication, ownership, and leadership. |
| Hard Skills | Technical capabilities involving frameworks, tools, and patterns. |
| SSR | Server-Side Rendering in rendering discussions; SSR Advanced in the level name. |
| CSR | Client-Side Rendering (React/Angular). |
| L1–L5 | Career levels from Junior to Senior. |

[Return to the Frontend overview](./README.md) · [Academy index](../README.md)
