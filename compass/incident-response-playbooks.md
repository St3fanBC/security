---
title: Incident response playbooks
description: Use these playbooks to quickly respond to security incidents in the Microsoft cloud.
keywords: investigation, attack, microsoft threat protection, microsoft 365, search, query, telemetry, security events, antivirus, incident, response, incident response, playbook, guidance, microsoft 365 defender
search.product: DART
search.appverid: met150
ms.prod: m365-security
ms.mktglfcycl: deploy
ms.sitesec: library
ms.pagetype: security
f1.keywords: 
  - NOCSH
ms.author: josephd
author: JoeDavies-MSFT
localization_priority: Normal
manager: dansimp
audience: ITPro
ms.collection: 
  - M365-security-compliance
  - m365initiative-m365-defender
ms.topic: article
ms.technology: m365d
---

# Incident response playbooks

You need to respond quickly to detected security attacks to contain and remediate its damage. As new widespread cyberattacks happen, such as [Nobellium](https://msrc-blog.microsoft.com/2020/12/21/december-21st-2020-solorigate-resource-center/) and the [Exchange Server vulnerability](https://msrc-blog.microsoft.com/2021/03/16/guidance-for-responders-investigating-and-remediating-on-premises-exchange-server-vulnerabilities/), Microsoft will respond with detailed incident response guidance. 

You also need detailed guidance for common attack methods that malicious users employ every day. To address this need, use the incident response playbooks for these types of attacks:

- [Phishing](incident-response-playbook-phishing.md)

- [Password spray](incident-response-playbook-password-spray.md)

- [App consent grant](incident-response-playbook-app-consent.md)

Each playbook includes:

- **Prerequisites:** The specific requirements you need to complete before starting the investigation. For example, logging that should be turned on and roles and permissions that are required.
- **Workflow:** The logical flow that you should follow to perform the investigation.
- **Checklist:** A list of tasks for the steps in the flow chart. This checklist can be helpful in highly regulated environments to verify what you have done.
- **Investigation steps:** Detailed step-by-step guidance for the specific investigation.

Also see [Microsoft’s DART ransomware approach and best practices](incident-response-playbook-dart-ransomware-approach.md) for information on how the Detection and Response Team (DART) at Microsoft deals with ransomware attacks.

## Incident response resources

- [Overview](incident-response-overview.md) for Microsoft security products and resources for new-to-role and experienced analysts
- [Planning](incident-response-planning.md) for your Security Operations Center (SOC)
- [Process](incident-response-process.md) for incident response process recommendations and best practices
- [Microsoft 365 Defender](/microsoft-365/security/defender/incidents-overview) incident response
- [Azure Sentinel](/azure/sentinel/investigate-cases) incident response
