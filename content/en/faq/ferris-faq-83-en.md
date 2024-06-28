---
title: "Does the platform offer the possibility to manage API keys for users and clients?"
tags: [api, key, token, security]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Does the platform offer the possibility to manage API keys for users and clients?" >}}

<!-- ANSWER -->

Yes, the platform offers support for external API key management.

Client Credentials Grant: KeyCoLak supports the Client Credentials Grant, in which clients (e.g. applications or services) can receive API keys for access to protected resources.

Client Registration:
Enables clients to be registered, which is required for the creation of API keys.Different configuration options can be determined during the registration process.

Token expiry:
The API keys created by the authentication process can be provided with expiry times.This means that an API key becomes invalid after a certain period of time.

Quotas and restrictions:
Offers the possibility of specifying quotas and restrictions for access to resources.This could affect, for example, the number of inquiries per unit of time or other access restrictions.

Scope-based access control:
Enables the definition of scopes, which can then be used to control access to certain resources.This enables granular control over which parts of the API can be used by a certain API key.

{{< /faq >}}
