\# Incident Escalation Workflows



\## Overview

Incident escalation ensures that security events are handled by the appropriate SOC tier based on severity, complexity, and potential business impact. Proper escalation improves response time and ensures efficient use of SOC resources.



---



\## SOC Tier Responsibilities



\*\*Tier 1 – Triage\*\*

\- Monitor alerts

\- Perform initial validation

\- Gather basic evidence

\- Escalate when required



\*\*Tier 2 – Investigation\*\*

\- Deep log analysis

\- Threat hunting

\- Scope determination

\- Containment actions



\*\*Tier 3 – Advanced Response\*\*

\- Malware analysis

\- Reverse engineering

\- Advanced forensics

\- Detection engineering improvements



---



\## Escalation Criteria



An alert is escalated from Tier 1 to Tier 2 when:



\- High or Critical severity

\- Confirmed malicious indicators

\- Lateral movement suspected

\- Privileged account involvement

\- Potential data exfiltration



---



\## Escalation Simulation



\*\*Alert:\*\* Unauthorized Access on Server-Y  

\*\*Severity:\*\* High  

\*\*Source IP:\*\* 192.168.1.200  

\*\*MITRE Technique:\*\* T1078 – Valid Accounts  



\### Tier 1 Actions

\- Alert validated as true positive  

\- Initial log review completed  

\- Source IP flagged as suspicious  

\- Incident escalated to Tier 2  



---



\## Tier 2 Escalation Summary (SITREP)



\*\*Title:\*\* Unauthorized Access Investigation – Server-Y  



\*\*Summary:\*\*  

A high-severity alert indicating potential misuse of valid credentials was detected on Server-Y. Initial triage confirmed suspicious authentication activity originating from IP 192.168.1.200. No confirmed lateral movement observed at this stage. The case has been escalated for deeper investigation and containment.



\*\*Recommended Actions:\*\*

\- Review authentication logs

\- Check for lateral movement

\- Monitor privileged accounts

\- Consider temporary access restrictions



---



\## Outcome



A structured escalation workflow ensures timely investigation of high-risk incidents and improves coordination between SOC tiers.



