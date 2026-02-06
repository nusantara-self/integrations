# Watcher


## Analyzers (1)

### Watcher_Check `v1.0`
Check if a domain is monitored in Watcher (Legitimate Domain and/or Website Monitoring modules) and retrieve all details.

- **Author:** THA-CERT // YNE
- **License:** AGPL-V3
- **Data Types:** `domain`
- **Configuration:** [.upstream/cortex/analyzers/Watcher/Watcher_Check.json](https://github.com/nusantara-self/strangebee-integrations/blob/main/.upstream/cortex/analyzers/Watcher/Watcher_Check.json) ([raw](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/main/.upstream/cortex/analyzers/Watcher/Watcher_Check.json))

---

## Responders (4)

### Watcher_Transfer `v1.1`
Transfer domain between Watcher modules. Required tag: watcher:module=LegitDomain|WebsiteMonitoring (DESTINATION module). Transfer TO LegitDomain: watcher:repurchased=Yes/No (required), watcher:contact=email (optional). Transfer TO WebsiteMonitoring: watcher:legitimacy=2-6 (required), watcher:takedown_request=Yes/No, watcher:legal_team=Yes/No, watcher:blocking_request=Yes/No

- **Author:** THA-CERT // YNE
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [.upstream/cortex/responders/Watcher/Watcher_Transfer.json](https://github.com/nusantara-self/strangebee-integrations/blob/main/.upstream/cortex/responders/Watcher/Watcher_Transfer.json) ([raw](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/main/.upstream/cortex/responders/Watcher/Watcher_Transfer.json))

### Watcher_Remove `v1.1`
Remove domain from Watcher. Required tag: watcher:module=LegitDomain|WebsiteMonitoring

- **Author:** THA-CERT // YNE
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [.upstream/cortex/responders/Watcher/Watcher_Remove.json](https://github.com/nusantara-self/strangebee-integrations/blob/main/.upstream/cortex/responders/Watcher/Watcher_Remove.json) ([raw](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/main/.upstream/cortex/responders/Watcher/Watcher_Remove.json))

### Watcher_Update `v1.1`
Update domain in Watcher. Required tags: watcher:module=LegitDomain|WebsiteMonitoring. For LegitDomain: watcher:repurchased=Yes/No, watcher:contact=email (optional). For WebsiteMonitoring: watcher:legitimacy=2-6, watcher:takedown_request=Yes/No, watcher:legal_team=Yes/No, watcher:blocking_request=Yes/No

- **Author:** THA-CERT // YNE
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [.upstream/cortex/responders/Watcher/Watcher_Update.json](https://github.com/nusantara-self/strangebee-integrations/blob/main/.upstream/cortex/responders/Watcher/Watcher_Update.json) ([raw](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/main/.upstream/cortex/responders/Watcher/Watcher_Update.json))

### Watcher_Add `v1.1`
Add domain to Watcher. Required tags: watcher:module=LegitDomain|WebsiteMonitoring. For LegitDomain: watcher:repurchased=Yes/No (required), watcher:contact=email (optional). For WebsiteMonitoring: watcher:legitimacy=2-6 (required), watcher:takedown_request=Yes/No, watcher:legal_team=Yes/No, watcher:blocking_request=Yes/No

- **Author:** THA-CERT // YNE
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [.upstream/cortex/responders/Watcher/Watcher_Add.json](https://github.com/nusantara-self/strangebee-integrations/blob/main/.upstream/cortex/responders/Watcher/Watcher_Add.json) ([raw](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/main/.upstream/cortex/responders/Watcher/Watcher_Add.json))

---

## Statistics

- **Total Analyzers:** 1
- **Total Responders:** 4
- **Total Functions:** 0
- **Total External Integrations:** 0
- **Total Integrations:** 5

---

*This file is auto-generated from the integration manifest. Do not edit manually.*
