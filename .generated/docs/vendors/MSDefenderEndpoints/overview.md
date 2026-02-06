# Microsoft Defender for Endpoint

![Microsoft Defender for Endpoint Logo](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/main/integrations/vendors/MSDefenderEndpoints/assets/logo.png)

Microsoft Defender for Endpoint is an enterprise EDR platform that provides threat detection, investigation, and automated response capabilities across Windows, macOS, Linux, iOS, and Android devices for comprehensive endpoint security

**Category:** EDR  
**Homepage:** https://www.microsoft.com/security/business/endpoint-security/microsoft-defender-endpoint  
**Tags:** edr, endpoint-protection, threat-detection, automated-response, incident-response, microsoft

## Subscription Information

- **Registration Required:** Yes
- **Subscription Required:** Yes
- **Free Subscription Available:** No

## Responders (12)

### MSDefender-FullVirusscan `v1.0`
Run full virus scan to machine with Microsoft Defender for Endpoints

- **Author:** Keijo Korte
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_VirusScan.json](https://github.com/nusantara-self/strangebee-integrations/blob/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_VirusScan.json) ([raw](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_VirusScan.json))

### MSDefender-PushIOC-BlockAndRemediate `v1.0`
Push IOC to Defender client. Block and Remediate mode

- **Author:** Vito Piserchia
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_PushIOCBlockAndRemediate.json](https://github.com/nusantara-self/strangebee-integrations/blob/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_PushIOCBlockAndRemediate.json) ([raw](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_PushIOCBlockAndRemediate.json))

### MSDefender-PushIOC-Warn `v1.0`
Push IOC to Defender client. Warn mode (Microsoft Defender for Cloud only)

- **Author:** Vito Piserchia
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_PushIOCWarn.json](https://github.com/nusantara-self/strangebee-integrations/blob/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_PushIOCWarn.json) ([raw](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_PushIOCWarn.json))

### MSDefender-UnRestrictAppExecution `v1.0`
Enable execution of any application on the device

- **Author:** Keijo Korte, Louis-Maximilien Dupouy
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_UnRestrictAppExecution.json](https://github.com/nusantara-self/strangebee-integrations/blob/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_UnRestrictAppExecution.json) ([raw](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_UnRestrictAppExecution.json))

### MSDefender-RestrictAppExecution `v1.0`
Restrict execution of all applications on the device except a predefined set

- **Author:** Keijo Korte, Louis-Maximilien Dupouy
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_RestrictAppExecution.json](https://github.com/nusantara-self/strangebee-integrations/blob/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_RestrictAppExecution.json) ([raw](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_RestrictAppExecution.json))

### MSDefender-PushIOC-Audit `v1.0`
Push IOC to Defender client. Audit mode

- **Author:** Vito Piserchia
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_PushIOCAudit.json](https://github.com/nusantara-self/strangebee-integrations/blob/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_PushIOCAudit.json) ([raw](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_PushIOCAudit.json))

### MSDefender-AutoInvestigation `v1.0`
Start an automated investigation on a device

- **Author:** Keijo Korte, Louis-Maximilien Dupouy
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_AutoInvestigation.json](https://github.com/nusantara-self/strangebee-integrations/blob/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_AutoInvestigation.json) ([raw](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_AutoInvestigation.json))

### MSDefender-PushIOC-Alert `v2.0`
Push IOC to Defender client. Alert mode. This mode is Deprecated and Audit should be used instead.

- **Author:** Keijo Korte, Louis-Maximilien Dupouy
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_PushIOCAlert.json](https://github.com/nusantara-self/strangebee-integrations/blob/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_PushIOCAlert.json) ([raw](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_PushIOCAlert.json))

### MSDefender-IsolateMachine `v1.0`
Isolate machine with Microsoft Defender for Endpoints

- **Author:** Keijo Korte
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_Isolate.json](https://github.com/nusantara-self/strangebee-integrations/blob/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_Isolate.json) ([raw](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_Isolate.json))

### MSDefender-PushIOC-Block `v2.1`
Push IOC to Defender client. Block mode

- **Author:** Keijo Korte, Louis-Maximilien Dupouy, Vito Piserchia
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_PushIOCBlock.json](https://github.com/nusantara-self/strangebee-integrations/blob/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_PushIOCBlock.json) ([raw](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_PushIOCBlock.json))

### MSDefender-UnisolateMachine `v1.0`
Unisolate machine with Microsoft Defender for Endpoints

- **Author:** Keijo Korte
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_Unisolate.json](https://github.com/nusantara-self/strangebee-integrations/blob/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_Unisolate.json) ([raw](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_Unisolate.json))

### MSDefender-PushIOC-Allowed `v1.0`
Push IOC to Defender client. Allowed mode

- **Author:** Vito Piserchia
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_PushIOCAllowed.json](https://github.com/nusantara-self/strangebee-integrations/blob/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_PushIOCAllowed.json) ([raw](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/main/.upstream/cortex/responders/MSDefenderEndpoints/MSDefenderEndpoints_PushIOCAllowed.json))

---

## Statistics

- **Total Analyzers:** 0
- **Total Responders:** 12
- **Total Functions:** 0
- **Total External Integrations:** 0
- **Total Integrations:** 12

---

*This file is auto-generated from the integration manifest. Do not edit manually.*
