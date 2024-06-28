---
title: "Does the platform support integration with an external public key infrastructure or Certificate Authority?"
tags: [security, key, certificates]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Does the platform support integration with an external public key infrastructure or Certificate Authority?" >}}

<!-- ANSWER -->

KA, the platform offers support for integration with an external public key infrastructure (PKI) or Certificate Authority (CA).Here are the basic steps and opportunities for integration:

Use of SSL/TLS certificates:
- The IAM platform itself can be protected with SSL/TLS certificates, and it is possible to use certificates from an external PKI or CA.This ensures safe communication between users and the IAM server.

Configuration of the TLS protocol:
- Administrators can adapt the TLS configuration in Keycloak so that it works with the certificates of the external PKI or CA.This includes the configuration of cipher suites, protocol versions and other TLS parameters.

Client certificate authentication:
-The platform also supports the client certificate authentication, in which users can authenticate themselves with a certificate.These certificates can be issued by an external PKI.

Integration with external identity providers (IDPS):
- The platform can act as an identity provider (IDP) and integrate with external identity providers.If the external PKI or CA acts as an identity provider, Keycloak can be integrated with it to enable seamless authentication.

Federation and Saml support:
- Supports Federation and the Security Association Markup Language (Saml).This enables integration with external identity providers who support Saml and facilitates interaction with an external PKI.

Certificate -based authentication in clients:
- When configuring clients, certificates can be used as an authentication method for access to resources.This enables strong authentication based on certificates.

Client authentication with Mutual TLS (MTLS):
- Supports Mutual TLS, in which both the client and the server authenticate each other with certificates.This can be part of an integration with an external PKI.

Use of X.509 certificates:
- The platform can use X.509 certificates issued by an external PKI to check the identity of users or services.

{{< /faq >}}
