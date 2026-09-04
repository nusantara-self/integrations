## Analyzers (2)

### MSDefenderForEndpoint_HashReputation `v1.0`
Check a file hash (SHA1 or SHA256) against Microsoft Defender for Endpoint: organization prevalence and related alerts.

- **Author:** Elina Galvao, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `hash`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/MSDefenderForEndpoint/MSDefenderForEndpoint_HashReputation.json)

### MSDefenderForEndpoint_DeviceLookup `v1.0`
Look up a device (by IP or hostname/FQDN) in Microsoft Defender for Endpoint: risk score, exposure level, health status and related alerts.

- **Author:** Elina Galvao, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `ip`, `fqdn`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/MSDefenderForEndpoint/MSDefenderForEndpoint_DeviceLookup.json)

---

## Responders (12)

### MSDefenderForEndpoint-UnisolateMachine `v1.0`
Unisolate machine with Microsoft Defender for Endpoints

- **Author:** Keijo Korte
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSDefenderForEndpoint/MSDefenderForEndpoint_Unisolate.json)

### MSDefenderForEndpoint-UnRestrictAppExecution `v1.0`
Enable execution of any application on the device

- **Author:** Keijo Korte, Louis-Maximilien Dupouy
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSDefenderForEndpoint/MSDefenderForEndpoint_UnRestrictAppExecution.json)

### MSDefenderForEndpoint-IsolateMachine `v1.0`
Isolate machine with Microsoft Defender for Endpoints

- **Author:** Keijo Korte
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSDefenderForEndpoint/MSDefenderForEndpoint_Isolate.json)

### MSDefenderForEndpoint-AutoInvestigation `v1.0`
Start an automated investigation on a device

- **Author:** Keijo Korte, Louis-Maximilien Dupouy
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSDefenderForEndpoint/MSDefenderForEndpoint_AutoInvestigation.json)

### MSDefenderForEndpoint-RestrictAppExecution `v1.0`
Restrict execution of all applications on the device except a predefined set

- **Author:** Keijo Korte, Louis-Maximilien Dupouy
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSDefenderForEndpoint/MSDefenderForEndpoint_RestrictAppExecution.json)

### MSDefenderForEndpoint-StopAndQuarantineFile `v1.0`
Stop execution of a file and delete it on every machine where it was seen (SHA1 hashes only)

- **Author:** Elina Galvao, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSDefenderForEndpoint/MSDefenderForEndpoint_StopAndQuarantineFile.json)

### MSDefenderForEndpoint-FullVirusScan `v1.0`
Run full virus scan to machine with Microsoft Defender for Endpoints

- **Author:** Keijo Korte
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSDefenderForEndpoint/MSDefenderForEndpoint_VirusScan.json)

### MSDefenderForEndpoint-PushIOC-Block `v2.1`
Push IOC to Defender client. Block mode

- **Author:** Keijo Korte, Louis-Maximilien Dupouy, Vito Piserchia
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSDefenderForEndpoint/MSDefenderForEndpoint_PushIOCBlock.json)

### MSDefenderForEndpoint-PushIOC-BlockAndRemediate `v1.0`
Push IOC to Defender client. Block and Remediate mode

- **Author:** Vito Piserchia
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSDefenderForEndpoint/MSDefenderForEndpoint_PushIOCBlockAndRemediate.json)

### MSDefenderForEndpoint-PushIOC-Warn `v1.0`
Push IOC to Defender client. Warn mode (Microsoft Defender for Cloud only)

- **Author:** Vito Piserchia
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSDefenderForEndpoint/MSDefenderForEndpoint_PushIOCWarn.json)

### MSDefenderForEndpoint-PushIOC-Allowed `v1.0`
Push IOC to Defender client. Allowed mode

- **Author:** Vito Piserchia
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSDefenderForEndpoint/MSDefenderForEndpoint_PushIOCAllowed.json)

### MSDefenderForEndpoint-PushIOC-Audit `v1.0`
Push IOC to Defender client. Audit mode

- **Author:** Vito Piserchia
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSDefenderForEndpoint/MSDefenderForEndpoint_PushIOCAudit.json)
