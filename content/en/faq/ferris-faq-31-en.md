---
title: "Are these patterns supported: Request and response, messaging, streaming, file transfer?"
tags: [integrations]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Are these patterns supported: Request and response, messaging, streaming, file transfer?" >}}

<!-- ANSWER -->

All required patterns are supported and they are also with various technologies.Abstraction levels (1) script-based, (2) API based and (3) container-based all patterns can be implemented in different ways of technology and modeling:

Request/Response:
- OpenAPI both along the standardized and specific metadata
- Graphql based on the analog OpenAPI models
- Synchronous and asynchronous APIS
- Integration of webhooks
- Safe and scalable operation and monitoring
- Metadata-driven generation of API servers

Messaging:
-Topic / Queue and Message-based management based on Kafka (open source, cloud-based or commercial))
-Illustration of Schema-Based and Schema-Less Topics / Events
- Domain scoping from Events & Topics
- Illustration of all message sequences (FIFO, LIFO, ONLYONCE, Exactlyonce, Timewindows; etc.)
- Development, testing & operation of consumer & producer components (both as a standardized EDGE adapter and functionality specially developed for USZ)

Streaming:
- Connection of various data management / data lake architectures (directly or via Kafka) for processing permanent data flows
- Decentralized and descriptive development of streaming-specific consumer and producer components

Filetransfer:
- Support existing filest systems (propriatär & s3 compliant)
- Support from Perisistant Volume Claims (K8S Baseline)
- Support of virtual file caches and fleeting, temporary file systems per service and project
- Batch and manual processing and orchestration of file metadata
-File -Based Intention including metadata, data quality and enemy

{{< /faq >}}
