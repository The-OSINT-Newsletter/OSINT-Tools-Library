---
description: >-
  Tool Description : A web scanning tool that safely visits a URL on your behalf
  and records everything that happens.
---

# urlscan.io

| **urlscan.io**   | **Quick Overview**                                                                                                                                         |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://urlscan.io/](https://urlscan.io/)                                                                                                                 |
| What it does     | It loads a website in a safe environment capturing page screenshots, domains contacted, IP addresses, scripts and resources loaded, and technologies used. |
| How to use it    | Drop in a suspicious URL, review the screenshot first, then dive into network requests to see hidden connections.                                          |
| Cost             | Free for basic use. Paid for higher volume, API access, and private scans.                                                                                 |
| Account required | No for basic scans. Yes for advanced features.                                                                                                             |
| Cookies          | Basic tracking and session cookies (but none recorded in our session).                                                                                     |
| Ownership        | German cybersecurity company urlscan GmbH, founded by Johannes Gilger.                                                                                     |
| Use in Reporting | Strong for evidence-based reporting. Screenshots help explain findings to non-technical audiences and technical logs support deeper analysis.              |

### What does urlscan.io do?

urlscan.io acts like a digital investigator, visiting a website so you don’t have to and recording everything it sees and does. It loads a website in a controlled environment and captures page screenshots, domains contacted, IP addresses, scripts and resources loaded, and technologies used.&#x20;

**The lowdown:** urlscan.io is a must-have OSINT tool for safely analysing websites. Think of it as a safe remote browser ideal for safely analysing suspicious or unknown links.

### How to Use:

1. **Paste a URL into the search bar and click “Scan”.**

<figure><img src="../.gitbook/assets/unknown (6) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

2. **Wait for the scan to complete (usually seconds) and explore the results via tabs (Summary, Links, DOM, etc.)**

<figure><img src="../.gitbook/assets/unknown (7) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

**Top tip: Use filters and search to pivot into related domains or infrastructure.**

**You can also** [**view our full guide in the OSINT Newsletter here.**](https://osintnewsletter.com/p/68)

### Cost

* [ ] Free
* [x] Partially Free
* [ ] Paid

Free for basic use. Paid for higher volume, API access, and private scans.

## Data Processing

### Account Required:

* [x] Yes
* [x] No

No for basic scans. Yes for advanced features like private scans and API use.

### Cookies:&#x20;

When we visited the webpage on 26.03.26, no cookies were recorded.

### Use in Reporting

Urlscan.io can be useful for:

* Providing visual evidence (screenshots).
* Capturing technical indicators (IPs, domains, requests).
* Malware analysis, phishing investigations, and attribution.
* Accessing easily shareable scan links.&#x20;

In real-world terms, a[ Reuters investigation](https://www.reuters.com/world/mercenary-hacker-group-runs-rampant-middle-east-cybersecurity-research-shows-2020-10-07/) revealed a for-hire hacking group (Bahamut) targeting individuals across regions using phishing, fake apps, and surveillance tools.&#x20;

“Reuters was able to identify new targets by cross-referencing data published in BlackBerry's report with boobytrapped webpages preserved by urlscan.io.”

| **Capabilities**                          | **Limitations**                                              |
| ----------------------------------------- | ------------------------------------------------------------ |
| Safe URL detonation (no direct exposure). | Some sites block automated scanners.                         |
| Full page rendering and screenshots.      | Limited scans per day on the free tier.                      |
| Network traffic analysis.                 | Advanced features require paid access.                       |
| Domain and IP extraction.                 | Not fully anonymous (target site may detect scan activity).  |
| Technology fingerprinting.                | <p><br></p>                                                  |
| Historical scan database.                 | <p><br></p>                                                  |

### Summary

urlscan.io combines visual insight with deep technical data, making it perfect for both quick checks and detailed investigations. It’s best used in the analysis and pivoting stages of the OSINT workflow to safely inspect a URL and uncover related infrastructure and activity.

### Ownership

The tool is owned by urlscan GmbH, a German cybersecurity company that provides web analysis and threat intelligence services. It was founded in 2017 by [Johannes Gilger.](https://www.linkedin.com/in/johannesgilger/)

### Ethical Considerations

* Only scan URLs you are authorised to investigate.
* Be aware scans may alert the target website.
* Avoid scanning sensitive or personal links without justification.
* Follow organisational and legal guidelines.

### Related Tools:

* VirusTotal
* Hybrid Analysis
* [Shodan](shodan.md)

#### Sources

[https://urlscan.io/](https://urlscan.io/)&#x20;

[https://urlscan.io/about/](https://urlscan.io/about/)&#x20;

[https://www.linkedin.com/in/johannesgilger/](https://www.linkedin.com/in/johannesgilger/)&#x20;

[https://x.com/heipei](https://x.com/heipei)&#x20;

[https://www.crunchbase.com/person/johannes-gilger](https://www.crunchbase.com/person/johannes-gilger)&#x20;

[https://www.backblaze.com/cloud-storage/case-studies/urlscan-io](https://www.backblaze.com/cloud-storage/case-studies/urlscan-io)&#x20;

[https://www.reuters.com/world/mercenary-hacker-group-runs-rampant-middle-east-cybersecurity-research-shows-2020-10-07/](https://www.reuters.com/world/mercenary-hacker-group-runs-rampant-middle-east-cybersecurity-research-shows-2020-10-07/)
