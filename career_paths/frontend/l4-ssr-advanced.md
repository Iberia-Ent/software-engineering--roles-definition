# Frontend Developer · L4 SSR Advanced

[Academy index](../README.md) · [Frontend overview](./README.md)

## Purpose

Explain L4 technical specialisation and visible leadership so product stakeholders can assess
its effect on delivery, collaboration, and risk management.

## Audience

Product Owner, Product Manager, Delivery Lead, and Technical Lead. Frontend Developer, Coach,
Mentor, and Architect participate in technical calibration as described by the source.

## Overview

L4 combines technical depth with autonomy, negotiation, conflict resolution, and visible impact.
The source describes delivery of 1–2 week features without daily check-ins and technical
decisions within scope. That describes an autonomy expectation, not a universal estimate for
every feature.

In this level label, SSR means the advanced Semi-Senior stage, not server-side rendering.

## Product-team context

For example, the Developer may guide a feature whose performance, security, and accessibility
requirements compete with a delivery deadline. Stakeholders should hear an understandable
account of alternatives, risks, and the consequences of deferring work. Disagreement should lead
towards documented decisions rather than unresolved technical friction.

Technical leadership should be apparent in the team's work: more reliable patterns, useful
review guidance, and better-informed delivery decisions. It should not depend solely on being
the person who resolves the most urgent issues.

## Evidence stakeholders can discuss

Review a negotiation about scope or debt, a technical disagreement brought to a clear decision,
and a contribution with visible impact beyond the individual's assigned task. Technical evidence
should support those observations through security, pipeline, package, accessibility, or
architecture work relevant to the actual project.

## Individual criterion index

Each link jumps to the exact criterion text on this page.

| Area | Individual criterion |
| --- | --- |
| Common | [Expert TypeScript](#item-l4-common-technical-criteria-both-tracks-expert-typescript) |
| Common | [Runtime and memory management](#item-l4-common-technical-criteria-both-tracks-event-loop-closures-and-memory-management) |
| Common | [OAuth 2.0 / OIDC](#item-l4-common-technical-criteria-both-tracks-oauth-20-oidc) |
| Common | [Web security](#item-l4-common-technical-criteria-both-tracks-web-security) |
| Common | [AWS](#item-l4-common-technical-criteria-both-tracks-aws) |
| Common | [Advanced CI/CD](#item-l4-common-technical-criteria-both-tracks-advanced-cicd) |
| Common | [Package publishing](#item-l4-common-technical-criteria-both-tracks-package-publishing) |
| Common | [Accessibility](#item-l4-common-technical-criteria-both-tracks-a11y) |
| Track A | [React](#item-l4-track-a-spa-legacy-react) |
| Track A | [Angular](#item-l4-track-a-spa-legacy-angular) |
| Track B | [Astro](#item-l4-track-b-astro-aem-astro) |
| Track B | [AEM](#item-l4-track-b-astro-aem-aem) |
| Track B | [CSS tokens](#item-l4-track-b-astro-aem-css) |
| Track B | [Security](#item-l4-track-b-astro-aem-security) |
| Track B | [DevOps](#item-l4-track-b-astro-aem-devops) |
| Track B | [Technical leadership](#item-l4-track-b-astro-aem-visible-technical-leadership) |
| Soft skills | [Autonomy](#item-l4-soft-skills-autonomy) |
| Soft skills | [Negotiation](#item-l4-soft-skills-negotiation) |
| Soft skills | [Conflict Resolution](#item-l4-soft-skills-conflict-resolution) |
| Soft skills | [Visibility](#item-l4-soft-skills-visibility) |

## Detailed criteria

The criteria below are reproduced from the English career-path chapter and grouped
by area. They describe technical expectations; the product interpretation explains
why they matter to delivery and does not add a separate promotion threshold.

### Common technical criteria (both tracks)

<a id="detail-l4-common"></a>

[Source criteria](./Frontend_Career_Path_Chapter.md#criteria-l4-common-technical-criteria-both-tracks)

Assess production evidence: public TypeScript APIs, practical memory or event-loop debugging,
OAuth/OIDC integration, least-privilege AWS use, gated delivery pipelines, package lifecycle,
and systematic WCAG 2.1 AA work. Discuss how these controls affect releases and user risk.

- **Expert TypeScript:** production generics (utility types, basic conditional types), modules and libraries with clean public APIs. <a id="item-l4-common-technical-criteria-both-tracks-expert-typescript"></a>
- **Event loop, closures and memory management:** explanation and practical debugging. <a id="item-l4-common-technical-criteria-both-tracks-event-loop-closures-and-memory-management"></a>
- **OAuth 2.0 / OIDC:** implementation in a production application. <a id="item-l4-common-technical-criteria-both-tracks-oauth-20-oidc"></a>
- **Web security:** XSS, CSRF, CORS misconfiguration, TLS certificates in deployment. <a id="item-l4-common-technical-criteria-both-tracks-web-security"></a>
- **AWS:** EC2, S3, SNS, IAM; least-privilege roles and policies. <a id="item-l4-common-technical-criteria-both-tracks-aws"></a>
- **Advanced CI/CD:** pipelines with lint → test → build → deploy stages, feature flags, coverage gates. <a id="item-l4-common-technical-criteria-both-tracks-advanced-cicd"></a>
- **Package publishing:** Nexus or private npm, semver, reproducible documentation. <a id="item-l4-common-technical-criteria-both-tracks-package-publishing"></a>
- **A11y:** Lighthouse + axe, systematic WCAG 2.1 AA, accessibility-first design, mentoring Juniors. <a id="item-l4-common-technical-criteria-both-tracks-a11y"></a>

### Track-specific criteria

#### Track A (SPA Legacy)

<a id="detail-l4-track-a"></a>

[Source criteria](./Frontend_Career_Path_Chapter.md#criteria-l4-track-a-spa-legacy)

For the assigned framework, examine a medium-to-large feature's architecture, bundle or
rendering implications, and focus management. The expectation includes profiling real behaviour
and selecting React or Angular capabilities deliberately, not applying every advanced API.

- **React:** `useRef`, portals (focus management, modals), React Profiler + Chrome Perf tab, component architecture for medium-to-large features. <a id="item-l4-track-a-spa-legacy-react"></a>
- **Angular:** reusable Angular libraries, advanced lazy loading, bundle optimisation, Angular Signals vs Zone.js. <a id="item-l4-track-a-spa-legacy-angular"></a>

#### Track B (Astro + AEM)

<a id="detail-l4-track-b"></a>

[Source criteria](./Frontend_Career_Path_Chapter.md#criteria-l4-track-b-astro-aem)

Review scalable Astro boundaries, complex AEM models, evolving tokens, CSP/RAC security review,
and deployment strategy. Ask what evidence supports the security and rollout decision and which
risks require another specialist.

- **Astro:** scalable architecture. <a id="item-l4-track-b-astro-aem-astro"></a>
- **AEM:** complex models. <a id="item-l4-track-b-astro-aem-aem"></a>
- **CSS:** tokens evolution. <a id="item-l4-track-b-astro-aem-css"></a>
- **Security:** CSP, RAC audit. <a id="item-l4-track-b-astro-aem-security"></a>
- **DevOps:** blue-green deployments. <a id="item-l4-track-b-astro-aem-devops"></a>
- Visible technical leadership. <a id="item-l4-track-b-astro-aem-visible-technical-leadership"></a>

### Soft skills

<a id="detail-l4-soft-skills"></a>

[Source criteria](./Frontend_Career_Path_Chapter.md#criteria-l4-soft-skills)

Bring examples of a scoped decision made without daily check-ins, a negotiation with evidence
and alternatives, and a disagreement resolved into a documented decision. Stakeholders can
describe impact and collaboration; technical reviewers verify the underlying decision quality.

| Competency | Observable indicators |
| --- | --- |
| <a id="item-l4-soft-skills-autonomy"></a>**Autonomy** | Delivers 1–2 week features without daily check-ins and makes technical decisions within scope. |
| <a id="item-l4-soft-skills-negotiation"></a>**Negotiation** | Negotiates scope, deadlines, or technical debt with stakeholders using clear arguments and alternatives. |
| <a id="item-l4-soft-skills-conflict-resolution"></a>**Conflict Resolution** | Guides technical disagreements towards documented, agreed decisions. |
| <a id="item-l4-soft-skills-visibility"></a>**Visibility** | Creates visible team or product impact beyond individual tasks. |

## Promotion gate

The [L4 promotion gate](./Frontend_Career_Path_Chapter.md#criteria-l4-promotion-gate) specifies
80% hard skills and 100% soft skills under the general criteria. The source includes Architect
input for L4+. Stakeholder feedback should therefore complement, rather than replace, review of
technical depth and architectural judgement.

## Source and navigation

[Frontend source chapter](./Frontend_Career_Path_Chapter.md)

[Previous level: L3](./l3-semi-senior.md) · [Frontend overview](./README.md) ·
[Next level: L5](./l5-senior.md)
