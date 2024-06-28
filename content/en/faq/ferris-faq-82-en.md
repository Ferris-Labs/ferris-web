---
title: "Is there a module to manage clients (applications, servers, machines)?"
tags: [iam, keycloak, security, user management]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Is there a module to manage clients (applications, servers, machines)?" >}}

<!-- ANSWER -->

The platform bids a powerful module for the client identity management, which enables the simple management and configuration of clients in different scenarios.

Client management:
- The platform provides its own module that enables administrators to create, configure, manage and monitor clients.
- Clients can have specific configurations, depending on their type (e.g., web application, mobile application, service).

Client types:
- Web application (public or confidential): For applications based on user interaction.
- Service (Bearer -Only): For services that have no own - user interfaces and only access resources.
- Service account (service account): for the exchange of - authentication information between service.

Client configuration:
- Administrators can define a variety of configuration options for each client, including URLs, access authorizations, redirect-uris, and much more.
- The configuration can also include specific security settings for each client.

Client roles and permissions:
- enables the allocation of roles and permissions at the client level.- This facilitates the definition of access controls on resources protected by the client.

Client Secrets and Security:
- Clients can be secured with secret keys (client secrets) to ensure communication with the authentication server.
- supports various authentication and authorization mechanisms for clients.

Client protocols and integration options:
- Supports various authentication protocols such as Oauth 2.0, OpenID Connect and Saml 2.0, which enables to integrate clients in different environments.

Client monitoring:
- Administrators can monitor the activities and behavior of clients via the Keycloak administration dashboard.

{{< /faq >}}
