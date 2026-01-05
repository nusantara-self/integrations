# JAMF


## Functions (1)

### createAlertFromJAMFProtect `v1.0.0`
Ingests alerts from JAMF Protect. Extracts analytic details, host and user information, MITRE ATT&CK tags, and file/path data. The function constructs a TheHive alert, including a title, markdown-formatted description (with original alert JSON), relevant observables (IP, hostname, file, hash, URL, FQDN, URI path, user agent), MITRE ATT&CK enrichment, and a link to the JAMF alert. Handles default values and supports tagging and mapping of MITRE tactics for easier triage and investigation. For the setup in JAMF Protect, go to Configuration > Actions > *your action* > Add an HTTP data endpoint + your Authorization Header and Bearer as value

- **Kind:** function
- **Mode:** Enabled
- **File:** [integrations/vendors/JAMF/thehive/functions/function_API_createAlertFromJAMFProtect.js](https://github.com/nusantara-self/strangebee-integrations/blob/develop/integrations/vendors/JAMF/thehive/functions/function_API_createAlertFromJAMFProtect.js) ([raw](https://raw.githubusercontent.com/nusantara-self/strangebee-integrations/refs/heads/develop/integrations/vendors/JAMF/thehive/functions/function_API_createAlertFromJAMFProtect.js))

---

## Statistics

- **Total Analyzers:** 0
- **Total Responders:** 0
- **Total Functions:** 1
- **Total External Integrations:** 0
- **Total Integrations:** 1

---

*This file is auto-generated from the integration manifest. Do not edit manually.*
