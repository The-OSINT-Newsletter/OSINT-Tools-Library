---
description: >-
  Tool Description :  A fast, browser-based OSINT tool for uncovering
  infrastructure linked to a domain.
---

# Domain Digger

| **Domain Digger** | **Quick Overview**                                                                                                                                           |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| URL               | [https://digger.tools/](https://digger.tools/)                                                                                                               |
| What it does      | Pulls together technical domain intelligence into one clean interface.                                                                                       |
| How to use it     | Enter a domain name, IP address, or hostname into the search bar, then review the returned infrastructure data and pivot into related assets.                |
| Cost              | Free.                                                                                                                                                        |
| Account required  | No.                                                                                                                                                          |
| Cookies           | Mainly used for account authentication, security, consent management, analytics, and delivering location-aware search functionality across Google services.  |
| Ownership         | Public ownership details are limited.                                                                                                                        |
| Use in Reporting  | Particularly useful for identifying relationships between websites and infrastructure during OSINT investigations.                                           |

### What does Domain Digger do?

Domain Digger is one of those tools that saves investigators a huge amount of time. Instead of jumping between DNS lookups, SSL checkers, and hosting databases, it pulls the important infrastructure details into one place. Essentially, when you drop in a domain, you instantly get a technical snapshot of how that website is built and where it lives online.

For OSINT analysts, this makes pivoting incredibly easy. A single IP address can lead to other hosted domains. A reused name server might expose connected infrastructure. SSL certificate overlaps can reveal hidden relationships between websites that appear unrelated on the surface.&#x20;

**The lowdown:** The interface is lightweight, quick, and easy to navigate, making it suitable for both beginners and experienced analysts.&#x20;

### How to Use:

**1. Head to Domain Digger and enter a target domain, IP address, or host name.**

<img src="../.gitbook/assets/unknown (120).png" alt="" height="188" width="602">

**2. Review the infrastructure data including MX records, NS records, hosting provider records, SSL certificate references and more. From here you can find patterns, pivot, and expand the investigation.**

<img src="../.gitbook/assets/unknown (121).png" alt="" height="517" width="602">

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

### Cookies:&#x20;

These cookies are primarily used by Google to manage authentication, security, user preferences, consent settings, and location-based functionality across its services. High-risk cookies such as SID, SAPISID, SSID, and SIDCC are linked to user account sessions and security protections, helping Google verify identity, prevent abuse, and maintain signed-in experiences.

Other cookies like OTZ, SOCS, and UULE are more focused on analytics, consent preferences, and localisation. UULE in particular is associated with geographic targeting in Google search results, while SOCS stores cookie consent choices and OTZ is commonly used for traffic measurement and service optimisation.

### Use in Reporting

Domain Digger can support:

* Infrastructure mapping
* Threat actor profiling
* Phishing investigations
* Brand impersonation investigations
* Attribution research
* Technical annexes in intelligence reports
* Domain and hosting correlation analysis

**Note:** When used in reporting, screenshots and exported data should be timestamped and independently verified where possible.

Whilst not much in the way of high-profile published intelligence reports openly stating Domain Digger’s use, the tool appears to be gaining traction among independent OSINT practitioners, cyber researchers, and domain investigators as part of modern infrastructure-analysis workflows.&#x20;

| **Capabilities**                                                   | **Limitations**                                                                |
| ------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| Quickly maps technical infrastructure.                             | Limited historical visibility compared to premium intelligence platforms.      |
| Helps identify linked digital assets.                              | Some infrastructure data may be incomplete or outdated.                        |
| Quick and simple interface, with no login barrier.                 | Requires analyst interpretation. Raw technical data alone is not attribution.  |
| Useful for infrastructure attribution and pivoting investigations. | Not a replacement for passive DNS datasets.                                    |

### Summary

Domain Digger typically sits in the infrastructure analysis and pivoting stage of the OSINT workflow, where you can move from an initial domain, IP address, or hostname into mapping connected technical assets such as DNS records, hosting infrastructure, SSL certificates, and related domains to expand and deepen an investigation.

### Ownership

Domain Digger is owned by [Felix Wotschofsky](https://x.com/wotschofsky), currently an engineer at Kombo, and based in Berlin.

### Ethical Considerations

* Always ensure investigations are lawful and authorised.
* Avoid targeting infrastructure without legitimate purpose.
* Corroborate technical findings before making attribution claims.
* Be cautious when reporting potentially sensitive infrastructure links.

### Related Tools:

* [Shodan](shodan.md)
* [Censys](censys.md)
* [IPinfo](ipinfo.md)
* [IntelligenceX](intelligencex.md)

#### Sources

[https://digger.tools/](https://digger.tools/)&#x20;

[https://sourceforge.net/projects/domain-digger.mirror/](https://sourceforge.net/projects/domain-digger.mirror/)&#x20;

[https://cyberliza.medium.com/tuesdaytool-42-domain-digger-one-stop-interface-for-domain-investigation-0e1fbf5266a0](https://cyberliza.medium.com/tuesdaytool-42-domain-digger-one-stop-interface-for-domain-investigation-0e1fbf5266a0)&#x20;

[https://www.reddit.com/r/OSINTExperts/comments/1hfebw2/domain\_digger/](https://www.reddit.com/r/OSINTExperts/comments/1hfebw2/domain_digger/)&#x20;

[https://github.com/wotschofsky/domain-digger](https://github.com/wotschofsky/domain-digger)&#x20;

[https://github.com/wotschofsky](https://github.com/wotschofsky)&#x20;

[https://x.com/wotschofsky](https://x.com/wotschofsky)&#x20;

[https://wotschofsky.com/](https://wotschofsky.com/)&#x20;
