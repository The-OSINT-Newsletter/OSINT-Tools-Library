---
description: 'Tool Description : Allows you to find various information via a phone number.'
---

# Phunter

| **Phunter**      | **Quick Overview**                                                                                                        |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://github.com/N0rz3/Phunter](https://github.com/N0rz3/Phunter)                                                      |
| What it does     | Uses a phone number to quickly uncover linked accounts, breaches, and online footprints.                                  |
| How to use it    | Run it via the command line with a target phone number and let it enumerate results from supported sources.               |
| Cost             | Free.                                                                                                                     |
| Account required | No.                                                                                                                       |
| Cookies          | None (runs locally in your environment)                                                                                   |
| Ownership        | Developed and maintained by the GitHub user N0rz3, based in France.                                                       |
| Use in Reporting | Useful for demonstrating links between a phone number and online services, or identifying potential exposure in breaches. |

### What does Phunter do?

Phunter helps gather intelligence on phone numbers by pulling together publicly available data from multiple sources, such as social media presence, breaches, and other digital traces. Think of it as a quick way to profile a number and spot links to accounts, leaks, or activity online.

**The lowdown:** It’s a lightweight OSINT tool, helping investigators quickly pivot from a phone number to potential online identities and exposures. It’s best used as a starting point, rather than a single source of truth.

### How to Use:

How to use it:

**1. Clone the repository from GitHub and install requirements.**

**2. Run the script with a phone number in international format.**

**3. Review the output for linked accounts, mentions, or breaches.**

**Example command pulled from GitHub:**&#x20;

$ python3 phunter.py -t +33666666666

<figure><img src="../.gitbook/assets/unknown (67).png" alt=""><figcaption></figcaption></figure>

_Image above is from Phunter on GitHub._

You can[ view our full guide including installation and usage at the OSINT newsletter here.](https://osintnewsletter.com/p/phunter)

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

### Cookies:&#x20;

None (runs locally in your environment).

### Use in Reporting

Phunter is useful for:

* Attributing activity to a phone number.
* Supporting investigations into digital footprints.
* Highlighting potential data exposure or breaches.
* Providing evidence of account linkage.

The techniques Phunter enables mean it could be used in cyber fraud and scam investigations, threat intelligence, and identity attribution and digital footprint mapping.

| **Capabilities**                             | **Limitations**                             |
| -------------------------------------------- | ------------------------------------------- |
| Phone number intelligence gathering.         | Dependent on available public data.         |
| Cross-platform account discovery.            | May produce false positives.                |
| Breach and leak checking.                    | Limited coverage compared to paid tools.    |
| Fast automation of repetitive OSINT tasks.   | Requires some technical setup (CLI usage)   |
| CLI-based (good for scripting and workflows. | Results can vary by region and number type. |

### Summary

Phunter is great for quick pivots, typically best used during the enrichment and pivoting phase of the OSINT workflow, where investigators can expand from a single data point (i.e. a phone number) to uncover linked accounts, breaches, and online activity. However, it’s not reliable enough to be used on its own without verification.

### Ownership

Developed and maintained by GitHub user [N0rz3](https://github.com/N0rz3), based in France.

### Ethical Considerations

* Only use numbers you are authorised to investigate.
* Be mindful of privacy and legal boundaries.
* Avoid harassment, doxxing, or misuse of personal data.
* Always verify findings before drawing conclusions.

### Related Tools:

* PhoneInfoga
* Holehe
* Sherlock
* WhatsMyName

#### Sources

[https://github.com/N0rz3/Phunter](https://github.com/N0rz3/Phunter)&#x20;

[https://github.com/N0rz3](https://github.com/N0rz3)&#x20;

[https://x.com/norze15](https://x.com/norze15)&#x20;

[https://offsec.tools/tool/phunter](https://offsec.tools/tool/phunter)&#x20;

[https://osintnewsletter.com/p/phunter](https://osintnewsletter.com/p/phunter)&#x20;

