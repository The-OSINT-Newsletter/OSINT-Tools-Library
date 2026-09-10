---
description: >-
  Tool Description: A threat-intelligence and indicator-enrichment platform that
  allows users to investigate domains, IP addresses, and URL.
---

# Pulsedive

| **Pulsedive**    | **Quick Overview**                                                                                                                                                |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://pulsedive.com/](https://pulsedive.com/)                                                                                                                  |
| What it does     | Investigates and enriches indicators such as IP addresses, domains and URLs.                                                                                      |
| How to use it    | Search an indicator, review its risk score and associated intelligence, then pivot through related indicators, threats, DNS, WHOIS, certificates and other data.  |
| Cost             | Partially Free. Free tier available with paid Pro, API, Feed and Enterprise options.                                                                              |
| Account required | No for basic searching. Yes for additional features.                                                                                                              |
| Cookies          | A PHP session cookie used by Pulsedive itself.                                                                                                                    |
| Ownership        | Owned and founded by cybersecurity professionals Dan Sherry and Grace Chi, in New Jersey, USA.                                                                    |
| Use in Reporting | Useful for investigating and corroborating technical indicators and documenting relationships between domains, IPs, URLs, threats and infrastructure.             |

### What does Pulsedive do?

Pulsedive is used to research and enrich indicators of compromise (IOCs), including domains, IP addresses and URLs. It provides contextual information such as risk scores, WHOIS information, DNS records, location data, ports, protocols, HTTP information, SSL certificate metadata, redirects, related domains and linked threats. It also allows you to pivot between related indicators and threats.

**The lowdown:** It’s great for quickly enriching technical indicators and pivoting between related domains, IPs, infrastructure and threat intelligence in one place.&#x20;

### How to Use:

**1. Search for an indicator such as a domain, IP address or URL using the Pulsedive search function.**

<img src="../.gitbook/assets/unknown (583).png" alt="" height="205" width="602">

**2. Review the indicator's risk score, attributes, registration information, DNS data, technologies, certificates, related domains and other available intelligence.**&#x20;

<img src="../.gitbook/assets/unknown (584).png" alt="" height="271" width="602">

**3. Pivot to linked indicators, threats, feeds or associated infrastructure to develop and corroborate investigative leads. Pulsedive also supports searching across its dataset using queries and exporting results.**&#x20;

### Cost

* [ ] Free
* [x] Partially Free
* [ ] Paid

Free tier available with paid Pro, API, Feed and Enterprise options.

## Data Processing

### Account Required:

* [x] Yes
* [x] No

No for basic searching but an account is required for additional features and higher limits.&#x20;

### Cookies:&#x20;

The site uses a PHPSESSID first-party session cookie to maintain a user's session. The cookie contains a randomly generated session identifier and does not itself provide meaningful information about the user's identity or investigative activity.

### Use in Reporting

Pulsedive can be used to:

* Investigate domains, IP addresses and URLs associated with a subject or incident.
* Identify related infrastructure, domains, IP addresses and other technical indicators.
* Review risk scores and risk factors associated with an indicator.
* Cross-reference WHOIS, DNS, SSL certificate, HTTP and other technical information.
* Pivot from one indicator to associated threats and linked indicators.
* Identify technologies, ports, protocols and other characteristics associated with infrastructure.
* Corroborate technical information obtained from other OSINT and threat-intelligence sources.
* Inform further research by providing additional indicators that can be independently investigated.

The platform has been used in documented SOC operations, phishing investigations, domain-abuse research and published threat-intelligence reporting. Examples include [Cisco SOC operations](https://www.cisco.com/c/dam/en/us/products/collateral/security/rsac-2023-soc-findings-report.pdf?ccid=cc002757\&dtid=osolin001080\&oid=anrsc031827&) and [BSI's PhishQueue phishing investigation service](https://blog.pulsedive.com/enriched-real-time-phishing-management/).

| **Capabilities**                                                       | **Limitations**                                                                            |
| ---------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| Enriches domains, IP addresses and URLs with contextual intelligence.  | Coverage and accuracy depend on Pulsedive's available datasets and sources.                |
| Provides risk scores and risk factors.                                 | A risk score should not automatically be treated as proof that an indicator is malicious.  |
| Allows investigators to pivot between related indicators and threats.  | Some historical data and advanced functionality require paid access.                       |
| Provides DNS, WHOIS, SSL, HTTP and infrastructure information.         | Information can change over time and should be recorded with an observation date.          |
| Supports API access and structured exports including STIX/TAXII.       | Free accounts have usage and API limits.                                                   |

### Summary

Pulsedive best fits within analysis and verification within the OSINT workflow and is particularly useful for investigating suspicious domains, IP addresses and URLs and for pivoting between related infrastructure. As always, be mindful not to treat its scores or associations as conclusive evidence.

### Ownership

Owned and founded by cybersecurity professionals [Dan Sherry ](https://www.linkedin.com/in/netbroom/)(CEO) and [Grace Chi](https://www.linkedin.com/in/graceschi/) (Co-Founder & COO). They launched the threat intelligence platform as an independent, privately held startup based in New Jersey, USA.

### Ethical Considerations

* Do not treat Pulsedive risk scores as definitive proof of malicious activity.
* Be cautious when investigating infrastructure belonging to legitimate organisations, as shared hosting and compromised infrastructure can create misleading associations.
* Avoid unnecessarily interacting with suspicious infrastructure; passive information should generally be preferred where sufficient.
* Record the date and time of observations because technical infrastructure and risk assessments can change.
* Clearly distinguish between Pulsedive's assessment/data and conclusions independently reached by the investigator.

### Related Tools:

* [VirusTotal](virustotal.md)
* [Shodan](shodan.md)
* [Censys](censys.md)
* AlienVault OTX
* [URLscan](urlscan.md)

#### Sources

[https://pulsedive.com/](https://pulsedive.com/)&#x20;

[https://wellfound.com/company/pulsedive/people](https://wellfound.com/company/pulsedive/people)&#x20;

[crunchbase.com/organization/pulsedive](http://crunchbase.com/organization/pulsedive)&#x20;

[https://www.linkedin.com/company/pulsedive/](https://www.linkedin.com/company/pulsedive/)&#x20;

[https://www.linkedin.com/in/netbroom/](https://www.linkedin.com/in/netbroom/)&#x20;

[https://www.cisco.com/c/dam/en/us/products/collateral/security/rsac-2023-soc-findings-report.pdf?ccid=cc002757\&dtid=osolin001080\&oid=anrsc031827&](https://www.cisco.com/c/dam/en/us/products/collateral/security/rsac-2023-soc-findings-report.pdf?ccid=cc002757\&dtid=osolin001080\&oid=anrsc031827&)&#x20;

[https://blog.pulsedive.com/enriched-real-time-phishing-management/](https://blog.pulsedive.com/enriched-real-time-phishing-management/)&#x20;
