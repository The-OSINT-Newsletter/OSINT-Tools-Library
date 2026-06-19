---
description: >-
  Tool Description : Scans usernames, emails, and phone numbers across 500+
  public sources to map a subject's digital footprint and calculate an exposure
  risk score.
---

# Footprint IQ

| **FootprintIQ**  | **Quick Overview**                                                                                                                                                                      |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://footprintiq.app/](https://footprintiq.app/)                                                                                                                                    |
| What it does     | Searches 500+ platforms by username, email, or phone; detects breaches, data broker listings, phone reputation, and dark web mentions; and scores exposure 0–100 via the LENSiQ engine. |
| How to use it    | Enter a username, email address, or phone number into the search bar, review ranked results (Urgent / Important / Recommended) with confidence scores, then access removal guides.      |
| Cost             | Free (limited). Paid Pro plan.                                                                                                                                                          |
| Account required | Yes (free account for basic scans. Pro account for advanced features).                                                                                                                  |
| Cookies          | Standard analytics and session cookies; no third-party advertising trackers. Does not store scan queries beyond the user's session.                                                     |
| Ownership        | FootprintIQ Ltd (Company No. 14698028), UK. Founder: Robin Clifford, cybersecurity researcher based in Surrey, England.                                                                 |
| Use in Reporting | Useful for identifying online accounts, exposure risks, and digital presence indicators.                                                                                                |

### What does Footprint IQ do?

FootprintIQ is an ethical OSINT platform for digital footprint intelligence. It searches usernames across 500+ social media platforms, forums, developer communities, and dating sites simultaneously. It also detects email breaches via Have I Been Pwned and proprietary sources, identifies listings on 40+ data broker/people-search aggregators (Spokeo, BeenVerified, MyLife, Whitepages, etc.), performs phone number reputation lookups (carrier, line type, risk score), checks for dark web credential leaks, and supports name-based people search.&#x20;

All results are processed through the proprietary LENSiQ engine (Layered Entity & Network Scoring), which applies probability-based confidence scoring to each match — reducing false positives and ranking findings as Urgent, Important, or Recommended. The platform also provides step-by-step removal guides and pre-filled GDPR/CCPA request templates for each data broker found.

**The lowdown:** It’s particularly useful for identifying usernames, breach exposure, and online presence across numerous public sources.

### How to Use:

**1. Navigate to the website, conduct a free search or create a free account/log in. Enter your identifier into the search bar.**

FootprintIQ queries 500+ public sources in parallel — results load progressively.

<img src="../.gitbook/assets/unknown (235).png" alt="" height="559" width="602">

**2. Review the LENSiQ exposure score (0–100) and confidence bands displayed at the top of the report. Browse findings sorted by priority: Urgent (immediate action needed), Important, and Recommended.**

<img src="../.gitbook/assets/unknown (236).png" alt="" height="265" width="602">

**3. For each platform match, review the confidence level and verification guidance provided.**

For data broker listings, use the built-in step-by-step removal guides or pre-filled GDPR/CCPA opt-out requests.

Pro users can also access phone intelligence (carrier, line type, risk score), dark web monitoring, and reverse image search.

**4.Save your identity profile to receive ongoing monitoring alerts for new exposures.**

### Cost

* [ ] Free
* [x] Partially Free
* [ ] Paid

Basic username and email scans available on a free account with limited results. Pro plan unlocks full scan depth, phone intelligence, dark web monitoring, reverse image search, and ongoing identity monitoring alerts.

## Data Processing

### Account Required:

* [x] Yes
* [ ] No

### Cookies:&#x20;

FootprintIQ uses standard session and analytics cookies (e.g., for authentication and usage analytics). No third-party advertising or tracking cookies are used. The platform states it does not sell user data. Scan queries are processed in real time and are not stored beyond the user's session.&#x20;

Analysts should be aware that creating an account links scans to an email address; using a dedicated research email is advisable when conducting third-party investigations.

### Use in Reporting

FootprintIQ is useful across several investigative contexts:

* Journalist investigations: Quickly map a subject's online presence across 500+ platforms to identify accounts, aliases, and potential sources of further intelligence.
* Corporate due diligence: Identify an individual's digital footprint to surface undisclosed affiliations,&#x20;

<table data-header-hidden><thead><tr><th width="257"></th><th></th></tr></thead><tbody><tr><td><strong>Capabilities</strong></td><td><strong>Limitations</strong></td></tr><tr><td>Username search across 500+ social media platforms, forums, developer communities and dating sites. </td><td>Designed for self-audit. Best practice is scanning your own identity rather than third parties without authorisation.</td></tr><tr><td>Email breach detection via Have I Been Pwned and proprietary breach databases.</td><td>Results depend on public data availability. Private/locked accounts won’t be detected.</td></tr><tr><td>Data broker exposure identification across 40+ people-search aggregators (Spokeo, BeenVerified, MyLife, Whitepages, etc.)</td><td>LENSiQ confidence scores and probabilistic - false positives can still occur on common usernames.</td></tr><tr><td>Phone number reputation intelligence: carrier, line type, fraud risk score (Pro)</td><td>Advanced features require a paid subscription.</td></tr><tr><td>Dark web credential and data leak monitoring (Pro)</td><td>Does not access private information, content behind logins, or non-public records.</td></tr><tr><td>Name-based people search and cross-referencing.</td><td>Coverage of 500+ platforms is broad but not exhaustive. Niche platforms may be absent.</td></tr><tr><td>Reverse image and face search for profile photo reuse detection (Pro).</td><td>Data broker removal is guided but not automated. Analysts must complete opt-out steps manually.</td></tr><tr><td>LENSiQ probability-based confidence scoring (0–100) to reduce false positives.</td><td>Not a replacement for full-spectrum OSINT tradecraft; should be used as a starting point alongside other tools.</td></tr></tbody></table>

### Summary

FootprintIQ is most useful during subject identification and digital footprint mapping — particularly during the early reconnaissance phase to establish a subject's online presence, aliases, breach exposure, and data broker listings before moving to deeper, platform-specific analysis.

### Ownership

FootprintIQ is owned and operated by FootprintIQ Ltd, a UK-registered company (Company Number: 14698028). The platform was founded by [Robin Clifford](https://x.com/Footprint_IQ), a cybersecurity researcher specialising in open-source intelligence and digital footprint analysis, based in Surrey, England, United Kingdom.&#x20;

The company operates under UK company law and is subject to UK GDPR data protection regulations. The platform is independently owned and not affiliated with any government body, data broker, or surveillance company. FootprintIQ's stated mission is to provide ethical, transparency-first digital footprint intelligence using only publicly available data.

### Ethical Considerations

* Only scan identities you own or have explicit authorisation to investigate; using OSINT tools against individuals without consent may violate privacy laws in many jurisdictions.
* Be aware of the legal framework in your region before using results in any report or investigation (UK GDPR, CCPA, ECPA, etc.)
* Treat LENSiQ confidence scores as probabilistic indicators, not confirmed facts; always corroborate findings through independent verification before drawing conclusions.
* Avoid using the platform to aggregate or compile profiles on private individuals for purposes beyond legitimate research or self-audit.
* Data broker listings contain real personal data; handle removal findings sensitively and do not redistribute this information.
* Phone intelligence features (carrier, line type, fraud score) should not be used to make decisions that adversely affect individuals without proper due process.
* Consider the digital footprint you leave when running scans — use a dedicated research account and, where possible, a VPN to reduce operational exposure.

### Related Tools:

* Maigret
* Sherlock
* [Have I Been Pwned?](have-i-been-pwned.md)
* [IntelX](intelligencex.md)
* [Hunter.io](http://hunter.io)
* Spokeo
* Pipl
* [OSINT Industries](osint-industries.md)
* [Epieos](epieos.md)

#### Sources

[https://footprintiq.app/](https://footprintiq.app/)&#x20;

[https://footprintiq.app/about-footprintiq](https://footprintiq.app/about-footprintiq)

[https://footprintiq.app/research/media-kit](https://footprintiq.app/research/media-kit)

[https://x.com/Footprint\_IQ](https://x.com/Footprint_IQ)

[https://find.companieshouse.gov.uk/company/14698028](https://find.companieshouse.gov.uk/company/14698028)<br>

_With thanks to Robin Clifford for submitting this tool to the OSINT Tool Library._

<br>
