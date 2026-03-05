## Analyzers (1)

### Proofpoint_Lookup `v1.0`
Check URL, file, SHA256 against Proofpoint forensics

- **Author:** Emmanuel Torquato
- **License:** AGPL-V3
- **Data Types:** `url`, `file`, `hash`
- **Configuration:** [.upstream/cortex/analyzers/Proofpoint/ProofPoint_Lookup.json](https://github.com/nusantara-self/strangebee-integrations/blob/main/.upstream/cortex/analyzers/Proofpoint/ProofPoint_Lookup.json) ([raw](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/main/.upstream/cortex/analyzers/Proofpoint/ProofPoint_Lookup.json))

---

## Functions (2)

### alertFeeder_ProofPoint_messageDelivered `v1.0.0`
Ingests ProofPoint messageDelivered alerts in TheHive

- **Kind:** function
- **Mode:** Enabled
- **File:** [integrations/vendors/Proofpoint/thehive/functions/function_Feeder_alertFromProofpoint_messageDelivered.js](https://github.com/nusantara-self/strangebee-integrations/blob/main/integrations/vendors/Proofpoint/thehive/functions/function_Feeder_alertFromProofpoint_messageDelivered.js) ([raw](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/main/integrations/vendors/Proofpoint/thehive/functions/function_Feeder_alertFromProofpoint_messageDelivered.js))

### alertFeeder_ProofPoint_clicksPermitted `v1.0.0`
Ingests ProofPoint clicksPermitted alerts in TheHive

- **Kind:** function
- **Mode:** Enabled
- **File:** [integrations/vendors/Proofpoint/thehive/functions/function_Feeder_alertFromProofpoint_clicksPermitted.js](https://github.com/nusantara-self/strangebee-integrations/blob/main/integrations/vendors/Proofpoint/thehive/functions/function_Feeder_alertFromProofpoint_clicksPermitted.js) ([raw](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/main/integrations/vendors/Proofpoint/thehive/functions/function_Feeder_alertFromProofpoint_clicksPermitted.js))

---

## Use Cases (2)

### Ingest Proofpoint MessagesDelivered Events into TheHive Using an Alert Feeder
Ingest Proofpoint TAP messagesDelivered events as TheHive alerts to track and respond to threats that have reached user mailboxes and may require investigation.

- **License required:** Platinum
- **TheHive version required:** 5.5+
- **Documentation:** [integrations/vendors/Proofpoint/use-cases/alert-ingestion-messageDelivered.md](https://github.com/nusantara-self/strangebee-integrations/blob/main/integrations/vendors/Proofpoint/use-cases/alert-ingestion-messageDelivered.md)
- **Related:** `integrations/vendors/Proofpoint/thehive/functions/function_Feeder_alertFromProofpoint_MessageDelivered.js`

---

### Ingest Proofpoint ClicksPermitted Events into TheHive Using an Alert Feeder
Ingest Proofpoint TAP clicksPermitted events as TheHive alerts to track and respond to users who clicked on malicious links that were not blocked by Proofpoint and may require investigation.

- **License required:** Platinum
- **TheHive version required:** 5.5+
- **Documentation:** [integrations/vendors/Proofpoint/use-cases/alert-ingestion-clicksPermitted.md](https://github.com/nusantara-self/strangebee-integrations/blob/main/integrations/vendors/Proofpoint/use-cases/alert-ingestion-clicksPermitted.md)
- **Related Function:** [alertFeeder_ProofPoint_clicksPermitted](https://github.com/nusantara-self/strangebee-integrations/blob/main/integrations/vendors/Proofpoint/thehive/functions/function_Feeder_alertFromProofpoint_clicksPermitted.js)
