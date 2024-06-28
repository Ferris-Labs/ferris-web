---
title: "What does the Basic Authentication platform support in the form of a header token?Can both synchronous and asynchronous APIs be protected in this way?"
tags: [autentication, security, api]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="What does the Basic Authentication platform support in the form of a header token?" >}}

<!-- ANSWER -->

Support of basic authentication in the form of a header token:
- Basic authentication itself is usually based on the transmission of the username and password in the authoritation header, whereby the login information is base64-encoded.
- If it means "header tokens" that the platform supports token-based authentication, this could be implemented in conjunction with Basic Authentication.The token is used instead of the username and password.

Connect user inventories and password check:
- Keycloak, as an example of a platform that provides IAM functions, enables integration with various user inventories, including LDAP, Active Directory and user-defined user databases.
- The password check can be carried out by integration with external identity stores or by using internal mechanisms, such as the storage of user data in KeyCoLak.

Protection both synchronous and asynchronous APIS:
- Basic authentication can be applied to Synchrone APIs by transmitting the login information in the authoritation header.
- For asynchronous APIs, such as messaging or streaming, token-based authentication, including Basic Auth with tokens, could be more relevant.A token is generated and used for authentication.

{{< /faq >}}
