---
title: "Does the platform have the ability to manage and validate tokens (e.g. caches from jwt access tokens)?"
tags: [token, jwt, saml, security]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Does the platform have the ability to manage and validate tokens (e.g. caches from jwt access tokens)?" >}}

<!-- ANSWER -->

The platform has extensive skills in management and validating tokens.Here are some important points:

Token management:
- The platform can manage different types of tokens, with JSON Web Tokens (JWT) being the most common form.This includes access tokens, refresh tokens and ID tokens.
- There are mechanisms for managing and securing tokens, including the possibility of storing access tokens in the cache in order to reduce the stress on the authentication server.

Token validation:
- The platform conducts the validation of tokens to ensure that they have been valid and not manipulated.
- Validation can be based on signatures, process data and other specific token properties.
Token standards:

Support of different token standards:
- JWT (JSON Web Tokens): For the representation of tokens in JSON format, which Keycloak often use for access tokens and ID tokens.
- Saml (Security Association Markup Language): Keycloak also supports Saml token, especially in the context of integrations with Saml 2.0 Identity provider.

Token-caching:
- Caching mechanisms for access tokens to improve performance and reduce the need for repeated validations.
- The caching mechanism can be configured to ensure that the balance and topicality of the tokens are observed.

Token rotation:
The platform also supports token rotation, especially in the use of refresh tokens.This means that new refresh tokens can also be generated when updating access tokens.

{{< /faq >}}
