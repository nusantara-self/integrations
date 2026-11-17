## Analyzers (1)

### OVH_Domain_Check `v1.0`
Check if a domain name is available for purchase on OVH Cloud.

- **Author:** THA-CERT
- **License:** AGPL-V3
- **Data Types:** `domain`, `fqdn`, `url`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/OvhCloud/OvhDomainCheck.json)

---

## Responders (2)

### OVH_Domain_Order `v1.0`
Buy an available Domain Name on OVH Cloud.

- **Author:** THA-CERT
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/OvhCloud/OvhDomainOrder.json)

### OVH_Domain_Redirection `v1.0`
Redirect an owned Domain Name on OVH Cloud, to a specific URL.

- **Author:** THA-CERT
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/OvhCloud/OvhDomainRedirection.json)
