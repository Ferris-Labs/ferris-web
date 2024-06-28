---
title: "What authentication mechanisms are supported?"
tags: [authorisation, security]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="What authentication mechanisms are supported?" >}}

<!-- ANSWER -->

Different authentication mechanisms are supported and can be used in different scenarios.

Request/Response (Synchronous APIS):
Authentication services can also be provided for messaging scenarios in which communication asynchronous is carried out.For example, it can support username/password authentication, social login (via external identity providers such as Google, Facebook), OpenID Connect, Saml and others.The standard flows can be configured in such a way that you meet the requirements of the Request/Response pattern.

Messaging (APIS asynchronous):
Authentication services can also be provided for messaging scenarios in which communication asynchronous is carried out.The use of token-based authentication mechanisms such as JWT (JSON Web Token) could be useful here.The platform can serve as an identity provider to transmit authentication information via safe channels to the parties involved.

Streaming (APIS asynchronous):
Streaming scenarios can use similar authentication mechanisms such as messaging.The platform can help implement token-based authentication for safe access to streaming services.The support of Oauth 2.0 can also be relevant to generate and manage accesses.

File transfer:
Various security mechanisms can be offered for file transfer scenarios, especially when it comes to the safe exchange of files.The use of Oauth 2.0 with client-credential-flow or resource own password credentials flow could be relevant in this context to ensure that only authorized entities can access the file transfer.The platform can also play a role in the secure management of access authorizations and identities in file transfer scenarios.

{{< /faq >}}
