---
title: "Can synchronous and asynchronous APIs be protected with Oauth?"
tags: [oauth, sync, async, security]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Can synchronous and asynchronous APIs be protected with Oauth?" >}}

<!-- ANSWER -->

The platform A comprehensive support for Oauth 2.0 and OpenID Connect enables integration with various identity providers, including Azure AD, and can be used for both synchronous and asynchronous API to protect resources.

Supported Flows:
- Authorization Code Flow
- Implicit flow
- Resource owner Password credentials flow
- Client credentials flow

Support of OpenID Connect:
Yes, the platform supports OpenID Connect (OIDC), an expansion of OautH 2.0, provides identity management via tokens.

Identity Provider Integrations:
- The platform offers a wide range of identity provider (IDP) integrations.This includes integrations with various IDPs such as LDAP, Active Directory, Google, Facebook and others.

Integration with Azure AD:
The platform can be integrated with Azure Active Directory (AD).

Protection of synchronous and asynchronous apis with Oauth:
OAWH 2.0 can be used for both synchronous and asynchronous APIs to control access to protected resources.
In the case of synchronous APIs, authentication usually takes place by transmitting Oauth-token in the authorization header of the HTTP request.
For asynchronous APIs, such as messaging or streaming, Oauth-token can be used in inquiries or as part of the authentication information, depending on the specific implementation.

{{< /faq >}}
