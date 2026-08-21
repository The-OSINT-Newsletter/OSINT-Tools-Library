---
description: >-
  Tool Description : A lightweight tool for generating a Shodan-compatible
  favicon hash from a website favicon or local favicon file.
---

# Favicon Hash Generator

| **Favicon hash generator** | **Quick Overview**                                                                                                                            |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| URL                        | [https://favicon-hash.kmsec.uk/](https://favicon-hash.kmsec.uk/)                                                                              |
| What it does               | Generates the hash of a favicon.ico which then lets you find websites that may impersonate your brand and phishing.                           |
| How to use it              | Simply enter a favicon URL or upload a favicon file, then generate the hash.                                                                  |
| Cost                       | Free.                                                                                                                                         |
| Account required           | No.                                                                                                                                           |
| Cookies                    | None.                                                                                                                                         |
| Ownership                  | Owned by KMSEC based in Cape Town, South Africa, and founded by [Keith Makan.](https://www.linkedin.com/in/keith-m-766b823a/)                 |
| Use in Reporting           | Record the favicon hash as an indicator and document any potentially impersonating or phishing sites identified through the resulting pivot.  |

### What does Favicon Hash Generator do?

Favicon hash generator generates a hash from a website's favicon.ico. The resulting hash can be used as a search indicator to find other websites or infrastructure using the same favicon, which can help identify potential brand impersonation, phishing sites or related infrastructure.&#x20;

**The lowdown:** The tool can be particularly useful when investigating brand impersonation or phishing, as a matching favicon may reveal additional websites that warrant investigation.&#x20;

**Important note:** A favicon match is not proof of attribution. Legitimate websites, shared hosting environments, and unrelated organisations can use the same favicon, so findings should be corroborated with other indicators.&#x20;

### How to Use:

**1. Enter a favicon URL or upload a favicon file to generate the hash.**

<img src="../.gitbook/assets/unknown (452).png" alt="" height="309" width="602">

**2. Use the generated hash as a pivot to search for other websites or infrastructure using the same favicon. Investigate any matches for signs of brand impersonation, phishing or other suspicious activity.**

The tool connects with Shodan, VirusTotal and Censys. Our results with Censys below:

<img src="../.gitbook/assets/unknown (453).png" alt="" height="475" width="602">

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

### Cookies:&#x20;

No account or login is required. The site states that it is built using Cloudflare Workers; no cookie requirement is identified on the tool itself and none were noted during our site session on 10 August 2026.

### Use in Reporting

<br>

Relevant use cases include:

<br>

* Brand impersonation investigations.
* Phishing investigations.
* Threat intelligence (pivot from a known suspicious website to potentially related infrastructure.)
* Infrastructure mapping (identify websites or hosts that share a common favicon and investigate possible links between them.)
* Lookalike website investigations.
* Brand protection reporting.

<br>

Note: A favicon hash alone does not establish ownership or attribution.

| **Capabilities**                                                | **Limitations**                                              |
| --------------------------------------------------------------- | ------------------------------------------------------------ |
| Generates a hash from a favicon.ico file.                       | A matching favicon doesn’t prove common ownership.           |
| Identifies websites using the same favicon.                     | Legitimate websites may use the same favicon.                |
| Supports brand impersonation investigations.                    | Changing a favicon will produce a different hash.            |
| Can help uncover potential phishing websites.                   | A favicon hash alone provides limited investigative context. |
| Provides a useful pivot for finding related infrastructure.     | Some websites may prevent their favicon being retrieved.     |
| Can be used with either a favicon URL or a local favicon file.  | <p><br></p>                                                  |

### Summary

Favicon Hash Generator is best used during the discovery and pivoting stage of an OSINT investigation, rather than being used as an attribution tool. A matching favicon can highlight websites for further investigation, but additional evidence is required before concluding that sites are connected or malicious.

### Ownership

Owned and operated by KMSEC (Keith Makan Security Consultancy); a cybersecurity consultancy based in Cape Town, South Africa and founded by [Keith Makan.](https://www.linkedin.com/in/keith-m-766b823a/)

### Ethical Considerations

* Use only for legitimate OSINT and security research.
* Do not assume a favicon match proves common ownership.
* Verify findings with additional sources and indicators.
* Avoid unnecessary interaction with suspicious websites.
* Consider privacy when handling submitted favicon URLs or files.

### Related Tools:

* Shodan
* VirusTotal
* [Censys](censys.md)
* SecurityTrails
* [urlscan.io](urlscan.md)

#### Sources

[https://favicon-hash.kmsec.uk/](https://favicon-hash.kmsec.uk/)&#x20;

[https://www.linkedin.com/in/keith-m-766b823a/](https://www.linkedin.com/in/keith-m-766b823a/)&#x20;
