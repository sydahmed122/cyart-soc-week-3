\# Evidence Preservation and Analysis



\## Overview

Evidence preservation is a critical step in incident response and digital forensics. Proper handling ensures that collected data remains intact, verifiable, and legally admissible if required. SOC analysts must preserve both volatile and non-volatile evidence while maintaining chain of custody.



---



\## Volatile Data Collection



Volatile data such as active network connections and running processes was prioritized for collection.



\*\*Collection Method (simulated):\*\*

\- Tool: Velociraptor (conceptual workflow)

\- Query Used: `SELECT \* FROM netstat`

\- Output Format: CSV



\### Observation

Active outbound connections were reviewed to identify suspicious communication patterns.



---



\## Memory Acquisition



Memory capture was performed to preserve runtime artifacts.



\*\*Acquisition Details (simulated):\*\*

\- Artifact: Windows Memory Dump

\- Tool: Velociraptor Memory Acquisition

\- Hash Algorithm: SHA-256



---



\## Evidence Log



| Item        | Description       | Collected By | Date       | Hash Value        |

|-------------|-------------------|--------------|------------|-------------------|

| Memory Dump | Server-Y Memory   | SOC Analyst  | 2026-02-04 | `<SHA256\_HASH>`   |

| Netstat CSV | Active Connections| SOC Analyst  | 2026-02-04 | `<SHA256\_HASH>`   |



---



\## Chain of Custody Considerations



The following controls were maintained:



\- Evidence collected in read-only manner  

\- Hash values generated to ensure integrity  

\- Collection time documented  

\- Access restricted to authorized personnel  



---



\## Outcome



Proper evidence preservation ensures investigation reliability, supports forensic analysis, and maintains integrity for potential legal or compliance requirements.



