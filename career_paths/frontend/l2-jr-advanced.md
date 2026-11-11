# Frontend Developer · L2 Jr Advanced

[Academy index](../README.md) · [Frontend overview](./README.md)

## Purpose

Explain how L2 builds on Frontend foundations and what stakeholders should observe as the
Developer becomes more effective at diagnosing problems and delivering reviewed changes.

## Audience

Product Owner, Product Manager, Delivery Lead, and Technical Lead. Frontend Developer, Coach,
and Mentor validate the linked technical criteria.

## Overview

L2 extends technical foundations with more deliberate debugging, testing, collaboration, and
initiative. The source emphasises goal orientation and problem solving: the Developer should
understand the result the team needs, not simply reproduce an implementation.

## Product-team context

For example, a familiar interface change may require responsive styling, state handling,
end-to-end testing, and resolution of review feedback. The Developer should investigate issues,
explain a proposed option when asking for help, and document enough context for others to review
the change. Guidance remains appropriate when the work exceeds demonstrated experience.

Product stakeholders should notice better awareness of the task's purpose and fewer avoidable
periods of silence when blocked. Technical reviewers should confirm that greater independence is
supported by sound code, tests, and accessibility checks rather than shortcuts that shift
problems to later in delivery.

## Evidence stakeholders can discuss

Useful examples include an investigated defect, a constructive review exchange, and a change
whose user-facing purpose the Developer can explain. A clear PR description or an early warning
about an impediment can show documentary skill and initiative. These are possible evidence
sources, not additional promotion gates.

## Individual criterion index

Each link jumps to the exact criterion text on this page.

| Area | Individual criterion |
| --- | --- |
| Common | [Advanced CSS](#item-l2-common-technical-criteria-both-tracks-advanced-css) |
| Common | [Event Loop](#item-l2-common-technical-criteria-both-tracks-event-loop) |
| Common | [JavaScript](#item-l2-common-technical-criteria-both-tracks-javascript) |
| Common | [Basic Node.js](#item-l2-common-technical-criteria-both-tracks-basic-nodejs) |
| Common | [Cypress](#item-l2-common-technical-criteria-both-tracks-cypress) |
| Common | [Advanced Git](#item-l2-common-technical-criteria-both-tracks-advanced-git) |
| Common | [Basic CI/CD](#item-l2-common-technical-criteria-both-tracks-basic-cicd) |
| Common | [Accessibility](#item-l2-common-technical-criteria-both-tracks-a11y) |
| Track A | [React](#item-l2-track-a-spa-legacy-react) |
| Track A | [Angular](#item-l2-track-a-spa-legacy-angular) |
| Track B | [TypeScript](#item-l2-track-b-astro-aem-typescript) |
| Track B | [Section state management](#item-l2-track-b-astro-aem-5-states-management-section) |
| Track B | [Hooks and Partials](#item-l2-track-b-astro-aem-custom-hooks-reactpartials-prefix-convention) |
| Track B | [AEM models and hydration](#item-l2-track-b-astro-aem-aem-cf-models-hydration) |
| Track B | [Universal Editor](#item-l2-track-b-astro-aem-ue) |
| Track B | [Design tokens](#item-l2-track-b-astro-aem-design-tokens-vs-hardcode) |
| Track B | [DOM budget](#item-l2-track-b-astro-aem-dom-budget-awareness) |
| Soft skills | [Goal Oriented](#item-l2-soft-skills-goal-oriented) |
| Soft skills | [Problem Solving](#item-l2-soft-skills-problem-solving) |
| Soft skills | [Analytical](#item-l2-soft-skills-analytical) |
| Soft skills | [Documentary](#item-l2-soft-skills-documentary) |
| Soft skills | [Initiative](#item-l2-soft-skills-initiative) |

## Detailed criteria

The criteria below are reproduced from the English career-path chapter and grouped
by area. They describe technical expectations; the product interpretation explains
why they matter to delivery and does not add a separate promotion threshold.

### Common technical criteria (both tracks)

<a id="detail-l2-common"></a>

[Source criteria](./Frontend_Career_Path_Chapter.md#criteria-l2-common-technical-criteria-both-tracks)

On a routine feature, look for reasoned CSS choices, browser debugging, robust error handling, a
basic end-to-end check, and the ability to diagnose a failing pipeline. Discuss how these checks
protect the user journey and how the Developer narrows a problem before escalating.

- **Advanced CSS:** appropriate use of Sass or Tailwind, atomic design, basic SEO. <a id="item-l2-common-technical-criteria-both-tracks-advanced-css"></a>
- **Event Loop:** debugging in DevTools (breakpoints, call stack, watchers). <a id="item-l2-common-technical-criteria-both-tracks-event-loop"></a>
- **JavaScript:** rest/spread, destructuring, robust error handling. <a id="item-l2-common-technical-criteria-both-tracks-javascript"></a>
- **Basic Node.js:** scripts using `fs`/`dotenv`, project npm scripts. <a id="item-l2-common-technical-criteria-both-tracks-basic-nodejs"></a>
- **Cypress:** basic E2E tests, conceptual understanding of TDD. <a id="item-l2-common-technical-criteria-both-tracks-cypress"></a>
- **Advanced Git:** conflict resolution, constructive code reviews, strategic branching. <a id="item-l2-common-technical-criteria-both-tracks-advanced-git"></a>
- **Basic CI/CD:** reading and debugging GitHub Actions failures. <a id="item-l2-common-technical-criteria-both-tracks-basic-cicd"></a>
- **A11y:** basic ARIA attributes, WCAG AA contrast, keyboard navigation, axe DevTools. <a id="item-l2-common-technical-criteria-both-tracks-a11y"></a>

### Track-specific criteria

#### Track A (SPA Legacy)

<a id="detail-l2-track-a"></a>

[Source criteria](./Frontend_Career_Path_Chapter.md#criteria-l2-track-a-spa-legacy)

For React work, discuss reuse through hooks or composition, avoidable re-renders, and
testing-library evidence. For Angular, look at dependency injection, reactive forms, and
lifecycle-safe RxJS use. The person applies established patterns with review rather than
redesigns the application.

- **React:** HOC, custom hooks, `useCallback`, `useContext`, `useReducer`, React Testing Library, problematic re-renders. <a id="item-l2-track-a-spa-legacy-react"></a>
- **Angular:** lazy-loaded modules, dependency injection, reactive forms, RxJS (`map`, `filter`, `switchMap`, `takeUntil`), TestBed. <a id="item-l2-track-a-spa-legacy-angular"></a>

#### Track B (Astro + AEM)

<a id="detail-l2-track-b"></a>

[Source criteria](./Frontend_Career_Path_Chapter.md#criteria-l2-track-b-astro-aem)

Review how TypeScript types, AEM content models, hydration, Universal Editor configuration, and
design tokens are used in the assigned slice. Ask what enters the DOM and why; confirm
implementation detail with a Track B reviewer.

- **TypeScript:** unions, generics. <a id="item-l2-track-b-astro-aem-typescript"></a>
- 5 states management (Section). <a id="item-l2-track-b-astro-aem-5-states-management-section"></a>
- Custom hooks (React)/Partials (`_prefix` convention). <a id="item-l2-track-b-astro-aem-custom-hooks-reactpartials-prefix-convention"></a>
- AEM CF models, hydration. <a id="item-l2-track-b-astro-aem-aem-cf-models-hydration"></a>
- **UE:** `rendererJs`, `component-def`. <a id="item-l2-track-b-astro-aem-ue"></a>
- Design tokens vs hardcode. <a id="item-l2-track-b-astro-aem-design-tokens-vs-hardcode"></a>
- DOM budget awareness. <a id="item-l2-track-b-astro-aem-dom-budget-awareness"></a>

### Soft skills

<a id="detail-l2-soft-skills"></a>

[Source criteria](./Frontend_Career_Path_Chapter.md#criteria-l2-soft-skills)

Look for an explanation of the task outcome, a manageable investigation before escalation,
readable PR context, and early action when blocked. Product partners can contribute examples of
task understanding; code review validates technical analysis.

| Competency | Observable indicators |
| --- | --- |
| <a id="item-l2-soft-skills-goal-oriented"></a>**Goal Oriented** | Understands each task's purpose and adapts execution to achieve the outcome. |
| <a id="item-l2-soft-skills-problem-solving"></a>**Problem Solving** | Investigates before escalating and suggests at least one solution when asking for help. |
| <a id="item-l2-soft-skills-analytical"></a>**Analytical** | Breaks complex problems into manageable parts and reviews others' code with sound judgement. |
| <a id="item-l2-soft-skills-documentary"></a>**Documentary** | Provides README files, relevant comments, and clear PR descriptions. |
| <a id="item-l2-soft-skills-initiative"></a>**Initiative** | Takes action to avoid remaining blocked and anticipates impediments. |

## Promotion gate

The [L2 promotion gate](./Frontend_Career_Path_Chapter.md#criteria-l2-promotion-gate) specifies
80% hard skills and 100% soft skills, interpreted through the chapter's general criteria. Review
sustained examples with the Technical Lead and Coach; completing a training course alone does
not demonstrate consistent use in product work.

## Source and navigation

[Frontend source chapter](./Frontend_Career_Path_Chapter.md)

[Previous level: L1](./l1-junior.md) · [Frontend overview](./README.md) ·
[Next level: L3](./l3-semi-senior.md)
