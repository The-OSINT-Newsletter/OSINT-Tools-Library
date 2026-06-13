---
description: >-
  Tool Description : A web forensics tool that captures a webpage and maps every
  domain, resource, redirect, and third-party connection involved in loading it.
---

# Lookyloo

| **Lookyloo**     | **Quick Overview**                                                                                                                                                                  |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://lookyloo.circl.lu/capture](https://lookyloo.circl.lu/capture)                                                                                                              |
| What it does     | Captures a webpage and generates an interactive visual map showing all domains, redirects, scripts, trackers, and resources loaded by the page.                                     |
| How to use it    | Submit a URL for analysis and review the generated domain tree, HTTP requests, redirects, cookies, & associated resources.                                                          |
| Cost             | Free.                                                                                                                                                                               |
| Account required | No.                                                                                                                                                                                 |
| Cookies          | Minimal/none.                                                                                                                                                                       |
| Ownership        | Developed and maintained by the CIRCL (Computer Incident Response Center Luxembourg).                                                                                               |
| Use in Reporting | Useful for analysing phishing websites, documenting redirects, identifying third-party infrastructure, & demonstrating how websites load content and connect to external services.  |

### What does Lookyloo do?

Lookyloo helps investigators understand how websites behave, identify suspicious infrastructure, analyse phishing pages, and uncover hidden relationships between web resources.&#x20;

Rather than simply showing what a page looks like, Lookyloo reveals everything happening in the background when a page loads. It captures requests, redirects, scripts, trackers, cookies, and external resources, then visualises how they all connect.&#x20;

**The lowdown:** It provides valuable visibility into website infrastructure and behaviour.

### How to Use:

**1. Enter the URL you want to investigate and simply run the capture.**

<img src="../.gitbook/assets/unknown (201).png" alt="" height="184" width="602">

**2. Review the generated investigation tree paying attention to redirect chains, external domains, third-party scripts, tracking services, embedded resources, and infrastructure overlaps.**

<img src="../.gitbook/assets/unknown (202).png" alt="" height="299" width="602">

**3. You can also view capture details, statistics, storage state, and screenshots on a separate tab, plus various analytical tools. Export or document findings for further analysis and reporting.**&#x20;

<img src="../.gitbook/assets/unknown (203).png" alt="" height="176" width="602">

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

### Cookies:&#x20;

Minimal/none logged during our site session on 10 June 2026.

### Use in Reporting

Lookyloo can support reporting by:

* Documenting phishing infrastructure.
* Mapping redirect chains used in scams.
* Identifying third-party services and trackers.
* Visualising website relationships for readers and stakeholders.
* Supporting cyber threat intelligence investigations.
* Verifying connections between suspicious domains.
* Providing screenshots and technical evidence of website behaviour.

[CIRCL](https://www.circl.lu/projects/internships/lookyloo02/) states that it uses the platform daily to analyse phishing and malicious websites during incident response investigation.&#x20;

| **Capabilities**                                                       | **Limitations**                                                                  |
| ---------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| Captures and analyses websites in real time.                           | Only analyses publicly accessible web content.                                   |
| Visualises all domains and resources involved in loading a webpage.    | Cannot identify the individuals operating a website.                             |
| Reveals redirect chains and third-party dependencies.                  | Results reflect the website at the time of capture and may change later.         |
| Helps identify suspicious scripts, trackers, and external services.    | Complex websites can generate large volumes of data that require interpretation. |
| Supports phishing, malware, and website infrastructure investigations. | Public capture instances may have rate limits or temporary availability issues.  |

### Summary

Lookyloo is a powerful web investigation tool that helps analysts understand what happens behind the scenes when a webpage loads, and is most valuable during the analysis stage of the OSINT workflow.

### Ownership

Developed and maintained by the [CIRCL](https://www.circl.lu/mission/) (Computer Incident Response Center Luxembourg). The project is open source and publicly available for community use and contribution.&#x20;

### Ethical Considerations

* Avoid submitting sensitive, private, or internal URLs to public instances.
* Be aware that publicly submitted captures may be visible to other users depending on configuration.
* Consider operational security (OPSEC) when investigating malicious websites.
* Verify findings through multiple sources before drawing conclusions about ownership or malicious intent.

### Related Tools:

* [urlscan.io](urlscan.md)
* VirusTotal
* ANY.RUN

#### Sources

[https://lookyloo.circl.lu/capture](https://lookyloo.circl.lu/capture)&#x20;

[https://www.circl.lu/mission/](https://www.circl.lu/mission/)&#x20;

[https://www.circl.lu/projects/internships/lookyloo02/](https://www.circl.lu/projects/internships/lookyloo02/)&#x20;
