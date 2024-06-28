---
title: "Does the platform have the ability to treat errors that occur during the term of a program?"
tags: [error handling, monitoring, logging]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Does the platform have the ability to treat errors that occur during the term of a program?" >}}

<!-- ANSWER -->

Yes, this is possible, but must also be careful as part of the service design.This means that both dedicated "Try Fail Recover" Loops and automated "Retries-After-Fail" are possible and can be configured depending on the project and service.The use of dynamic event chains may also be helpful in this scenario (standardized error event types that only trigger further consequences if necessary).Usually we use "Dead Fletter Queues" for scenarios in which fail effects or duration cannot be qualified from the outset.In this case, either human intervention or an automated process can contribute to the resolution of the errors.

{{< /faq >}}
