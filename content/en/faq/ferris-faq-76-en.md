---
title: "Does the platform support certificate-based registration?"
tags: [security, certificates]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Does the platform support certificate-based registration?" >}}

<!-- ANSWER -->

The platform supports the certificate -based authentication, especially in the context of TLS/SSL.

Supported certificates:
- Keycloak supports various types of certificates, especially X.509 certificates used as part of TLS/SSL.
Generation of certificates in the platform:

- Usually certificates are issued by a certification body (CA) or created with the help of tools such as OpenSSL.However, Keycloak can deal with certificates issued by a trustworthy CA.

Use of own certificates (USZ):
- The platform can be used with custom certificates issued by a trustworthy CA.

Use in various patterns:
Certificate -based authentication can be used in various patterns and applications, including:
- Request/Response (Synchron APIS): For example, for secure transmission of data between users and the platform via HTTPS.
- Messaging (APIS asynchronous): For example, for secure communication between different services or microservices using certificates.
-Streaming (APIS asynchronous): For securing streaming connections with TLS/SSL certificates.
- Filetransfer: For example, for the authentication of users or systems that transmit files via HTTPS.

{{< /faq >}}
