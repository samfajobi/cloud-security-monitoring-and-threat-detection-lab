#  SentinelOne

## Role: Third-party Endpoint Detection & Response

### Used for:

  * Endpoint malware detection

  * Behavioral threat analysis

  * Providing external security signals to Sentinel

Key outputs:

  * Endpoint alerts

  * Remediation actions



### How They Work Together

In many organizations, SentinelOne and Microsoft Sentinel are used together:

  * SentinelOne detects malicious activity on an endpoint

  * Alert is forwarded to Microsoft Sentinel

  * Sentinel correlates it with:

     * Identity sign-ins

     * Network logs

     * Cloud activity

  * Automated response is triggered:

     * Disable user account

     * Create incident

     * Notify SOC teams

💡 SentinelOne provides signals
💡 Microsoft Sentinel provides context and orchestration
