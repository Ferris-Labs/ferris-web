---
title: "How are RTO and RPO achievements achieved?"
tags: [rto rpo]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="How are RTO and RPO achievements achieved?" >}}

<!-- ANSWER -->

Postgres or subordinate databases are used to store operational data.Consul is used to create backup scripts.Minio serves as an object storage and standard disk backups.And Kafka Data Retention will be set up depending on the audit requirements.

Source code backups are set up and created in Git (GitHub, Gitlabs or Bitbucket).

The combined Kubernetes and Kafka solution offers robust mechanisms for back-up and restoration to achieve recovery time objectives (RTO) and Recovery Point Objectives (RPO).These skills are made possible by a combination of internal platform functions and proven strategies.

Strategies for back-up & restoration:
Securing and restoration of data:
The platform supports regular backups of Kafka data and Kubernetes resources to minimize data loss.

Version of fuses:
A versioning of the fuses is used in order to be able to fall back on different times.This enables selective restoration based on time stamps or version numbers.

Incremental fuses:
The platform offers the possibility of incremental fuses to deal with large data volume efficiently and accelerate the backup process.

Functions of the platform:
Automated back-up routines:
The platform enables the configuration of automated back-up routines for Kafka data and Kubernetes resources.This ensures regular execution of fuse without manual effort.

Integrated security and recovery tools:
The platform provides integrated tools for securing and restoration, which are especially optimized for Kubernetes and Kafka.This includes mechanisms for the consistent security and restoration of conditions.

Monitoring of back-up processes:
Monitoring functions are provided to monitor the status and integrity of the back-up processes.This enables early detection of problems and quick troubleshooting.

Encryption and security:
The platform integrates safety measures, including encryption of back-up data, to ensure confidentiality and meet compliance requirements.

Documentation and reporting:
The platform offers comprehensive documentation and reporting on back-up operations carried out to ensure transparency and traceability.

Additional tools/technologies:
If necessary, external tools can be integrated for long-term data storage or special requirements for back-up and recovery.This could include, for example, the use of cloud services for back-up and long-term storage.

{{< /faq >}}
