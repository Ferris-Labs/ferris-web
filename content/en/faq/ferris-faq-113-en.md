---
title: "What functions does Ferris already provide to ensure performance and availability?"
tags: [logging, monitoring, performance, availability]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="What functions does Ferris already provide to ensure performance and availability?" >}}

<!-- ANSWER -->

The control and management of the platform takes place centrally via two main tools:

Management UI:
Management UI offers a user -friendly surface to control the application.Administrators can configure the platform, activate monitoring functions and carry out general administrative tasks.

Cube CTL:
Cube CTL is used to control the cluster and manage recovery functions.This command line interface enables precise control over cluster operations and ensures the efficient implementation of recovery measures if necessary.

The architecture is based on event -driven use cases, supported by an integrated Kafka Message Bus.This architecture ensures high reliability and complete recovery in the event of a failure.The Kafka Message Bus enables the safe transfer of messages, and in the event of a system failure, the messages are completely restored to ensure data integrity and continuity.

The platform is extremely robust and performant.Existing implementation has an availability of over 99%.

{{< /faq >}}
