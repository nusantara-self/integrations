## Analyzers (2)

### ZscalerZIA_URLLookup `v1.0`
Query Zscaler Internet Access for URL categorization and security classification. Supports OneAPI OAuth2 and legacy authentication.

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `domain`, `fqdn`, `url`, `ip`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/Zscaler/ZscalerZIA_URLLookup.json)

### Zscaler `v1.3`
Check Zscaler category for a domain, fqdn, IP address or FQDN. This analyzer requires a paid subscription to Zscaler ZIA

- **Author:** Simon Lavigne, Mikael Keri
- **License:** AGPL-V3
- **Data Types:** `ip`, `domain`, `url`, `fqdn`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/Zscaler/Zscaler.json)

---

## Responders (12)

### ZscalerZIA_AddToURLCategoryWildcard `v1.0`
Add a domain and all its subdomains to a custom ZIA URL category

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/Zscaler/ZscalerZIA_AddToURLCategoryWildcard.json)

### ZscalerZIA_RemoveFromATPDenylist `v1.0`
Remove domains, FQDNs and URLs from the ZIA ATP Denylist (Policy > Security > Advanced Threat Protection > Blocked Malicious URLs)

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/Zscaler/ZscalerZIA_RemoveFromATPDenylist.json)

### ZscalerZIA_AddToATPDenylist `v1.0`
Block domains, FQDNs and URLs in the ZIA ATP Denylist (Policy > Security > Advanced Threat Protection > Blocked Malicious URLs)

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/Zscaler/ZscalerZIA_AddToATPDenylist.json)

### ZscalerZIA_AddToURLCategory `v1.0`
Add observables (domain, fqdn, url, ip, cidr) to a custom ZIA URL category

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/Zscaler/ZscalerZIA_AddToURLCategory.json)

### ZscalerZIA_RemoveFromURLCategory `v1.0`
Remove observables (domain, fqdn, url, ip, cidr) from a custom ZIA URL category

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/Zscaler/ZscalerZIA_RemoveFromURLCategory.json)

### ZscalerZIA_AddToCloudFirewallRule `v1.0`
Add an IP address or CIDR to the destination address list of a ZIA Cloud Firewall rule - network-layer block, all ports/protocols (Policy > Cloud Firewall)

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/Zscaler/ZscalerZIA_AddToCloudFirewallRule.json)

### ZscalerZIA_AddToATPSecurityExceptions `v1.0`
Add domains, FQDNs and URLs to ZIA Security Exceptions - bypasses ATP content scanning (Policy > Security > Advanced Threat Protection > Security Exceptions)

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/Zscaler/ZscalerZIA_AddToATPSecurityExceptions.json)

### ZscalerZIA_AddToATPDenylistWildcard `v1.0`
Block a domain and all its subdomains in the ZIA ATP Denylist (Policy > Security > Advanced Threat Protection > Blocked Malicious URLs)

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/Zscaler/ZscalerZIA_AddToATPDenylistWildcard.json)

### ZscalerZIA_RemoveFromATPSecurityExceptions `v1.0`
Remove domains, FQDNs and URLs from ZIA Security Exceptions (Policy > Security > Advanced Threat Protection > Security Exceptions)

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/Zscaler/ZscalerZIA_RemoveFromATPSecurityExceptions.json)

### ZscalerZIA_RemoveFromURLCategoryWildcard `v1.0`
Remove a domain and all its subdomains from a custom ZIA URL category

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/Zscaler/ZscalerZIA_RemoveFromURLCategoryWildcard.json)

### ZscalerZIA_RemoveFromCloudFirewallRule `v1.0`
Remove an IP address or CIDR from the destination address list of a ZIA Cloud Firewall rule - network-layer block, all ports/protocols (Policy > Cloud Firewall)

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/Zscaler/ZscalerZIA_RemoveFromCloudFirewallRule.json)

### ZscalerZIA_RemoveFromATPDenylistWildcard `v1.0`
Remove a domain and all its subdomains from the ZIA ATP Denylist (Policy > Security > Advanced Threat Protection > Blocked Malicious URLs)

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/Zscaler/ZscalerZIA_RemoveFromATPDenylistWildcard.json)
