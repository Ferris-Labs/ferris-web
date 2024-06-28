---
title: "Which mechanisms are supported on the platform for authentication of exposed interfaces?"
tags: [iam, keycloak, authentisierung, security]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Which mechanisms are supported on the platform for authentication of exposed interfaces?" >}}

<!-- ANSWER -->

The platform uses KeyCloak IAM as an Identity Access Management System.The authentication takes place centrally via KeyCloak, which is untried all common mechanisms and protocols.In particular:

- Username Password
- Social Identity Providers (e.g. Google, Facebook)
- OpenID Connect
- Saml (Security Association Markup Language)
- SSO (single sign on)

{{< /faq >}}
