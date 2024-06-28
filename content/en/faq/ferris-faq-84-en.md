---
title: "Does the platform offer the possibility of awarding identities (users and clients in the sense of API consumers)?"
tags: [roles, security,iam]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Does the platform offer the possibility of awarding identities (users and clients in the sense of API consumers)?" >}}

<!-- ANSWER -->

The platform offers powerful roles management that enables identities (users and clients) with different roles and thereby control access management at a fine granular level.

Rolling for identities (users and clients):
- Allows the allocation of roles to identities, including users and clients (API consumers).
-Roles can be awarded at different levels, including realm rolls (valid for all clients in the realm) and client roles (specifically for a specific client).

Allocation of roles:
- Administrators can assign users and clients to roles, either directly via the user interface of the administrator or via the Admin API.

Fine -grained access control:
- Rolling management enables fine-grained access control.- By assigning roles, specific access rights can be controlled to resources and functions.

Inheritance of roles:
- supports the inheritance of roles.Users can inherit realm roles that then apply to all clients in the realm or inherit specific client roles from certain clients.

Access management by roles:
-Access management is controlled by roles management.By allocating roles, authorizations and access rights can be defined.
- Roles can be used in the various OautH 2.0 and OpenID Connect Authorization Flows to regulate access to protected resources.

Client-specific roles:
- Each client can have its own specific roles that apply to this client.This enables granular control of access for different API consumers.

Dynamic role management:
- Also supports dynamic role management, in which rolls can be assigned based on user attributes or other dynamic factors.

{{< /faq >}}
