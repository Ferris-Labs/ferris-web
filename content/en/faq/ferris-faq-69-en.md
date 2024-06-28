---
title: "How are implementation SAP skills supported?"
tags: [sap, integration]
category: "nan"
---

<!-- QUESTION -->

{{< faq question="How are implementation SAP functions supported?" >}}

<!-- ANSWER -->

Soap: On the basis of existing WSDL, XSD or XML definitions, we can use all SAP end points bidirectionally.
RFC: Use and integration of the SAP NetWeaver RFC SDK and Connector.This pattern also applies analogously to SAP S4/HANA SOAP.
SAP AI: Can be integrated using the SAP AI Business Services SDK
QRFC / TRFC: Events that are triggered in SAP are listed on specific topics and event types..
BAPI: In this pattern, the relevant Bapis from the iOP platform are initialized, the corresponding answer is recorded as a kafka event and continuously processed.
IDOC / ALE: The IOP receives the "raw" IDOCs via ALE or a directed RFC port and convert their XML or text content into Kafka and IOP -compliant messages (with all options) and wrapped this result also within a cloude event.When sending IDOCs to SAP, this is done in a sequence.
SAP S4/HANA OADATA: However, this pattern complements the standard remaining pattern with SAP specific authorization and parameterization in large parts of the classic rest pattern.
ABAP PROXIS: In the assumption that USZ uses the SAP Enterprise Services Repository (ESR), the analog pattern for standard XML -based messages applies.On the part of IOP, dedicated web service endpoints would then be held actively (or actively activated), which receive and process these XML messages.
S4 / Hana Business Events: In this pattern we assume an active SAP Event Mesh or Event Message Broker Instance, which we can access either via webhooks or via Message Topics / Queues.
SAP CDs: We assume that all semantic views that are relevant for the IOP are also published as Odata Services and are therefore accessible.Then this pattern also follows a simple request / response procedure with all the possibilities via parameters, secrets and event processing.

{{< /faq >}}
