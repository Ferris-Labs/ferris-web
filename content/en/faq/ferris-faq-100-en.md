---
title: "Can a Ferris platform be managed centrally?"
tags: [platform, management]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Can a Ferris platform be managed centrally?" >}}

<!-- ANSWER -->

The platform is configured and managed via Kubernetes and helm charts.Here is a summary of the configuration and administrative processes:

Kubernetes as an orchestration platform:
- The platform uses Kubernetes as an orchestration platform to manage, deploy and scale container-based applications.
- Kubernetes enables the definition of resources such as pods, services and deployments to operate applications in a distributed environment.

Helm charts for configuration and provision:
- HELM is the preferred tool for configuration and provision.HELM Charts are packages of predefined Kubernetes resources that simplify the configuration and provision of applications.
- The platform uses helm charts to easily configure and deploy applications, services and dependencies.

Central configuration files:
- The platform is configured via central configuration files.These files contain settings for different aspects, including API endpoints, security guidelines and integration parameters.

Automated scaling and load distribution:
- Kubernetes enables automated scaling of applications based on resource use and load.
The platform is configured in such a way that it uses load distribution functions of Kubernetes to ensure an even distribution of inquiries to the available services.

Monitoring and logging:
- Monitoring and protocol are configured via Kubernetes resources.This includes the use of tools such as Prometheus and Grafana for monitoring resource use and application performance.

Integration of helm repositories:
- HELM repositories are integrated into the platform to facilitate access to helm charts.This enables an efficient update and expansion of the platform by accessing prefabricated configuration templates.

Version and rollback:
- The platform uses Helm's versioning functions to ensure uniform deployments.If necessary, Helm also enables rollbacks to previous versions to fix unexpected problems.

{{< /faq >}}
