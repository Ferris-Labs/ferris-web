---
title: "Does the platform have the ability to save messages (for transport) during a defined time?"
tags: [caching, messaging]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Does the platform have the ability to save messages (for transport) during a defined time?" >}}

<!-- ANSWER -->

Yes, we have concrete implementations in which the Kakfa Cluster is even used as a medium to long-term storage layer.And in a highly transchable and highly volume operational environment of a large bank.The logs / messages are held up to 6 months in order to save the overhead of an additional batch processing.The news will then be archived after successful preparation by this "Last Call" Consumer.

{{< /faq >}}
