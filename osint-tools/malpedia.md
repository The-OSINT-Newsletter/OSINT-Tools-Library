---
description: >-
  Tool Description: A curated malware intelligence platform used to identify
  malware families, research samples, actors and related technical information.
---

# Malpedia

| **Tool name**    | **Quick Overview**                                                                                                                                                                     |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://malpedia.caad.fkie.fraunhofer.de/](https://malpedia.caad.fkie.fraunhofer.de/)                                                                                                 |
| What it does     | Identifies and contextualises malware families, samples, actors and technical indicators.                                                                                              |
| How to use it    | Search for a malware name, family, actor or sample hash and review associated intelligence and references.                                                                             |
| Cost             | Free.                                                                                                                                                                                  |
| Account required | No for basic public information. Yes for some restricted data and samples.                                                                                                             |
| Cookies          | A CSRF protection cookie used by Malpedia.                                                                                                                                             |
| Ownership        | Operated and maintained by Daniel Plohmann & Steffen Enders under the umbrella of the Fraunhofer Institute for Communication, Information Processing and Ergonomics (FKIE) in Germany. |
| Use in Reporting | Supports malware identification, attribution/contextualisation and corroboration of technical findings.                                                                                |

### What does Malpedia do?

Malpedia is a curated malware intelligence resource designed to support the quick identification and contextualisation of malware. It maintains information on malware families, samples, actors, references and detection rules.

It can prove particularly useful when you have a malware name, file hash, YARA match or technical indicator and need to establish what malware family it may relate to.&#x20;

**The lowdown:** It provides structured information linking malware families with samples, aliases, threat actors, references and detection content.&#x20;

### How to Use:

**1. Search for the malware family, actor, sample hash or other relevant identifier using Malpedia's search functionality.**

<img src="../.gitbook/assets/unknown (575).png" alt="" height="151" width="602">

**2. Review the associated family information, aliases, actors, references, samples and available detection material.**&#x20;

<img src="../.gitbook/assets/unknown (576).png" alt="" height="325" width="602">

**3. Compare the Malpedia information against other sources such as VirusTotal, MalwareBazaar, YARA, MISP or vendor threat-intelligence reports before drawing conclusions.**&#x20;

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

No for basic public information. Yes for some restricted data and samples.&#x20;

### Cookies:&#x20;

The site uses a csrftoken cookie for CSRF protection and website security. It is a functional security cookie rather than an advertising or analytics cookie.

### Use in Reporting

Malpedia can be used to:

* Identify and contextualise malware families associated with a sample or technical indicator.
* Establish aliases and relationships between malware families and threat actors.
* Corroborate malware identification obtained from other security or OSINT sources.
* Document malware references, family information, hashes and relevant detection material.
* Support analysis of malware campaigns, intrusion activity and suspected threat actors.
* Provide supporting technical context when explaining malware findings in an investigative report.
* Reference established malware classifications while clearly distinguishing them from an investigator's own assessment.

As an example, during [CERT Polaska’s analysis](https://cert.pl/en/posts/2026/02/fake-captcha-in-action/) of a Latrodectus sample, it was stated that the sample matched a Malpedia YARA rule (win\_latrodectus\_g0) shared by SWITCH.&#x20;

| **Capabilities**                                                           | **Limitations**                                                                                  |
| -------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| Identifies and categorises malware families.                               | Not every malware sample or family will be present.                                              |
| Provides malware aliases and associated threat-actor information.          | Family attribution can change as new research becomes available.                                 |
| Provides references supporting malware and actor relationships.            | Some information and samples require an account.                                                 |
| Provides YARA rules and other technical resources for supported families.  | Detection rules should not automatically be treated as proof that a sample belongs to a family.  |
| Supports searches through its web interface and API.                       | Some entries contain limited information or incomplete references.                               |
| Provides structured malware intelligence for research and investigation.   | <p><br></p>                                                                                      |

### Summary

Malpedia fits best in the identification, enrichment, analysis, and verification stages of the OSINT workflow. It’s particularly useful for linking malware to families, aliases, actors, references and detection rules, but findings should be corroborated with other technical and intelligence sources.

### Ownership

Operated and maintained by researchers [Daniel Plohmann](https://www.linkedin.com/in/daniel-plohmann/) and Steffen Enders under the umbrella of the Fraunhofer Institute for Communication, Information Processing and Ergonomics (FKIE) in Germany. It functions as a collaborative, invite-only resource for tracking and analysing malware families.&#x20;

### Ethical Considerations

* Treat Malpedia classifications as intelligence to be assessed, not definitive attribution.
* Don’t download or execute malware samples unless authorised and using appropriate isolated infrastructure.
* Avoid exposing sensitive investigation data when submitting hashes or indicators to external services.
* Consider applicable organisational security, data-protection and information-handling requirements.
* Corroborate malware-family or actor attribution with independent sources before reporting it as fact.

### Related Tools:

* [VirusTotal](virustotal.md)
* MalwareBazaar
* URLhaus
* MISP

#### Sources

[https://malpedia.caad.fkie.fraunhofer.de/](https://malpedia.caad.fkie.fraunhofer.de/)&#x20;

[https://cert.pl/en/posts/2026/02/fake-captcha-in-action/](https://cert.pl/en/posts/2026/02/fake-captcha-in-action/)&#x20;

[https://hunt.io/blog/interview-daniel-plohmann-malpedia-malware-analysis](https://hunt.io/blog/interview-daniel-plohmann-malpedia-malware-analysis)&#x20;

[https://www.linkedin.com/in/daniel-plohmann/](https://www.linkedin.com/in/daniel-plohmann/)&#x20;
