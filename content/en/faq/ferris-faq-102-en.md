---
title: "How are various environments (e.g. development, test, production) mapped and managed?"
tags: [environment, management]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="How are various environments (e.g. development, test, production) mapped and managed?" >}}

<!-- ANSWER -->

This configuration principles and the use of Kubernetes in conjunction with Helm Charts ensure a clear separation and efficient management of the various environments.

Environment management: illustration and administration

Configuration via Kubernetes:
The various environments such as development, test and production are configured via Kubernetes resources.This includes the definition of namespaces, each of which is assigned to a specific environment.

Namespace structure:
A clear namespace structure is implemented to separate different environments.Each environment has its own namespace, which contains resources such as pods, services and configmaps.

Helm charts for Environment-specific configuration:
Helm charts are used to manage environment-specific configurations.This enables easy adjustment of the deployments and configurations for every environment.

Use of configmaps and secrets:
Configurations that differ between the environments, such as database connections or API keys, are stored in Kubernetes configmaps and secrets.This enables simple administration and updating.

Provision of ambient variables:
Environmental variables are used to provide specific settings for any environment.These can be defined in the helm charts or directly in the Kubernetes resources.

Monitoring and logging pro Environment:
The monitoring and protocol are configured for any environment.This enables a differentiated view of the performance and errors in any environment.

Separation of resources and resource quotas:
Each environment has its own resource quotas and restrictions to ensure that resources are used efficiently and that there are no unexpected bottlenecks.

{{< /faq >}}
