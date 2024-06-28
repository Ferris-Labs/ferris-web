---
title: "Does the platform offer a user management module for interface users?"
tags: [iam, keycloak, security, user management]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="Does the platform offer a user management module for interface users?" >}}

<!-- ANSWER -->

Keycloak as a central platform IAM offers comprehensive functions in the field of user identity management.

User management module for interface users:
- Powerful user management module, which enables the management of interface users such as doctors, patients, assignments, etc.
- Users can be created, edited, deleted and organized in groups to facilitate the management and organization of users.
- The module also enables the management of user attributes and custom properties.

Multifactor authentication (MFA):
- Supports the implementation of multifactor authentication (MFA).
- MFA adds additional security levels by required several - authentication methods for access to resources.

Supported MFA methods:
- One-off password (OTP): Users receive a one-time code on your mobile device or by email.
-E-mail confirmation: The user receives a confirmation link by email.
- Security questions: Users must answer predefined security questions.
-Push notifications: The user receives a push notification on his registered device.

Configurable MFA guidelines:
Administrators can configure MFA guidelines and determine which methods and in which combination they are required for certain user groups or applications.

Adaptive authentication:
Keycloak supports adaptive authentication, in which the MFA requirements can be dynamically adapted based on various factors in order to optimize user-friendliness and security.

{{< /faq >}}
