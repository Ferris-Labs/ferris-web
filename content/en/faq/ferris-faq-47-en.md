---
title: "Which schema formats are supported?"
tags: [schema, validation]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Which schema formats are supported?" >}}

<!-- ANSWER -->

Schema can be defined on the model, project, service and topic level and, depending on the context, hard or softly validated.With a schema -bound implementation of a service on DB or Topic level, the other levels are also schema bound.Schema formats are basically to be defined JSON, YAML, text or XSM.All messages are generally defined as a cloud event wrapper and the specific payloads can be freely defined

{{< /faq >}}
