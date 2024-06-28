---
title: "Is authorization possible based on ad security groups?"
tags: [authorisation, security, ad]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Is authorization possible based on ad security groups?" >}}

<!-- ANSWER -->

The platform offers a number of authorization mechanisms to control access to exposed interfaces.Here are some of the supported mechanisms and information on the granularity of the authorization distribution:

Supported authorization mechanisms:
- Keycloak supports various authorization mechanisms, including:
- RBAC (Role-based Access Control): Authorization based on user roles.
- Abac (attribute-based access control): Authorization based on attributes of entity (e.g., userattribute).
- ACLS (Access Control Lists): Authorization based on specific access control lists.
- Granularity of the authorization distribution:

Permits can be granular on different levels, including:
- per developmental environment: You can configure permissions specifically for different environments.
- per application: authorizations can be set at the application level to control access to specific applications.
- Per channel: Depending on the configuration, permissions can be distributed at the channel level (e.g. API channels).
- per interface: Fine granular control of the authorizations at the level of the individual interfaces or end points.
- Separate reading and writing:

The platform also enables the separate allocation of reading and writing.This can be configured on rolls or individual level.You can assign specific permissions for reading and writing access to resources or APIs.

Authorization based on ad security groups:
The platform can be integrated with Active Directory (AD), and it is possible to carry out authorization based on AD-Security Groups.
Users can get roles based on their ad security group in KeyCoLoak, and authorization can be based on these roles.

For which patterns:
The supported authorization mechanisms and the granularity of the authorization distribution are flexible and can be used for various patterns, including Request/Response, Messaging, Streaming and Filetransfer.

{{< /faq >}}
