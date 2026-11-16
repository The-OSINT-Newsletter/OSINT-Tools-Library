---
description: >-
  Tool Description: A community-maintained security reference project
  documenting legitimate Windows binaries, scripts, and libraries that can be
  abused by attackers to carry out malicious activity.
---

# LOLBAS

| **LOLBAS**       | **Quick Overview**                                                                                                                                                                                     |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| URL              | [https://lolbas-project.github.io/](https://lolbas-project.github.io/)                                                                                                                                 |
| What it does     | Documents Windows binaries, scripts and libraries that can be abused for activities such as code execution, file operations, persistence, privilege escalation and security-control evasion.           |
| How to use it    | Search or browse the catalogue by component, function or MITRE ATT\&CK technique. Review individual entries and their documented behaviour, then compare them with suspicious activity or system logs. |
| Cost             | Free.                                                                                                                                                                                                  |
| Account required | No to browse or use the public data.                                                                                                                                                                   |
| Cookies          | Google Analytics 4 (GA4) analytics cookies.                                                                                                                                                            |
| Ownership        | Community-driven open-source project maintained by volunteer contributors.                                                                                                                             |
| Use in Reporting | Explaining suspicious Windows processes, identifying potential living-off-the-land techniques, researching attacker behaviour, and supporting technical analysis of cyber incidents.                   |

### What does LOLBAS do?

LOLBAS documents legitimate Windows components that have functionality beyond their ordinary intended use and could be exploited by attackers.

For example, a Windows executable designed for a legitimate administrative or system-management task may also be capable of executing code, downloading files, launching other processes or helping an attacker evade security controls.

The catalogue provides information about these components, including:

* Their names and legitimate Windows functionality.
* The unexpected or potentially abusive functionality they provide.
* Examples of relevant behaviours and use cases.
* Associated MITRE ATT\&CK techniques.
* References to research and other technical resources.

It covers binaries, scripts and libraries, with individual entries maintained in structured YAML files.

**The lowdown:** It essentially helps users understand which Windows components may be misused and what suspicious behaviour to look for.

### How to Use:

**1. Browse the listed Windows binaries, scripts and libraries. Look for a particular component or explore the different functions and MITRE ATT\&CK techniques.**

<img src="../.gitbook/assets/unknown (837).png" alt="" height="385" width="602">

**2. Open the relevant entry and review its legitimate purpose, documented functionality, associated commands, use cases and ATT\&CK mappings. Pay attention to how the component could be misused and what behaviour might be suspicious.**

<img src="../.gitbook/assets/unknown (838).png" alt="" height="416" width="602">

<img src="../.gitbook/assets/unknown (839).png" alt="" height="137" width="602">

**3. Compare findings with Windows event logs, process execution records, command-line activity, endpoint telemetry or other evidence collected during an investigation.**&#x20;

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

No account required to browse or use the public data.

### Cookies:&#x20;

Only Google Analytics 4 (GA4) analytics cookies were noted.

### Use in Reporting

LOLBAS is useful for:

* Understanding how legitimate Windows binaries, scripts and libraries can be misused during cyberattacks.
* Explaining why a seemingly ordinary Windows process may be relevant to a security investigation.
* Identifying potential living-off-the-land techniques in suspicious process and command-line activity.
* Researching how attackers may execute code, download files or establish persistence using existing Windows components.
* Investigating possible attempts to bypass application controls, elevate privileges or evade security monitoring.
* Comparing suspicious system activity with documented MITRE ATT\&CK techniques.
* Supporting the analysis of malware behaviour and Windows endpoint activity.
* Identifying investigative leads when examining unusual executable activity or unexpected parent-child process relationships.
* Supporting technical explanations of attacker techniques in cybersecurity reports and incident investigations.
* Providing background research for threat intelligence, digital forensics and defensive security reporting.

As a working example, security researcher Xavier Mertens described investigating a malicious script and used LOLBAS as a starting point for examining suspicious Windows process activity. [The article ](https://isc.sans.edu/diary/New%2BTool%2Bto%2BAdd%2Bto%2BYour%2BLOLBAS%2BList%2Bcvtresexe/27892/)discusses how cvtres.exe and other native utilities can be involved in malicious execution.

| **Capabilities**                                                              | **Limitations**                                                                                        |
| ----------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| Documents potentially abusive functionality in legitimate Windows components. | Does not scan computers or identify malicious activity automatically.                                  |
| Covers binaries, scripts and libraries.                                       | Focuses on Windows and does not provide a complete cross-platform catalogue.                           |
| Maps documented functionality to MITRE ATT\&CK techniques.                    | An ATT\&CK mapping does not prove that a particular technique occurred in an investigation.            |
| Provides structured JSON, CSV and YAML data.                                  | Users may need technical knowledge to interpret entries and analyse the data.                          |
| Supports research into attacker behaviour and defensive detection.            | The catalogue is not exhaustive, and documented entries may not cover every possible use or variation. |

### Summary

LOLBAS is a valuable open-source reference for understanding how legitimate Windows components can be repurposed for malicious activity. It best fits in the verification and analysis stages of the OSINT workflow when you already have some evidence of suspicious Windows activity and need to understand what it might mean.&#x20;

However, it’s not a malware scanner or an attribution tool. A component appearing in the catalogue does not establish that it has been used maliciously.&#x20;

### Ownership

The platform is a community-driven open-source project maintained by volunteer contributors.

The project's GitHub repository identifies maintainers including Oddvar Moe, Jimmy Bayne, Conor Richard, Chris Spehn, Liam, Wietze and Jose Hernandez.

### Ethical Considerations

* Use the catalogue for legitimate security research, incident response, education and defensive analysis.
* Do not assume that the presence of a documented Windows component proves malicious activity.
* Remember that many listed components have legitimate administrative and operational uses.
* Conduct any testing in a controlled environment with permission from the system owner.
* Avoid using the documented techniques to bypass security controls or gain unauthorised access.
* Be aware that the catalogue is not exhaustive and that the absence of an entry does not establish that a process or technique is safe.

### Related Tools:

* GTFOBins
* MITRE ATTACK
* Atomic Red Team

#### Sources

[https://lolbas-project.github.io/](https://lolbas-project.github.io/)&#x20;

[https://github.com/LOLBAS-Project/LOLBAS](https://github.com/LOLBAS-Project/LOLBAS)&#x20;

[https://lolbas-project.github.io/api/](https://lolbas-project.github.io/api/)&#x20;

[https://www.secuinfra.com/en/glossary/lolbas-lolbins/](https://www.secuinfra.com/en/glossary/lolbas-lolbins/) [https://isc.sans.edu/diary/New%2BTool%2Bto%2BAdd%2Bto%2BYour%2BLOLBAS%2BList%2Bcvtresexe/27892/](https://isc.sans.edu/diary/New%2BTool%2Bto%2BAdd%2Bto%2BYour%2BLOLBAS%2BList%2Bcvtresexe/27892/)&#x20;
