---
title: "Can synchronous and asynchronous APIs be protected?"
tags: [api, async, sync, security]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Can synchronous and asynchronous APIs be protected?" >}}

<!-- ANSWER -->

The platform supports the authentication by API keys and offers various methods for the safe transmission of these keys.The use of API keys can be used for both synchronous and asynchronous APIs to control access to protected resources.

Types of key transmission:
-As a header: The API-Key can be transmitted in the authorization header of the HTTP request.
-As a query parameter: The API key can be transmitted as part of the URL query parameters.
-In the request playload: The API key can also be transmitted as part of the data body of the request.
Protection of synchronous and asynchronous APIS:

API keys can be used for both synchronous and asynchronous APIs to regulate access to protected resources.
In the case of synchronous APIs, the API key is usually transmitted as part of the HTTP header or as an URL parameter.For asynchronous APIs, such as messaging or streaming, the API key can be used in inquiries or as part of the authentication information, depending on the specific implementation.

{{< /faq >}}
