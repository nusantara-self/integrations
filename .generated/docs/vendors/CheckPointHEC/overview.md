## Analyzers (5)

### CheckPointHEC_SearchByURL `v1.0`
Search for all emails containing a specific URL in Check Point Harmony Email & Collaboration and retrieve their security verdicts.

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `url`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/CheckPointHEC/CheckPointHEC_SearchByURL.json)

### CheckPointHEC_SearchByDomain `v1.0`
Search for all emails from a sender domain in Check Point Harmony Email & Collaboration. Accepts a domain observable or an .eml file (sender domain is extracted automatically, with forwarded email support).

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `domain`, `file`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/CheckPointHEC/CheckPointHEC_SearchByDomain.json)

### CheckPointHEC_SearchEmail `v1.0`
Search for an email in Check Point Harmony Email & Collaboration and retrieve its security verdict, phishing confidence, classification and scan results. Accepts an .eml file or a Message-ID as an 'other' observable.

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `file`, `other`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/CheckPointHEC/CheckPointHEC_SearchEmail.json)

### CheckPointHEC_SearchBySender `v1.0`
Search for all emails from a sender address in Check Point Harmony Email & Collaboration. Accepts a mail observable or an .eml file (sender is extracted automatically, with forwarded email support).

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `mail`, `file`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/CheckPointHEC/CheckPointHEC_SearchBySender.json)

### CheckPointHEC_SearchBySenderIP `v1.0`
Search for all emails from a sender IP in Check Point Harmony Email & Collaboration. Accepts an IP observable or an .eml file (sender IP is extracted from Received headers, with forwarded email support).

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `ip`, `file`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/CheckPointHEC/CheckPointHEC_SearchBySenderIP.json)
