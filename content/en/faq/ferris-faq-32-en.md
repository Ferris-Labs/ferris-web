---
title: "Which mechanisms for creating and receiving producers and consumers are supported?"
tags: [producer, consumer, pub sub]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Which mechanisms for creating and receiving producers and consumers are supported?" >}}

<!-- ANSWER -->

The platform supports all producers / consumers and push / pull mechanisms and these can be implemented via various technologies (script, app, endpoint or container-based).Editing and renewed messages can only be implemented via a continuous audit trail - (1) original message, (2) edited message and (3) forwarding with logged reference - can be realized.The platform can act as a message broker and the piorization can be displayed in different ways: (a) via Service Levels, (2) via project & service-specific prioritiy queues (and K8S resources defined in bandwidths) or (3) via dedicated containers& associated K8S resources.

{{< /faq >}}
