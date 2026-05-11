---
description: >-
  Tool Description: Internet intelligence and attack surface discovery platform
  to search and analyse publicly exposed infrastructure, domains, services,
  certificates, technologies etc.
---

# Netlas

| **Netlas**       | **Quick Overview**                                                                                                                                                                                                         |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://netlas.io/](https://netlas.io/)                                                                                                                                                                                   |
| What it does     | Indexes vast amounts of internet-facing infrastructure and metadata, allowing users to search for domains, IPs, SSL certificates, open ports, technologies, services, login panels, APIs, and exposed systems.             |
| How to use it    | Search using keywords, domains, IP addresses, technologies, certificates, banners, or advanced filters. Results can reveal exposed infrastructure, linked assets, technologies in use, and potential security weaknesses.  |
| Cost             | Free for basic use. Paid for further functionality.                                                                                                                                                                        |
| Account required | Yes.                                                                                                                                                                                                                       |
| Cookies          | Yes - Security and bot protection, analytics tracking, storing user consent preferences, protecting authenticated sessions, and remembering interface settings                                                             |
| Ownership        | Owned and operated by Armenian company Netlas LLC, headed up by CEO and co-founder, Arthur Kotylevskiy.                                                                                                                    |
| Use in Reporting | Useful to identify exposed infrastructure, correlate digital assets, and uncover publicly accessible technical data.                                                                                                       |

### What does Netlas do?

Netlas acts like a specialised search engine for internet-connected systems. Instead of searching websites like a traditional search engine, it searches infrastructure data collected from internet-wide scans.

Users can search for:

* Domains
* IP addresses
* Open ports
* SSL/TLS certificates
* Login panels
* APIs
* Technologies and frameworks
* Cloud services
* Email servers
* Remote access systems
* Exposed databases
* Misconfigured services

It also supports advanced filtering and query operators, making it extremely useful for narrowing investigations quickly.

**The lowdown:** If you’ve used tools like Shodan or Censys before, Netlas sits comfortably in the same ecosystem, but with its own style, datasets, and querying strengths.&#x20;

### How to Use:

**1. Search a company domain, IP address, ASN, technology name, or service banner.**

<img src="../.gitbook/assets/unknown (106).png" alt="" height="307" width="602">

**2. Once you find a result, use linked metadata to expand the investigation.  For example, you could explore other domains sharing the same IP, review SSL certificate details, or discover related subdomains or cloud assets.**&#x20;

<img src="../.gitbook/assets/unknown (107).png" alt="" height="352" width="602">

### Cost

* [ ] Free
* [x] Partially Free
* [ ] Paid

A limited free tier is available, with premium plans unlocking larger datasets, historical scans, exports, API access, and advanced querying features.

## Data Processing

### Account Required:

* [x] Yes
* [ ] No

### Cookies:&#x20;

Netlas uses cookies for security and bot protection, analytics tracking, storing user consent preferences, protecting authenticated sessions, and remembering interface settings such as theme preferences.&#x20;

### Use in Reporting

Netlas can provide strong supporting evidence in:

* Threat intelligence reports
* Exposure assessments
* Red team reports
* Infrastructure mapping
* Incident response investigations
* Vulnerability research
* Attribution analysis

Security researchers use Netlas to discover what a company exposes to the internet (servers, subdomains, services, etc.), helping build a full digital footprint for reporting or audits. For example, it’s used to map infrastructure like web servers, email systems, and cloud services to understand exposure and misconfigurations.

| **Capabilities**                         | **Limitations**                                           |
| ---------------------------------------- | --------------------------------------------------------- |
| Internet-wide infrastructure discovery.  | Advanced features are locked behind paid plans.           |
| SSL certificate and domain correlation.  | Data may not always reflect real-time changes.            |
| Open port and service identification.    | False positives can occur in scan results.                |
| Technology and software fingerprinting.  | Requires technical knowledge for effective use.           |
| Advanced filtering and search operators. | Limited context around identified assets or services.     |
| Attack surface and asset mapping.        | Does not confirm vulnerabilities without further testing. |

### Summary

Netlas is especially valuable during cyber threat intelligence, attack surface mapping, and infrastructure attribution investigations. primarily sitting within the collection, discovery, and analysis stages of the OSINT workflow.

### Ownership

Netlas.io is owned and operated by[ Netlas LLC](https://www.google.com/search?q=Netlas+LLC\&rlz=1C1VDKB_enGB1040GB1040\&oq=who+owns+netlas\&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIKCAEQABixAxiABDIKCAIQABixAxiABDIHCAMQABiABDIHCAQQABiABDIHCAUQABiABDIHCAYQABiABDIHCAcQABiABDIHCAgQABiABDIHCAkQABiABNIBCDM2NzRqMGo0qAIDsAIB8QV8FNdXo1cugQ\&sourceid=chrome\&ie=UTF-8\&mstk=AUtExfBpV5iIYo2WzU7socuJJkkIgY3S2O0NPLdC93OwV8JUHSU3krjeKV8zt9oeUnNDJNKPp4j4Aj0tXPmJztPS552CWXwaWzYR5NXVJn2wgqCklZxeKmH26iXpHAbwOseHjMG6Psw8eGvYbJG9F0crbzJpH1uGwXHBo3TG7QBK3E3ddCk\&csui=3\&ved=2ahUKEwinsrTUqqeUAxUWaEEAHUdZK6AQgK4QegQIARAC), a company incorporated in Armenia since June 16, 2022. The cybersecurity search engine and platform are managed by a team led by CEO and co-founder [Arthur Kotylevskiy](https://www.linkedin.com/in/arturkotylevskiy/), a cybersecurity expert.

### Ethical Considerations

* Avoid unauthorised access attempts.
* Respect privacy and legal boundaries.
* Verify findings before attribution.
* Avoid active interaction with exposed systems unless authorised.
* Consider operational security (OPSEC) when conducting sensitive investigations.

### Related Tools:

* [Shodan](shodan.md)
* [Censys](censys.md)
* ZoomEye

#### Sources

[https://netlas.io/](https://netlas.io/)&#x20;

[https://netlas.io/legal/](https://netlas.io/legal/)&#x20;

[https://www.linkedin.com/in/arturkotylevskiy/](https://www.linkedin.com/in/arturkotylevskiy/)&#x20;
