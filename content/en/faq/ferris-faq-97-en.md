---
title: "How are interfaces in the inventory published?"
tags: [integrations, interfaces]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="How are interfaces in the inventory published?" >}}

<!-- ANSWER -->

The platform fulfills the inventory management as follows:

Interface publication:
- Interfaces are automatically published via Kubernetes and OpenAPI/rest.The publication takes place by providing API services that provide OpenAPI specifications and are accessible to RESTSCUL Endpoints.

Lifecycle statistics:
- The inventory offers comprehensive lifecycle statistics for every interface.This includes information such as deployment status, version history, update times and monitoring data that reflect the current state of the interfaces.

Supported formats:
- The inventory supports various formats for the publication of interfaces, including OpenAPI specifications in JSON or YAML.This enables flexible and standardized documentation of the published APIs.

Collected metadata:
- Comprehensive metadata are collected, including descriptions, versions, owner information and contact details.These metadata serve to document and identify the interfaces in the inventory.

Functionalities for consumers:
- Consumers have access to functions such as accessing API descriptions, surveillance data, version historia and documentation directly from the inventory.This facilitates the integration and use of the published interfaces.

Access and roles:
- The access authorization is roll -based and can be integrated into Active Directory (AD) or LDAP.Administrators can assign user roles to control access to certain interfaces or actions.

Group and folder structures:
- Interfaces can be stored in the inventory according to logical groups or in folder structures.This facilitates the organization and management of interfaces, especially with extensive integration landscapes.

Tagging for relieved search:
- Entries in the inventory can be provided with tags to enable a relieved search.These tags can be customizable and help to categorize and filter interfaces according to certain criteria.

Publication of external interfaces:
- Yes, external interfaces that are not implemented or configured directly on the integration platform can still be published in the inventory.This enables a holistic overview of all relevant interfaces, regardless of their implementation on the platform.

{{< /faq >}}
