## Analyzers (1)

### MSExchangeOnline_GetInboxRules `v1.1`
List a mailbox's inbox rules via Microsoft Graph and flag rules commonly abused after a mailbox compromise/BEC: external auto-forwarding, silent delete/move rules, keyword filters on security or financial terms, hiding folders (RSS Feeds...), obfuscated rule names.

- **Author:** Fabien Bloume ,StrangeBee
- **License:** AGPL-V3
- **Data Types:** `mail`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/MSExchangeOnline/MSExchangeOnline_GetInboxRules.json)

---

## Responders (1)

### MSExchangeOnline_RemoveInboxRule `v1.0`
Removes a malicious Exchange Online inbox rule via Microsoft Graph. Reads the target mailbox UPN and Graph rule ID from a case custom field (name configurable, defaults to "inbox-rule-input"), formatted as "<mailboxUPN>|<ruleId>".

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `thehive:case`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSExchangeOnline/MSExchangeOnline_RemoveInboxRule.json)
