# Backend Developer · L2 Jr Advanced

[Academy index](../README.md) · [Backend overview](./README.md) ·
[Previous level](./l1-junior.md) · [Next level](./l3-semi-senior.md)

## Purpose

Explain how L2 contributes to recurring Backend work and what product stakeholders should observe
as the Developer moves from foundational learning towards independent delivery.

## Audience

Product Owner, Product Manager, Delivery Lead, and Technical Lead. Backend Developer, Coach, and
Mentor use the linked criteria for technical review.

## Overview

L2 delivers standard Backend work with limited guidance and participates actively in reviews.
The expectation is greater consistency with established patterns, not ownership of complex
architecture decisions. Support remains important when requirements or implementation choices
fall outside familiar situations.

## Product-team context

For example, the Developer might implement a familiar API change including validation, standard
error responses, integration tests, and a database migration reviewed by a more experienced peer.
The important distinction from L1 is the ability to connect those activities into a coherent
delivery rather than wait for instructions at every step.

Stakeholders should see earlier risk communication, more useful questions, and a clearer account
of how the change affects callers and data. A working endpoint without adequate tests or migration
considerations is not equivalent to a complete, reliable delivery.

## Technical criteria and their delivery relevance

| Area | Detailed criteria | Product relevance |
| --- | --- | --- |
| Role focus | [Standard delivery and reviews](./Backend_Java_Career_Path_Chapter.md#l2-role-focus) | Recurring work needs less guidance. |
| Java and Spring | [Configuration, validation, and tooling](./Backend_Java_Career_Path_Chapter.md#l2-java-and-spring) | Fits changes into the existing application. |
| Concurrency and performance | [Blocking and bottleneck basics](./Backend_Java_Career_Path_Chapter.md#l2-concurrency-and-performance) | Recognises obvious execution risks. |
| Engineering and security | [SOLID, patterns, and OWASP basics](./Backend_Java_Career_Path_Chapter.md#l2-engineering-and-security) | Surfaces design and security concerns early. |
| APIs and testing | [API documentation and integration tests](./Backend_Java_Career_Path_Chapter.md#l2-apis-and-testing) | Makes behaviour understandable to consumers. |
| Architecture and integration | [Hexagonal, vertical-slice, and client basics](./Backend_Java_Career_Path_Chapter.md#l2-architecture-and-integration) | Applies agreed boundaries with guidance. |
| Data and AI literacy | [Transactions, Flyway, and AI concepts](./Backend_Java_Career_Path_Chapter.md#l2-data-resilience-and-ai-literacy) | Connects application changes with persistence needs. |

## Evidence and progression

Useful evidence includes consistently delivered standard changes, integration tests, reviewed
migrations, and early discussion of data or security risks. Review whether limited supervision was
sufficient and whether the person understood the work, rather than counting completed stories.

The [L2 gate and L2-to-L3 evidence](./Backend_Java_Career_Path_Chapter.md#l2-promotion-gate)
identify independent stories, API/data quality, and standard CI/CD and security practices as
progression evidence. Product observations should be combined with technical validation.

## References

[English source chapter](./Backend_Java_Career_Path_Chapter.md) ·
[Original presentation](./Backend_Java_Career_Path_-_Globant.pdf)
