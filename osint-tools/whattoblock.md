---
description: >-
  Tool Description: A web-based cyber threat-intelligence and network-security
  platform that helps analysts investigate IP addresses and network threats
  using observations from internet-facing sensors.
---

# Whattoblock

| **Whattoblock**  | **Quick Overview**                                                                                                                                                              |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://whatoblock.com/](https://whatoblock.com/)                                                                                                                              |
| What it does     | Searches sensor observations and explores threat data and IP blocklists.                                                                                                        |
| How to use it    | Create an account, search or filter IP records, and inspect related observations.                                                                                               |
| Cost             | Partially Free.                                                                                                                                                                 |
| Account required | Yes for live records and blocklist access.                                                                                                                                      |
| Cookies          | Cloudflare security, Google Analytics, browser-scope configuration and application session cookies.                                                                             |
| Ownership        | Whatoblock.com; founder [Stelios Pavlidis.](https://www.linkedin.com/in/steliospavlidis/)                                                                                       |
| Use in Reporting | Investigating suspicious IP addresses, scanning activity, botnet infrastructure, proxy networks, network reconnaissance and patterns of malicious/unsolicited internet traffic. |

### What does Whattoblock do?

Whattoblock is a cybersecurity threat intelligence platform that classifies unsolicited connections observed by HoneyBot sensors. It lets analysts investigate IP records, network context, botnet infrastructure and related activity, and supplies IP blocklist feeds.

**The lowdown:** It’s particularly useful for network-security investigations and cyber threat intelligence because it provides access to observed network activity rather than relying exclusively on third-party reputation lists.

### How to Use:

**1. Visit whatoblock.com and create an account.**

<img src="../.gitbook/assets/unknown (854).png" alt="" height="257" width="602">

**2. Choose the appropriate intelligence product:**

* **Scanner Recon for port-scanning activity.**
* **Heartbeat for proxies, Tor and DDoS-related infrastructure.**
* **Botnet & C2 for suspected command-and-control infrastructure.**
* **OpenData for downloadable network datasets.**

<img src="../.gitbook/assets/unknown (855).png" alt="" height="297" width="602">

<img src="../.gitbook/assets/unknown (856).png" alt="" height="296" width="602">

**3. Use filters to narrow your search then review observation details and related activity.**

<img src="../.gitbook/assets/unknown (857).png" alt="" height="225" width="602">

**4. Corroborate findings with other sources before reporting or blocking.**

### Cost

* [ ] Free
* [x] Partially Free
* [ ] Paid

Paid plans available.

## Data Processing

### Account Required:

* [x] Yes
* [ ] No

Yes for live records and blocklist access.

### Cookies:&#x20;

The site uses Cloudflare cookies (\_\_cf\_ob and cf\_clearance) to support browser verification, challenge handling and anti-bot security. The \_\_cf\_ob cookie appears to store encoded browser-interaction and navigation information, while cf\_clearance records successful completion of a Cloudflare security check.&#x20;

The dashboard also uses a first-party whatoblock\_session cookie for application session management and \_\_Host-whatoblock-cookie-scope for cookie-scope configuration. Google Analytics cookies (\_ga and \_ga\_WG301238QT) measure website usage and maintain visitor/session analytics state.&#x20;

### Use in Reporting

Whatoblock can be useful for:

* Investigating IP addresses observed probing internet-facing services.
* Examining repeated TCP and UDP port-scanning activity.
* Identifying which ports and protocols a suspicious IP address has been observed probing.
* Investigating possible botnet command-and-control infrastructure.
* Researching IP addresses associated with open proxies, residential proxies, datacenter proxies and Tor exit nodes.
* Examining IP addresses associated with suspected DDoS activity.
* Investigating network reconnaissance against exposed services such as SSH, RDP, VNC and HTTP.
* Examining captured packet information to understand what a scanner or automated connection transmitted to a honeypot.
* Identifying networks, ASNs, ISPs and hosting organisations associated with observed activity.
* Comparing activity across countries, networks, protocols and time periods.
* Identifying recurring scanning patterns and changes in network activity.
* Researching infrastructure potentially associated with malware, botnets and other cyber threats.
* Examining DNS, NTP and SSDP datasets for network-security research.
* Producing supporting evidence for incident-response investigations and technical threat-intelligence reports.

**Note from the developer:** Use observations as context for an IP investigation and corroborate independently.

| **Capabilities**                                                                            | **Limitations**                                                                      |
| ------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| Searches and filters network observations.                                                  | Free account provides limited records and a sample blocklist.                        |
| Investigates IP and related botnet infrastructure.                                          | Data reflects sensor coverage, not all internet activity.                            |
| Provides searchable TCP and UDP scanner records, including ports, protocols and timestamps. | Classification does not prove that an IP address is controlled by a malicious actor. |
| Provides threat maps, analysis tools, downloadable datasets and firewall-ready blocklists.  | UDP source addresses can be spoofed, so UDP observations require additional caution. |

### Summary

Whatoblock is a cybersecurity threat-intelligence platform that uses a distributed honeypot network to observe, classify and investigate unsolicited internet traffic. It’s most useful for IP threat triage and investigating observed network activity, however its records represent activity observed by its own sensors, not proof of the identity or intentions of the person or organisation behind an IP address.&#x20;

Findings should be corroborated with other threat-intelligence sources, network logs, and technical evidence.

### Ownership

Founded by [Stelios Pavlidis](https://www.linkedin.com/in/steliospavlidis/), based in Athens according to LinkedIn.

### Ethical Considerations

* An IP address appearing in Whatoblock does not identify the person or organisation controlling the device.
* A recorded connection is evidence of activity observed by a sensor, not proof of malicious intent.
* IP addresses may belong to shared networks, VPNs, proxies, compromised servers, cloud infrastructure or residential gateways.
* UDP source addresses can be spoofed. Use TCP observations or the platform's spoofable-UDP filter when stronger source verification is required.
* Do not describe every scanner as an attacker. Security researchers, search engines, and legitimate monitoring services also conduct scanning.
* Treat downloadable malware samples as potentially dangerous. Use isolated analysis environments and appropriate security controls.
* Applying a blocklist can disrupt legitimate services, particularly where shared IP addresses, cloud providers or content-delivery networks are involved.
* • Verify context and authorisation before blocking or acting on an observation.

### Related Tools:

• AbuseIPDB

• [VirusTotal](virustotal.md)

• GreyNoise

#### Sources

[https://whatoblock.com/](https://whatoblock.com/)&#x20;

[https://whatoblock.com/platform](https://whatoblock.com/platform)&#x20;

[https://whatoblock.com/documentation](https://whatoblock.com/documentation)&#x20;

[https://whatoblock.com/privacy](https://whatoblock.com/privacy)&#x20;

[https://www.linkedin.com/in/steliospavlidis/](https://www.linkedin.com/in/steliospavlidis/)&#x20;



_With thanks to Stelios Pavlidis for submitting this tool to the OSINT Tool Library._&#x20;
