---
title: "Is there an overview of the Ferris development Tools and Technologies?"
tags: [development, cycles]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Is there an overview of the Ferris development Tools and Technologies?" >}}

<!-- ANSWER -->

Platform tools:
Design:
- Separation in process, logic and data view when separate
Development of each service along these levels
- Scheme extraction from data
- Scheme Management (Yaml via IDE and GIT Repository)
- Process design & management (Yaml via IDE and GIT Repository)
- Tag-based classification per component / service

Development:
- Theia is based on GIT synchronization
- Fine granular components real management
- Project & service management (with git synchronization)
- Context management (parameters, secrets, environmental variables)
- Metadata management (to APIS / Services, Streams and Schemas)
- Security management (roles, tokens, functionalities)

Testing:
- Zero-deployment by direct .git synchronization
- Change and test case-specific context
- Fine granular release tracking for debugging & iterations
- Integrated roles / user management per service / project

Lifecycle mgmt:
- Separate upgrade and separate scaling per level per service
- Support of different priorities and SLAS (per service)
- Container & image management including deployments, PVC & Ingress

External tools with connection (always foss and commercial tools)
Design:
- Leanix or other architecture tools
- Data catalogs / metadata repositories (e.G. OpenMetadata)
- Data modeling & schema modeling
- Scheme & model matching (also via local llm)

Development:
- External Ides (both locally and Devcloud / on Prem)
- CI/CD and Secdevops Tools
- External Vaults and Secrets Management
- External BI and Analytics Tools
- External Linting & Co-Pilot LLM models (also locally hosted)

Testing:
- External test data and test case management
- External test automation & evaluation
- Screening & Monitoring Security Issues Code & Libraries

Lifecycle-mgmt.:
- Key-Value Stores and Config Management
- Container & Image Repositories (Harbor Based)
- External CI/CD Deployment Tools
- External Security Policy Management (Open Policy Agent)
- External SLA / SLO / Accounting & Usage Tracking

{{< /faq >}}
