---
description: 'Tool Description: A digital footprint checker and public username search tool.'
---

# MyRecon

| **MyRecon**      | **Quick Overview**                                                                                                                |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://www.myrecon.xyz/](https://www.myrecon.xyz/)                                                                              |
| What it does     | Collects public username leads and domain/DNS/IP context in a CLI and web interface.                                              |
| How to use it    | Run the source-pinned review kit or try a guest web lookup. Verify matches at the original source.                                |
| Cost             | Partially Free.                                                                                                                   |
| Account required | No for the local CLI or basic guest web checks. Some hosted features require sign-in or payment.                                  |
| Cookies          | Google Analytics 4 and cookies associated with Google's consent-management system.                                                |
| Ownership        | Aryan Walia / BugSnaps.                                                                                                           |
| Use in Reporting | Useful to evaluate for initial public-profile lead discovery, a consented digital-footprint self-audit, or DNS/domain/IP context. |

### What does MyRecon do?

MyRecon is an MIT-licensed Python CLI, Flask API, and web frontend for public username leads and infrastructure lookups.&#x20;

The platform distinguishes between confirmed-looking results, unavailable checks, and inconclusive results. It also provides source links so that users can investigate whether a match is genuine.

The hosted site has separate guest, signed-in and paid limits. Android is maintained separately and its source is not in this repository. Shared usernames do not establish identity or registration availability.&#x20;

**The lowdown:** It’s particularly useful for digital-footprint investigations, username discovery and preliminary identity research.

### How to Use:

For web:

**1. Enter the username you want to investigate in the search bar.**

<img src="../.gitbook/assets/unknown (848).png" alt="" height="95" width="602">

**2.  Press ‘ Investigate’ and view results. (Only 2 free profiles available without sign in).  Review and verify findings.**&#x20;

**Note:** The links returned here were broken which may be indicative of the accounts either not existing or incorrect links.

<img src="../.gitbook/assets/unknown (849).png" alt="" height="565" width="602">

For Github:

**1. Start with the source-pinned review kit:** [**https://github.com/4ryanwalia/Myrecon/blob/97f976bd120488c7ddd26ce444b88f7931a31ed1/docs/review-kit/README.md**](https://github.com/4ryanwalia/Myrecon/blob/97f976bd120488c7ddd26ce444b88f7931a31ed1/docs/review-kit/README.md)

**2. Run python examples/offline\_demo.py for four explicitly synthetic examples; these are not live accuracy evidence.**

<img src="../.gitbook/assets/unknown (850).png" alt="" height="256" width="602">

**3. In a fresh Python environment, install the pinned minimal dependencies and run a consented username search with the command: python myrecon.py username YOUR USERNAME**

<img src="../.gitbook/assets/unknown (851).png" alt="" height="288" width="602">

**4. Review and verify findings.**

### Cost

* [ ] Free
* [x] Partially Free
* [ ] Paid

MIT-licensed CLI/source. Hosted web interface has free guest and paid limits.

## Data Processing

### Account Required:

* [x] Yes
* [x] No

No for the local CLI or basic guest web checks. Some hosted features require sign-in or payment.

### Cookies:&#x20;

The site uses Google Analytics 4 cookies (\_ga and \_ga\_3L8YYC6NKF) to distinguish website visitors, recognise returning browsers and measure website usage and interactions. It also uses the FCCDCF cookie, associated with Google's Funding Choices and Privacy & Messaging consent-management system, to store privacy and advertising-consent preferences.

### Use in Reporting

MyRecon is useful for:

* Initial lead discovery and infrastructure context.
* Discovering publicly accessible social media accounts, forum profiles and other online accounts associated with a username.
* Investigating whether the same username appears across different platforms and identifying possible connections requiring further verification.
* Examining public profile information, including biographies, avatars, linked websites and other available account details.
* Investigating possible aliases and linked accounts using publicly available profile information and links published by account owners.
* Supporting digital-footprint audits, impersonation investigations, fraud research and authorised security assessments.

| **Capabilities**                                                                     | **Limitations**                                                                                                                                                                       |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Public username outcomes with verdict/reason information.                            | Shared usernames are leads, not identity proof or handle availability.                                                                                                                |
| Domain, DNS, RDAP/WHOIS and IP lookups via source CLI/API.                           | Login walls, blocks, timeouts and source changes can prevent a conclusion.                                                                                                            |
| JSON CLI output for supported lookups.                                               | Interfaces have different coverage and access limits.                                                                                                                                 |
| Synthetic offline verdict examples and a reproducible small live regression harness. | Supplied live sample: only ten fixed usernames on GitHub, GitLab and Hacker News; reference shares API evidence with the engine. Not an independent or full-catalogue accuracy audit. |
| Open repository for inspection and reproducibility.                                  | Sherlock/Maigret packages were not installed for the supplied run; their results are unavailable, not comparative scores.                                                             |
| <p><br></p>                                                                          | No Android device test or independent privacy audit is claimed.                                                                                                                       |

### Summary

MyRecon is a candidate for public-profile lead generation and initial infrastructure triage, with inspectable source and explicit unknown outcomes. Its practical value depends on platform availability and manual verification.&#x20;

### Ownership

MyRecon is developed by Aryan Walia at BugSnaps.&#x20;

The repository names Aryan Walia and aryan@bugsnaps.in as author/contact.

The operator's principal place of business is listed as Gurugram, India.

### Ethical Considerations

* Test only accounts you control or are authorised to investigate.
* Do not attribute accounts to a person using a shared handle alone.
* Minimise collected data and redact private identifiers and credentials.
* Respect provider restrictions and retain inconclusive outcomes.

### Related Tools:

* Sherlock
* [OSINT Industries](osint-industries.md)
* Maigret
* [WhatsMyName](whatsmyname.md)

#### Sources

[https://www.myrecon.xyz/](https://www.myrecon.xyz/)&#x20;

[https://github.com/4ryanwalia/Myrecon](https://github.com/4ryanwalia/Myrecon)&#x20;

[https://github.com/4ryanwalia/Myrecon/blob/97f976bd120488c7ddd26ce444b88f7931a31ed1/docs/review-kit/README.md](https://github.com/4ryanwalia/Myrecon/blob/97f976bd120488c7ddd26ce444b88f7931a31ed1/docs/review-kit/README.md)&#x20;

[https://www.myrecon.xyz/privacy.html](https://www.myrecon.xyz/privacy.html)&#x20;

[https://www.myrecon.xyz/cookies.html](https://www.myrecon.xyz/cookies.html)  <br>

_With thanks to Aryan Walia for submitting this tool the OSINT Tool Library._
