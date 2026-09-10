---
description: >-
  Tool Description: An online threat intelligence platform that aggregates over
  70 antivirus scanners and blocklisting services to analyse suspicious files,
  URLs, domains, and IP addresses.
---

# VirusTotal

| **VirusTotal**   | **Quick Overview**                                                                                                                          |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://www.virustotal.com/gui/home/upload](https://www.virustotal.com/gui/home/upload)                                                    |
| What it does     | Analyses files, URLs, domains and IP addresses using multiple security engines and threat-intelligence sources.                             |
| How to use it    | Search an indicator/upload a file/URL and review the resulting detections, metadata, relationships and historical information.              |
| Cost             | Partially Free. (Basic use is free, premium services & higher limits are paid.)                                                             |
| Account required | No for basic website searches; Yes for full functionality.                                                                                  |
| Cookies          | A mixture of Google account/service cookies and a VirusTotal preference cookie.                                                             |
| Ownership        | Owned and operated by Google's cybersecurity business; Chronicle, following Google's acquisition in 2012.                                   |
| Use in Reporting | Can provide supporting evidence when assessing whether files, URLS, domains, or IP addresses have been associated with malicious activity.  |

### What does VirusTotal do?

VirusTotal aggregates information from numerous antivirus engines, website scanners, file-analysis systems, and user contributions to help identify potentially malicious files, URLs, and other indicators. It can also provide contextual information such as metadata, detection history, and relationships between indicators.&#x20;

**The lowdown:** It’s a useful technical verification and enrichment tool for investigating potentially malicious files, URLs, domains, IP addresses etc.

### How to Use:

**1. Search for a target indicator using VirusTotal, or upload the relevant file/URL where appropriate.**

<img src="../.gitbook/assets/unknown (580).png" alt="" height="287" width="602">

**2. Simply review detections, metadata, historical results and related indicators, then corroborate significant findings with additional sources before including them in reporting.**

<img src="../.gitbook/assets/unknown (581).png" alt="" height="287" width="602">

<img src="../.gitbook/assets/unknown (582).png" alt="" height="703" width="602">

### Cost

* [ ] Free
* [x] Partially Free
* [ ] Paid

Basic use is free. Premium services and higher limits are paid.

## Data Processing

### Account Required:

* [x] Yes
* [x] No

No for basic website searches although an account is required for some features, including the API.

### Cookies:&#x20;

VirusTotal uses functional cookies to maintain site functionality, preferences and user sessions. The site may also load third-party Google services that set Google-domain cookies such as APISID, HSID, NID, SAPISID, SID and SSID. VT\_PREFERRED\_LANGUAGE is a VirusTotal preference cookie storing the selected interface language.

### Use in Reporting

VirusTotal can be used to:

* Assess whether a file, URL, domain, or IP address has been detected by multiple security engines.
* Identify malware names, detection classifications, and associated technical indicators.
* Review historical analysis and detection information associated with an indicator.
* Identify relationships between files, domains, URLs, IP addresses, and other technical artefacts.
* Cross-reference technical indicators identified through other OSINT or investigative sources.
* Support the assessment of whether a suspicious file, website, or infrastructure warrants further investigation.
* Corroborate technical findings obtained from other cybersecurity and threat-intelligence sources.
* Support malware, phishing, infrastructure and incident investigations.

As a real-world example, a 2024 joint advisory by the FBI/CISA/NSA on Russian military cyber actors (Unit 29155) states that the actors used VirusTotal to obtain subdomains for target websites. You can[ view the full report here.](https://www.cisa.gov/sites/default/files/2024-09/aa24-249a-russian-military-cyber-actors-target-us-and-global-critical-infrastructure.pdf)

| **Capabilities**                                               | **Limitations**                                                       |
| -------------------------------------------------------------- | --------------------------------------------------------------------- |
| Multi-engine analysis of files and URLs.                       | Individual detections can be false positives or false negatives.      |
| Searchable information on domains, IPs, URLs and file hashes.  | Coverage depends on the available engines and data sources.           |
| Provides technical metadata and contextual information.        | Results can change as vendors update their detections.                |
| Can reveal relationships between technical indicators.         | Some advanced intelligence and API capabilities require paid access.  |
| Useful for malware and phishing investigations.                | Standard submissions may enter VirusTotal's shared threat corpus.     |

### Summary

VirusTotal is particularly valuable when an investigator has already identified a suspicious technical artefact and wants to establish whether it has previously been detected, analysed or associated with other indicators.

However,l results should always be corroborated with other evidence and should not, by themselves, be treated as definitive proof that an individual, file, website or infrastructure is malicious.

### Ownership

VirusTotal is owned by Google (operating under Google's cybersecurity and threat intelligence umbrella via Chronicle). It was originally founded in 2004 by the Spanish security company Hispasec Sistemas before Google acquired it in September 2012.

### Ethical Considerations

* Treat VirusTotal detections as indicators, not definitive proof of maliciousness.
* Don’t upload confidential, personal or sensitive material to the standard public scanning service without appropriate authority.
* Consider whether a submission could expose information to VirusTotal users or security partners.
* Use Private Scanning where appropriate for material that shouldn’t enter the shared threat corpus.

### Related Tools:

* [Pulsedive](pulsedive.md)
* [Shodan](shodan.md)
* [Censys](censys.md)
* MalwareBazaar
* AlienVault OTX

#### Sources

[https://www.virustotal.com/gui/home/upload](https://www.virustotal.com/gui/home/upload)&#x20;

[https://en.wikipedia.org/wiki/VirusTotal](https://en.wikipedia.org/wiki/VirusTotal)

[https://www.linkedin.com/posts/virustotal-securemojo-googlecloud-share-7321528000607334402-m1ms/](https://www.linkedin.com/posts/virustotal-securemojo-googlecloud-share-7321528000607334402-m1ms/)&#x20;

[https://www.cisa.gov/sites/default/files/2024-09/aa24-249a-russian-military-cyber-actors-target-us-and-global-critical-infrastructure.pdf](https://www.cisa.gov/sites/default/files/2024-09/aa24-249a-russian-military-cyber-actors-target-us-and-global-critical-infrastructure.pdf)&#x20;
