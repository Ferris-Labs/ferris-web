---
title: "Are there different variants of how use case projects can be implemented?"
tags: [use cases]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Are there different variants of how use case projects can be implemented?" >}}

<!-- ANSWER -->

Variant 1) 
Direct On Cloud provision of all non-security relevant components and services of the IOP (Green Zone).Simultaneous on-premise provision of a mirrored platform for all critical components & services (Red Zone).Integration of the role and ripping concepts based on the USZ IAM across both zones.Illustration of the connection of both security zones via the various required anonymization and tokenization methods.Use of the two -part environment for an economically optimal load distribution.

Variant 2) 
One-sided provision of the iOP only on-premises on the available USZ infrastructure.Design and implementation of all components in an infrastructure-independent way, so that in addition to the environments development, testing and production, a deployment on other (future) cloud providers or hyperscalers is guaranteed.

Evaluation: While we see variant 2 as a minimum recommendation, in which only the design and independence of infrastructure are created as a prerequisite, these are also implemented and tested in variant 1.From our experience, there is a considerable difference between the expense between these two variants, since the role concepts, IAM connections, policism management and metadata across all services must not only be conceptually available, but must also be practical.This is often reflected in an effort of 1.5-2 people over 6-9 months.

{{< /faq >}}
