---
description: >-
  Tool Description : A free browser-based email investigation and
  troubleshooting tool that examines the technical headers of an email.
---

# Email Header Analyzer

| **Email Header Analyzer** | **Quick Overview**                                                                                                                                                                                  |
| ------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL                       | [https://mailboxinsights.com/email-header-analyzer/](https://mailboxinsights.com/email-header-analyzer/)                                                                                            |
| What it does              | Analyzes pasted email headers: SPF/DKIM/DMARC, delivery path, and spoofing/phishing signs.                                                                                                          |
| How to use it             | Paste raw email headers into the box and click Analyze headers.                                                                                                                                     |
| Cost                      | Free.                                                                                                                                                                                               |
| Account required          | No.                                                                                                                                                                                                 |
| Cookies                   | Cookies are predominantly associated with Google account security, Google's consent management & location-based search personalisation, plus Comscore/ScorecardResearch audience measurement.       |
| Ownership                 | Mailbox Insights, founded by Dinesh Kumar.                                                                                                                                                          |
| Use in Reporting          | Useful for examining suspicious emails, checking sender authentication, reviewing delivery routes, identifying possible spoofing and phishing indicators, and documenting technical email evidence. |

### What does Email Header Analyzer do?

The free web tool that turns raw email headers into a clear report: checks SPF, DKIM and DMARC results, traces the hop-by-hop delivery path between mail servers, and flags spoofing and phishing warning signs such as mismatched senders.&#x20;

An LLM explains the results in plain language. Authentication checks (SPF, DKIM, DMARC) are done in code; the LLM is used only to explain the findings. It also decodes Microsoft 365 spam stamps (SCL, BCL, spam category) and shows the delay at each hop.

**The lowdown:** Rather than examining the visible message content, the tool concentrates on the technical metadata that accompanies an email.

### How to Use:

**1. Get the raw headers (Gmail: three dots > Show original; Outlook: File > Properties > Internet headers; new Outlook/web: three dots > View > View message details).**

<img src="../.gitbook/assets/Pasted image 2026-11-16 10.30.05.png" alt="" height="235" width="602">

**2. Open https://mailboxinsights.com/email-header-analyzer/ and paste the headers into the box and select Analyze headers.**

<img src="../.gitbook/assets/Pasted image 2026-11-16 10.30.32.png" alt="" height="165" width="602">

**3. Review the authentication results, delivery route and warning signs.**

<img src="../.gitbook/assets/Pasted image 2026-11-16 10.30.56.png" alt="" height="177" width="602">

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

### Cookies:&#x20;

Google cookies (SID, SIDCC, SOCS and SSID) were observed during browsing. SID and SSID support Google account authentication and security, while SIDCC provides additional session protection. SOCS stores Google privacy and consent preferences.

Google's UULE cookie provides geographical context for location-based search personalisation. Third-party ScorecardResearch cookies (UID and XID) support pseudonymous visitor recognition and digital audience measurement through Comscore.

### Use in Reporting

Email Header Analyzer is useful for:

* Examining suspicious emails and identifying technical characteristics that may indicate phishing or spoofing.
* Checking SPF, DKIM and DMARC authentication results to assess whether a sending domain's email authentication checks passed.
* Investigating discrepancies between the displayed sender address, envelope sender and Reply-To address.
* Reviewing the mail-server route to identify the systems involved in delivering an email.
* Identifying delays between mail servers and establishing a more detailed delivery timeline.
* Interpreting Microsoft 365 SCL, BCL and spam-filter information to understand how a message was classified.
* Identifying suspicious or unexpected sending infrastructure for further investigation.
* Recording technical email evidence to support phishing investigations, cybercrime research and digital-forensics reporting.

| **Capabilities**                                                               | **Limitations**                                                                                      |
| ------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------- |
| Hop-by-hop delivery route with delay per hop.                                  | Analyzes only the headers you paste, not the message body or attachments.                            |
| Warning signs: Reply-To mismatch, failed alignment, other phishing indicators. | Headers can be forged, so results are indicators, not proof.                                         |
| Microsoft 365 spam stamp decoding (SCL, BCL, spam category).                   | LLM explanations may contain errors and should be verified against the raw headers.                  |
| Plain-language explanation from an LLM.                                        | Microsoft-specific spam stamps are not necessarily available in emails processed by other providers. |

### Summary

Email Header Analyzer helps review sender authentication, identify possible spoofing indicators, examine mail-server routes, and interpret Microsoft 365 spam-filter information.

Its main strength is making complex email headers easier to understand without requiring extensive knowledge of email infrastructure, and is most useful for email investigation and phishing/spoofing triage.

Its results should be preserved alongside the original email and corroborated with independent technical evidence before conclusions are drawn about the sender or authenticity of a message.

### Ownership

Owned and built by Dinesh Kumar, an IT infrastructure specialist with 20+ years of experience in email systems, Exchange Server and Microsoft 365, and founder of the Mailbox Insights website (https://mailboxinsights.com).

### Ethical Considerations

* Email headers contain IP addresses, server names and email addresses; handle as personal data.
* Share only headers you are entitled to analyze.
* Do not paste the message body or sensitive content.
* Treat results as indicators, not proof of identity or intent.

### Related Tools:

* MXToolbox Email Header Analyzer
* Google Admin Toolbox Messageheader
* DNSChecker

#### Sources

[https://mailboxinsights.com/email-header-analyzer/](https://mailboxinsights.com/email-header-analyzer/)&#x20;

[https://mailboxinsights.com/about/](https://mailboxinsights.com/about/)&#x20;

[https://mailboxinsights.com/privacy-policy/](https://mailboxinsights.com/privacy-policy/)&#x20;

[https://knowledge.workspace.google.com/admin/security/set-up-spf?visit\_id=639299099603652614-4228926652\&rd=1](https://knowledge.workspace.google.com/admin/security/set-up-spf?visit_id=639299099603652614-4228926652\&rd=1)&#x20;

[https://knowledge.workspace.google.com/admin/security/set-up-dkim?visit\_id=639299099773506863-2340203600\&rd=1](https://knowledge.workspace.google.com/admin/security/set-up-dkim?visit_id=639299099773506863-2340203600\&rd=1)&#x20;

[https://learn.microsoft.com/en-us/defender-office-365/message-headers-eop-mdo](https://learn.microsoft.com/en-us/defender-office-365/message-headers-eop-mdo) [https://learn.microsoft.com/en-us/defender-office-365/email-authentication-about](https://learn.microsoft.com/en-us/defender-office-365/email-authentication-about)



_With thanks to Dinesh Kumar for submitting this tool for the OSINT Tool Library._
