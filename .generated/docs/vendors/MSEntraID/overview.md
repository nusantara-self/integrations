## Analyzers (7)

### MSEntraID_GetRiskyUser `v1.0`
Retrieve Microsoft Entra ID Identity Protection risk information for a user: current risk state (riskyUsers) and risk detection history (riskDetections). Requires Entra ID P1/P2.

- **Author:** StrangeBee
- **License:** AGPL-V3
- **Data Types:** `mail`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/MSEntraID/MSEntraID_GetRiskyUser.json)

### MSEntraID_GetDirectoryAuditLogs `v1.0`
Pull Microsoft Entra ID directory audit logs for a user within the specified timeframe.

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `mail`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/MSEntraID/MSEntraID_GetDirectoryAuditLogs.json)

### MSEntraID_GetSignIns `v1.0`
Pull all Microsoft Entra ID sign ins for a user within the specified amount of time.

- **Author:** @jahamilto
- **License:** AGPL-V3
- **Data Types:** `mail`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/MSEntraID/MSEntraID_GetSignIns.json)

### MSEntraID_GetSignInsByIP `v1.0`
Pull all Microsoft Entra ID sign ins across the tenant that originated from a given IP address, within the specified amount of time.

- **Author:** 3lina, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `ip`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/MSEntraID/MSEntraID_GetSignInsByIP.json)

### MSEntraID_GetDirectoryRoles `v1.0`
List the Microsoft Entra ID directory roles (built-in admin roles) directly assigned to a user, to help prioritize investigations involving privileged accounts.

- **Author:** 3lina, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `mail`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/MSEntraID/MSEntraID_GetDirectoryRoles.json)

### MSEntraID_GetUserInfo `v1.0`
Get information about the user from Microsoft Entra ID, using mail or user identifier (UPN/sAMAccountName/employeeId)

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `mail`, `other`, `user`, `username`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/MSEntraID/MSEntraID_GetUserInfo.json)

### MSEntraID_GetManagedDevicesInfo `v1.0`
Get Microsoft Intune Managed Device(s) Details from hostname or mail

- **Author:** Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `mail`, `hostname`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/analyzers/MSEntraID/MSEntraID_GetManagedDevicesInfo.json)

---

## Responders (5)

### MSEntraID_enableUser `v1.0`
Enable user in Microsoft Entra ID for a User Principal Name. (mail)

- **Author:** nusatanra-self, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSEntraID/MSEntraID_enableUser.json)

### MSEntraID_ForcePasswordReset `v1.0`
Force password reset at next login for a User Principal Name. (mail)

- **Author:** nusatanra-self, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSEntraID/MSEntraID_ForcePasswordReset.json)

### MSEntraID_ForcePasswordResetWithMFA `v1.0`
Force password reset at next login with MFA verification before password change for a User Principal Name. (mail)

- **Author:** nusatanra-self, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSEntraID/MSEntraID_ForcePasswordResetWithMFA.json)

### MSEntraID_disableUser `v1.0`
Disable user in Microsoft Entra ID for a User Principal Name. (mail)

- **Author:** nusatanra-self, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSEntraID/MSEntraID_disableUser.json)

### MSEntraID_revokeSignInSessions `v1.1`
Invalidates all the refresh tokens issued to applications for a Microsoft Entra ID user (as well as session cookies in a user's browser)

- **Author:** Daniel Weiner @dmweiner; revised by @jahamilto; Fabien Bloume, StrangeBee
- **License:** AGPL-V3
- **Data Types:** `thehive:case_artifact`
- **Configuration:** [View config](https://github.com/TheHive-Project/Cortex-Analyzers/blob/master/responders/MSEntraID/MSEntraID_revokeSignInSessions.json)
