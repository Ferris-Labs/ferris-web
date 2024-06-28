---
title: "Does the platform have the ability to map the business processes and to dissolve and carry out processing steps and data flows accordingly?"
tags: [business processes, automation]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Does the platform have the ability to map the business processes and to dissolve and carry out processing steps and data flows accordingly?" >}}

<!-- ANSWER -->

We support three different Basipatterns for the mapping of business processes, whereby the integration depth from "on platform" ranges to "hybrid" to "external":
1) On platform: The combination of event-driven process chains with parameters and Ui fragments allow pure handling with the means of the platform
2) Hybrid: Either the event chains or the UI components can be used individually or in the tandem and the results or intermediate results can be handed over to external systems or are handled by these EPM-catches.
3) Extern: The platform is only used as a data transport and routing agent and Payoad and Event State are transferred to an external BPM platform or adopted by it (this can then be done in turn via APIs, asynchronous calls, webhooks or message queues)

{{< /faq >}}
