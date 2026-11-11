# Frontend Developer · L1 Junior

[Academy index](../README.md) · [Frontend overview](./README.md)

## Purpose

Explain the expected contribution of a Junior Frontend Developer, the support needed for safe
delivery, and the evidence product stakeholders can bring to a growth discussion.

## Audience

Product Owner, Product Manager, Delivery Lead, and Technical Lead. Frontend Developer, Coach,
and Mentor validate technical progress against the linked criteria.

## Overview

L1 develops technical foundations and reliable working habits within the assigned Frontend
track. The source covers common skills plus either SPA Legacy or Astro + AEM criteria.

At this level, guidance and review are part of the expected delivery model, not exceptions to
it. The objective is to build reliable application of the basics while making support needs
visible.

## Product-team context

A useful assignment could be a small, clearly defined interface change within an existing
customer journey. The Developer should understand what the user needs, follow established
implementation patterns, and ask for help when requirements or behaviour are unclear. This is
an illustrative assignment rather than a new assessment requirement.

Stakeholders should see punctual participation, clear blocker reporting, and constructive use
of feedback. The Technical Lead and Coach should provide appropriate review capacity and check
the technical basics, including tests and accessibility awareness.

A visually correct screen alone does not demonstrate that the change is reliable or accessible.
Discuss how the implementation behaves across relevant viewport sizes, handles a request, and
supports basic interaction rather than assessing appearance in isolation.

## Evidence stakeholders can discuss

Bring an example of a completed change, the review feedback it received, and how the Developer
responded. Explain whether status updates made it possible to spot a blocker early.

Keep the support provided visible. Guided success can demonstrate L1 growth without being
described as independent feature ownership. The discussion should identify what the person
understood, what they applied, and what still required step-by-step assistance.

## Criterion index

Each link opens the exact description on this page.

| Area | Criterion |
| --- | --- |
| Common | [HTML/CSS](#item-l1-common-technical-criteria-both-tracks-htmlcss-es6) |
| Common | [JavaScript](#item-l1-common-technical-criteria-both-tracks-javascript-es6) |
| Common | [Basic TypeScript](#item-l1-common-technical-criteria-both-tracks-basic-typescript) |
| Common | [Git](#item-l1-common-technical-criteria-both-tracks-git) |
| Common | [jest/vitest](#item-l1-common-technical-criteria-both-tracks-jestvitest) |
| Common | [Tooling](#item-l1-common-technical-criteria-both-tracks-tooling) |
| Common | [Accessibility](#item-l1-common-technical-criteria-both-tracks-a11y) |
| Common | [Cloud](#item-l1-common-technical-criteria-both-tracks-cloud) |
| Track A | [React](#item-l1-track-a-spa-legacy-react) |
| Track A | [Angular](#item-l1-track-a-spa-legacy-angular) |
| Track B | [Vanilla HTML/CSS](#item-l1-track-b-astro-aem-vanilla-htmlcss-without-a-framework) |
| Track B | [Framework-free TypeScript](#item-l1-track-b-astro-aem-typescript-framework-free-frontend) |
| Track B | [Astro](#item-l1-track-b-astro-aem-astro) |
| Track B | [CSS layers](#item-l1-track-b-astro-aem-basic-layer-css-system) |
| Track B | [RAC requests](#item-l1-track-b-astro-aem-fetch-via-rac) |
| Behaviour | [Aptitude](#item-l1-soft-skills-aptitude) |
| Behaviour | [Attitude](#item-l1-soft-skills-attitude) |
| Behaviour | [Reporting](#item-l1-soft-skills-reporting) |
| Behaviour | [Creative](#item-l1-soft-skills-creative) |
| Behaviour | [Team Player](#item-l1-soft-skills-team-player) |

## Detailed criteria

The criteria below reproduce the level-specific expectations in the English source chapter.
The accompanying interpretation explains their relevance to product delivery; it does not add
a separate promotion threshold.

### Common technical criteria — both tracks

<a id="detail-l1-common"></a>

[Source criteria](./Frontend_Career_Path_Chapter.md#criteria-l1-common-technical-criteria-both-tracks)

For a small interface change, reviewers can follow the user-visible markup, styling, API call,
and basic unit test with the Developer. The expectation is to recognise and apply fundamentals
with guidance, not independently design a reusable system.

- **HTML/CSS ES6+:** semantic HTML, Flexbox/Grid, responsive design, media queries. <a id="item-l1-common-technical-criteria-both-tracks-htmlcss-es6"></a>
- **JavaScript ES6+:** types, functions, modules, async/await, fetch + REST APIs. <a id="item-l1-common-technical-criteria-both-tracks-javascript-es6"></a>
- **Basic TypeScript:** interfaces, types, avoiding `any`. <a id="item-l1-common-technical-criteria-both-tracks-basic-typescript"></a>
- **Git:** clone/add/commit/push, Conventional Commits, basic Gitflow. <a id="item-l1-common-technical-criteria-both-tracks-git"></a>
- **jest/vitest:** basic unit tests with simple mocks. <a id="item-l1-common-technical-criteria-both-tracks-jestvitest"></a>
- **Tooling:** `.env`, `tsconfig`, `vite.config`, `.eslintrc`, `localStorage`, CORS. <a id="item-l1-common-technical-criteria-both-tracks-tooling"></a>
- **Accessibility:** semantic HTML, screen readers, basic awareness. <a id="item-l1-common-technical-criteria-both-tracks-a11y"></a>
- **Cloud:** cloud computing fundamentals and conceptual knowledge of AWS services: EC2, S3, IAM, Lambda. <a id="item-l1-common-technical-criteria-both-tracks-cloud"></a>

### Track A — SPA Legacy

<a id="detail-l1-track-a"></a>

[Source criteria](./Frontend_Career_Path_Chapter.md#criteria-l1-track-a-spa-legacy)

When the assignment uses React or Angular, examine how the Developer connects a component or
template to input, state, navigation, and a simple request. Ask them to explain what the
framework is doing and where they need help.

The applicable framework should reflect the project context. Do not treat experience with one
as automatic evidence of the other.

- **React:** functional components, JSX/TSX, props vs state, `useState`, `useEffect`, React Router. <a id="item-l1-track-a-spa-legacy-react"></a>
- **Angular:** CLI, property/event/two-way binding, HttpClient, template-driven forms, basic Observables. <a id="item-l1-track-a-spa-legacy-angular"></a>

### Track B — Astro + AEM

<a id="detail-l1-track-b"></a>

[Source criteria](./Frontend_Career_Path_Chapter.md#criteria-l1-track-b-astro-aem)

For an Astro assignment, look for a basic Page, Section, or Partial and a safe content request
through RAC. The source explicitly describes framework-free frontend foundations; do not assess
React or Angular skills as substitutes.

The discussion should establish whether the Developer understands the responsibility of the
piece being changed and can follow the established content-access and styling conventions.

- Vanilla HTML/CSS without a framework. <a id="item-l1-track-b-astro-aem-vanilla-htmlcss-without-a-framework"></a>
- TypeScript for framework-free frontend. <a id="item-l1-track-b-astro-aem-typescript-framework-free-frontend"></a>
- **Astro:** Page, Section, Partial. <a id="item-l1-track-b-astro-aem-astro"></a>
- Basic `@layer` CSS system. <a id="item-l1-track-b-astro-aem-basic-layer-css-system"></a>
- `fetch()` via RAC. <a id="item-l1-track-b-astro-aem-fetch-via-rac"></a>

### Soft skills

<a id="detail-l1-soft-skills"></a>

[Source criteria](./Frontend_Career_Path_Chapter.md#criteria-l1-soft-skills)

Use a bounded task to observe punctuality, early blocker reporting, openness to feedback, and
a simple alternative when something fails. Record the guidance provided so the discussion
distinguishes supported progress from independent ownership.

| Competency | Observable indicators |
| --- | --- |
| <a id="item-l1-soft-skills-aptitude"></a>**Aptitude** | Learns quickly and retains new concepts. |
| <a id="item-l1-soft-skills-attitude"></a>**Attitude** | Is punctual, meets short deadlines, and asks for help promptly when blocked. |
| <a id="item-l1-soft-skills-reporting"></a>**Reporting** | Communicates clearly in standups without omitting blockers. |
| <a id="item-l1-soft-skills-creative"></a>**Creative** | Suggests simple alternatives to a problem, even without making the final decision. |
| <a id="item-l1-soft-skills-team-player"></a>**Team Player** | Collaborates smoothly and accepts feedback without becoming defensive. |

## Promotion gate

The [L1 source gate](./Frontend_Career_Path_Chapter.md#criteria-l1-promotion-gate) specifies
**80% hard skills and 100% soft skills**.

Read it with the chapter's [general criteria](./Frontend_Career_Path_Chapter.md#promotion-criteria):
soft skills may be demonstrated or in progress, with none unobserved.

Product feedback contributes to the assessment but does not replace technical validation.
A course completion or a single successful demonstration does not establish consistent use
in daily work.

## Navigation

[Source chapter](./Frontend_Career_Path_Chapter.md) ·
[Frontend overview](./README.md) ·
[Next level: L2](./l2-jr-advanced.md)
