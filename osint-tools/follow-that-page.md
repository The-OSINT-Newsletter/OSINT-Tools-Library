---
description: >-
  Tool Description : A web-monitoring service that tracks specified webpages and
  sends notifications when changes are detected.
---

# Follow That Page

| **Follow That Page** | **Quick Overview**                                                                                                                        |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| URL                  | [https://www.followthatpage.com/](https://www.followthatpage.com/)                                                                        |
| What it does         | Monitors webpages for changes and sends email notifications when changes are detected.                                                    |
| How to use it        | Enter the URL of the webpage to monitor, provide an email address, and configure monitoring options.                                      |
| Cost                 | Partially Free.                                                                                                                           |
| Account required     | Yes, to manage ongoing page monitoring.                                                                                                   |
| Cookies              | Mainly older Google Analytics cookies, plus a PHP session cookie.                                                                         |
| Ownership            | Operated by Onno Zweers (based in Amsterdam) as a personal/hobby project.                                                                 |
| Use in Reporting     | Useful for monitoring webpages, tracking changes over time, and identifying new information or amendments to publicly available sources.  |

### What does Follow That Page do?

Follow That Page automatically checks webpages and sends an email when it detects changes, showing text that has been added or removed. The service can therefore be useful when an investigator needs to monitor a webpage over an extended period rather than repeatedly checking it manually.&#x20;

**The lowdown:** It’s a web-change detection and notification tool.<br>

### How to Use:

**1. Enter the URL of the webpage you want to monitor together with an email address. You’ll need to sign up for an account if you don’t already have one.**

<img src="../.gitbook/assets/unknown (533).png" alt="" height="472" width="602">

**2. Once you’ve confirmed your account details and logged in, you’ll be directed to configure the monitoring options. Filters can be used to focus on particular keywords or sections of a webpage and reduce notifications caused by irrelevant changes.**&#x20;

<img src="../.gitbook/assets/unknown (534).png" alt="" height="615" width="602">



**3. Review the email notifications when changes are detected. The service reports text that has been added or removed, allowing the investigator to identify potentially significant updates and preserve the relevant information for further verification.**

### Cost

* [ ] Free
* [x] Partially Free
* [ ] Paid

Free tier available alongside paid pro account.

## Data Processing

### Account Required:

* [x] Yes
* [ ] No

An account is required to manage ongoing page monitoring.

### Cookies:&#x20;

The site uses legacy Google Analytics cookies, including \_\_utma, \_\_utmb, \_\_utmc, \_\_utmt and \_\_utmz, to measure website visits, sessions and traffic sources. It also uses a PHPSESSID session cookie to maintain the user's temporary website session. These cookies are primarily related to website analytics and functionality and do not form part of the webpage-monitoring data collected by the service.

### Use in Reporting

Follow That Page can be used to:

* Monitor publicly accessible webpages for subsequent changes.
* Identify when information on a webpage has been added, removed or amended.
* Track changes to government, corporate, regulatory or organisational webpages.
* Identify potential developments that warrant further investigation.
* Establish a timeline showing when publicly available information changed.
* Receive automated notifications rather than repeatedly checking a source manually.
* Focus monitoring on particular keywords or sections of a webpage using filters.
* Support preservation and verification of information that subsequently changes or disappears.
* Generate investigative leads from changes to publicly available information.

**Potential OSINT applications include monitoring:**

* Government webpages and public notices.
* Company websites and corporate announcements.
* Regulatory or policy pages.
* News and press-release pages.
* Public profiles or organisational webpages.
* Job advertisements and procurement pages.
* Pages containing information relevant to an ongoing investigation.

| **Capabilities**                                                      | **Limitations**                                                                                               |
| --------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| Monitors publicly accessible webpages for changes.                    | It cannot monitor password-protected webpages.                                                                |
| Sends email notifications when changes are detected.                  | The service doesn’t execute JavaScript, Java or Flash, so dynamically generated content may not be captured.  |
| Reports added and removed text.                                       | Changes can be missed if they occur and are subsequently reversed before the service checks the page.         |
| Supports keyword and block filtering.                                 | Websites can block the monitoring service's crawler.                                                          |
| Can monitor pages at different frequencies depending on the account.  | Monitoring frequency and capacity are subject to account limits.                                              |

### Summary

Follow That Page’s main value is in the monitoring and collection stages of the OSINT workflow, particularly where an investigator needs to establish whether information on a webpage has changed over time. It’s particularly useful for long-running investigations because it reduces the need for manual, repeated checking of websites.&#x20;

However, detected changes should be independently verified and preserved where they’re important to an investigation.

### Ownership

Operated by [Onno Zweers](https://www.linkedin.com/in/onnozweers/) as a personal/hobby project. He states he works at [SURFsara](https://www.surfsara.nl/) (Dutch) as a systems programmer.

### Ethical Considerations

* Only monitor webpages that are publicly accessible and relevant to a legitimate investigative purpose.
* Avoid excessive monitoring frequencies that could place unnecessary load on smaller websites.
* Do not attempt to circumvent authentication or access controls.
* Do not provide passwords or session cookies for protected websites.
* Preserve the original URL, date/time and relevant webpage content when documenting an important change.
* Be aware that email reports may contain information about which webpages are being monitored; Follow That Page itself warns that its email reports may be sent in plain text.

### Related Tools:

* Visualping
* Wachete
* [Wayback Machine](wayback-machine.md)
* [Anna’s Archive](annas-archive.md)

#### Sources

[https://www.followthatpage.com/](https://www.followthatpage.com/)&#x20;

[https://www.followthatpage.com/faq](https://www.followthatpage.com/faq)&#x20;

[https://www.surf.nl/](https://www.surf.nl/)&#x20;

[https://www.linkedin.com/in/onnozweers/](https://www.linkedin.com/in/onnozweers/)&#x20;
