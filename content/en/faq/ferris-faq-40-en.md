---
title: "Is Change Data Capture (CDC) supported by databases?"
tags: [cdc]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Is Change Data Capture (CDC) supported by databases?" >}}

<!-- ANSWER -->

CDC can be classically via the DB Redologs or via the monitoring of the commits of individual tables, whereby each change on a record is also routed as a Kafka message via the platform.

{{< /faq >}}
