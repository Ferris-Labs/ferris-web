---
title: "Is the transport of very large files supported?"
tags: [data, volumes]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Is the transport of very large files supported?" >}}

<!-- ANSWER -->

Yes, this is achieved by the combination of S3 and Cloud events.

CT Files are sent to the S3 Bucket with the URL via the rest.The associated metadata are transmitted and processed separately via Kafka.

{{< /faq >}}
