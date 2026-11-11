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

Greater effectiveness does not mean that all work is now independent. Guidance remains
appropriate when the assignment exceeds demonstrated experience, introduces unfamiliar
technical constraints, or involves decisions outside the person's scope.

## Product-team context

For example, a familiar interface change may require responsive styling, state handling,
end-to-end testing, and resolution of review feedback. The Developer should investigate issues,
explain a proposed option when asking for help, and document enough context for others to review
the change.

Product stakeholders should notice better awareness of the task's purpose and fewer avoidable
periods of silence when blocked. An escalation should give the team enough information to act:
what was expected, what happened, what has been investigated, and where support is needed.

Technical reviewers should confirm that greater independence is supported by sound code,
tests, and accessibility checks rather than shortcuts that shift problems to later delivery.

## Evidence stakeholders can discuss

Useful examples include an investigated defect, a constructive review exchange, and a change
whose user-facing purpose the Developer can explain.

A clear PR description or an early warning about an impediment can show documentary skill
and initiative. These are possible evidence sources, not additional promotion gates.

When reviewing progress, distinguish between repeating an established recipe and understanding
why it is appropriate. The Developer should increasingly be able to connect implementation
choices with the intended outcome and explain when the usual approach does not fit.

## Criterion index

Each link opens the exact description on this page.

| Area | Criterion |
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
| Track B | [AEM content models and hydration](#item-l2-track-b-astro-aem-aem-cf-models-hydration) |
| Track B | [Universal Editor](#item-l2-track-b-astro-aem-ue) |
| Track B | [Design tokens](#item-l2-track-b-astro-aem-design-tokens-vs-hardcode) |
| Track B | [DOM budget](#item-l2-track-b-astro-aem-dom-budget-awareness) |
| Behaviour | [Goal Oriented](#item-l2-soft-skills-goal-oriented) |
| Behaviour | [Problem Solving](#item-l2-soft-skills-problem-solving) |
| Behaviour | [Analytical](#item-l2-soft-skills-analytical) |
| Behaviour | [Documentary](#item-l2-soft-skills-documentary) |
| Behaviour | [Initiative](#item-l2-soft-skills-initiative) |

## Detailed criteria

The criteria below reproduce the level-specific expectations in the English source chapter.
The accompanying interpretation explains their relevance to product delivery; it does not add
a separate promotion threshold.

### Common technical criteria — both tracks

<a id="detail-l2-common"></a>

[Source criteria](./Frontend_Career_Path_Chapter.md#criteria-l2-common-technical-criteria-both-tracks)

On a routine feature, look for reasoned CSS choices, browser debugging, robust error handling,
a basic end-to-end check, and the ability to diagnose a failing pipeline.

Discuss how these checks protect the user journey and how the Developer narrows a problem
before escalating. The value is not simply knowing the tool names; it is using them to provide
a more reliable change and a clearer account of any remaining uncertainty.

- **Advanced CSS:** appropriate use of Sass or Tailwind, atomic design, basic SEO. <a id="item-l2-common-technical-criteria-both-tracks-advanced-css"></a>
- **Event Loop:** debugging in DevTools: breakpoints, call stack, watchers. <a id="item-l2-common-technical-criteria-both-tracks-event-loop"></a>
- **JavaScript:** rest/spread, destructuring, robust error handling. <a id="item-l2-common-technical-criteria-both-tracks-javascript"></a>
- **Basic Node.js:** scripts using `fs`/`dotenv`, project npm scripts. <a id="item-l2-common-technical-criteria-both-tracks-basic-nodejs"></a>
- **Cypress:** basic E2E tests, conceptual understanding of TDD. <a id="item-l2-common-technical-criteria-both-tracks-cypress"></a>
- **Advanced Git:** conflict resolution, constructive code reviews, strategic branching. <a id="item-l2-common-technical-criteria-both-tracks-advanced-git"></a>
- **Basic CI/CD:** reading and debugging GitHub Actions failures. <a id="item-l2-common-technical-criteria-both-tracks-basic-cicd"></a>
- **Accessibility:** basic ARIA attributes, WCAG AA contrast, keyboard navigation, axe DevTools. <a id="item-l2-common-technical-criteria-both-tracks-a11y"></a>

### Track A — SPA Legacy

<a id="detail-l2-track-a"></a>

[Source criteria](./Frontend_Career_Path_Chapter.md#criteria-l2-track-a-spa-legacy)

For React work, discuss reuse through hooks or composition, avoidable re-renders, and
testing-library evidence. For Angular, look at dependency injection, reactive forms, and
lifecycle-safe RxJS use.

The person applies established patterns with review rather than redesigning the application.
Technical reviewers should assess whether the chosen pattern fits the actual behaviour being
implemented.

- **React:** HOC, custom hooks, `useCallback`, `useContext`, `useReducer`, React Testing Library, problematic re-renders. <a id="item-l2-track-a-spa-legacy-react"></a>
- **Angular:** lazy-loaded modules, dependency injection, reactive forms, RxJS: `map`, `filter`, `switchMap`, `takeUntil`; TestBed. <a id="item-l2-track-a-spa-legacy-angular"></a>

### Track B — Astro + AEM

<a id="detail-l2-track-b"></a>

[Source criteria](./Frontend_Career_Path_Chapter.md#criteria-l2-track-b-astro-aem)

Review how TypeScript types, AEM content models, hydration, Universal Editor configuration,
and design tokens are used in the assigned slice.

Ask what enters the DOM and why. Confirm implementation details with a Track B reviewer.
Project-specific terms such as the five Section states should be interpreted using the
applicable implementation guidance rather than assigned an invented definition.

- **TypeScript:** unions, generics. <a id="item-l2-track-b-astro-aem-typescript"></a>
- Five-state management for Sections. <a id="item-l2-track-b-astro-aem-5-states-management-section"></a>
- Custom hooks in React / Partials using the `_prefix` convention. <a id="item-l2-track-b-astro-aem-custom-hooks-reactpartials-prefix-convention"></a>
- AEM Content Fragment models and hydration. <a id="item-l2-track-b-astro-aem-aem-cf-models-hydration"></a>
- **Universal Editor:** `rendererJs`, `component-def`. <a id="item-l2-track-b-astro-aem-ue"></a>
- Design tokens vs hardcoded values. <a id="item-l2-track-b-astro-aem-design-tokens-vs-hardcode"></a>
- DOM budget awareness. <a id="item-l2-track-b-astro-aem-dom-budget-awareness"></a>

### Soft skills

<a id="detail-l2-soft-skills"></a>

[Source criteria](./Frontend_Career_Path_Chapter.md#criteria-l2-soft-skills)

Look for an explanation of the task outcome, a manageable investigation before escalation,
readable PR context, and early action when blocked.

Product partners can contribute examples of task understanding and collaboration. Technical
review validates the quality of the investigation and the proposed solution.

| Competency | Observable indicators |
| --- | --- |
| <a id="item-l2-soft-skills-goal-oriented"></a>**Goal Oriented** | Understands each task's purpose and adapts execution to achieve the outcome. |
| <a id="item-l2-soft-skills-problem-solving"></a>**Problem Solving** | Investigates before escalating and suggests at least one solution when asking for help. |
| <a id="item-l2-soft-skills-analytical"></a>**Analytical** | Breaks complex problems into manageable parts and reviews others' code with sound judgement. |
| <a id="item-l2-soft-skills-documentary"></a>**Documentary** | Provides README files, relevant comments, and clear PR descriptions. |
| <a id="item-l2-soft-skills-initiative"></a>**Initiative** | Takes action to avoid remaining blocked and anticipates impediments. |

## Promotion gate

The [L2 source gate](./Frontend_Career_Path_Chapter.md#criteria-l2-promotion-gate) specifies
**80% hard skills and 100% soft skills**, interpreted through the chapter's
[general criteria](./Frontend_Career_Path_Chapter.md#promotion-criteria).

Review sustained examples with the Technical Lead and Coach. Completing a training course
alone does not demonstrate consistent use in product work.

## Navigation

[Source chapter](./Frontend_Career_Path_Chapter.md) ·
[Previous level: L1](./l1-junior.md) ·
[Next level: L3](./l3-semi-senior.md)
