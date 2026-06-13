---
description: >-
  Tool Description : A non-profit, regional internet registry that provides
  public access to IP address, Autonomous System Number (ASN), and network
  ownership records for North America.
---

# ARIN

| **ARIN**         | **Quick Overview**                                                                                                                                                 |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| URL              | [https://www.arin.net/](https://www.arin.net/)                                                                                                                     |
| What it does     | Provides registration information for IP addresses, IP ranges, Autonomous System Numbers (ASNs), organisations, and network contacts within ARIN's service region. |
| How to use it    | Search an IP address, ASN, CIDR range, organisation name, or domain to retrieve registration and ownership info.                                                   |
| Cost             | Free.                                                                                                                                                              |
| Account required | No.                                                                                                                                                                |
| Cookies          | Google Analytics cookies to collect anonymous visitor statistics and a functional survey cookie.                                                                   |
| Ownership        | American Registry for Internet Numbers (ARIN), a non-profit Regional Internet Registry (RIR)                                                                       |
| Use in Reporting | Useful for identifying network ownership, attributing IP addresses, investigating online infrastructure, and supporting cyber investigations.                      |

### What does ARIN do?

ARIN acts as one of the world's five Regional Internet Registries (RIRs), responsible for managing and recording internet number resources across the United States, Canada, and parts of the Caribbean. Its public WHOIS and RDAP services allow investigators to discover who has been allocated an IP address block or ASN and identify the organisation responsible for that network.&#x20;

ARIN is a core OSINT resource for identifying who controls internet infrastructure, investigating IP addresses, and attributing network activity to organisations.&#x20;

**The lowdown:** While it won't reveal individual identities, it often provides the crucial first step in understanding who is behind a piece of internet infrastructure.&#x20;

### How to Use:

**1. Search an IP address, IP range, ASN, or organisation name from your investigation using ARIN's WHOIS or RDAP search tool.**&#x20;

<img src="../.gitbook/assets/unknown (204).png" alt="" height="133" width="602">

**2. Review the results including organisation name, network owner, contact details, IP allocation ranges, ASN information, registration dates, and related network resources.**

<img src="../.gitbook/assets/unknown (205).png" alt="" height="404" width="602">

**3. Cross-reference findings with other tools for additional context.**

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

### Cookies:&#x20;

The site uses Google Analytics cookies to collect anonymous visitor statistics and a functional survey cookie to remember whether website feedback or questionnaire prompts have already been completed or dismissed.

### Use in Reporting

ARIN can support reporting by:

* Identifying organisations behind IP addresses.
* Investigating cyber incidents and phishing campaigns.
* Verifying hosting providers and network ownership.
* Mapping digital infrastructure used by organisations.
* Supporting attribution in cyber threat intelligence investigations.
* Providing evidence of IP ownership and allocation records.
* Corroborating technical findings from other OSINT sources.

Journalists and researchers [routinely use ARIN WHOIS records](https://www.lifewire.com/look-up-ip-address-owner-11710872) when investigating the ownership of IP addresses linked to websites, cyber incidents, and online services.&#x20;

| **Capabilities**                                                          | **Limitations**                                                                       |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| Identifies the organisation responsible for an IP address/network range.  | Doesn’t identify individual users behind IP addresses.                                |
| Provides ASN, IP allocation, and registration information.                | Primarily covers ARIN’s geographic region (North America and parts of the Caribbean). |
| Helps attribute online infrastructure to organisations and providers.     | Registration info may be outdated/incomplete.                                         |
| Supports WHOIS and RDAP searches for internet resources.                  | Hosting providers often mask the end-user behind the infrastructure.                  |
| Useful for cyber investigations, infrastructure mapping, and attribution. | Requires additional OSINT sources for full attribution.                               |

### Summary

ARIN is a powerful infrastructure-focused OSINT resource, best used in the infrastructure analysis stage of the OSINT workflow, usually right after you’ve identified an IP address or network indicator.&#x20;

### Ownership

ARIN (American Registry for Internet Numbers) is a non-profit Regional Internet Registry responsible for managing and registering internet number resources throughout the United States, Canada, and parts of the Caribbean.&#x20;

### Ethical Considerations

* Avoid assuming that network ownership equals responsibility for activity originating from an IP address.
* Note that hosting providers often allocate infrastructure to thousands of customers.
* Use attribution cautiously and corroborate findings through multiple sources.
* Respect privacy and legal considerations when investigating internet infrastructure.
* Clearly distinguish between network ownership and user identity in reporting.

### Related Tools:

* ICANN Lookup
* [Shodan](shodan.md)
* [Censys](censys.md)

#### Sources

[https://www.arin.net/](https://www.arin.net/)&#x20;

[https://www.arin.net/resources/registry/whois/](https://www.arin.net/resources/registry/whois/)&#x20;

[https://www.lifewire.com/look-up-ip-address-owner-11710872](https://www.lifewire.com/look-up-ip-address-owner-11710872)
