---
description: >-
  Tool Description : A bot-signature lookup service that checks names, email
  addresses & IP addresses against a database of previously identified bot
  activity.
---

# BotScout

| **BotScout**     | **Quick Overview**                                                                                                                                  |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://botscout.com/search.htm](https://botscout.com/search.htm)                                                                                  |
| What it does     | Checks names, emails and IPs against known bot signatures.                                                                                          |
| How to use it    | Search an identifier and review any BotScout matches.                                                                                               |
| Cost             | Free for normal use. Higher-volume/API use may have limits or charges.                                                                              |
| Account required | No for basic searches. API access requires an API key.                                                                                              |
| Cookies          | A functional/session cookie.                                                                                                                        |
| Ownership        | Not publicly disclosed.                                                                                                                             |
| Use in Reporting | Most useful as a supporting verification step when assessing whether an online account, registration or interaction may be automated or malicious.  |

### What does BotScout do?

BotScout maintains a database of bot signatures made up of names, email addresses and IP addresses associated with previously detected automated activity. You can search these identifiers manually or query the database through its API.&#x20;

**The lowdown:** It’s particularly useful for checking whether an identifier associated with a suspicious account or online interaction has previously appeared in BotScout's database.&#x20;

**Note:** A match can indicate an email address, username or IP has previously been associated with bot activity, but it does not by itself prove that the current user, account or activity is automated.

### How to Use:

**1. Identify an indicator to investigate such as a username, email address, or IP address, then simply enter this indicator into the search bar.**&#x20;

<img src="../.gitbook/assets/unknown (480).png" alt="" height="280" width="602">

**2. Run the search and review whether it has previously appeared in the BotScout database. BotScout also supports separate API checks for email, IP and name, as well as combined queries.**&#x20;

<img src="../.gitbook/assets/unknown (481).png" alt="" height="468" width="602">

**3. Record the result, including the identifier searched, match status and any relevant returned information. Treat a match as supporting evidence, then corroborate it with other OSINT sources before reporting an assessment.**<br>

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

Free for normal use. Higher-volume/API use may have limits or charges.&#x20;

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

No for basic searches. API access requires an API key.

### Cookies:&#x20;

The site uses a PHPSESSID session cookie for maintaining a temporary PHP web session. (The cookie is functional rather than an advertising/tracking identifier based on its name and function).

### Use in Reporting

BotScout can be used to:

* Check usernames, email addresses and IP addresses for previous bot-related matches.
* Investigate identifiers associated with suspected automated, spam or malicious activity.
* Identify whether an identifier has previously appeared in BotScout's bot-signature database.
* Corroborate findings from other OSINT, threat-intelligence and account-analysis sources.
* Document searched identifiers, match results, match counts and search dates as supporting evidence.
* Support assessments of potentially automated or suspicious online activity.
* Inform risk assessments when profiling accounts, email addresses, IP addresses or online activity.

For example, in a [2017 SC Media investigation](https://www.scworld.com/perspective/floki-bot-a-zeus-wannabe-with-delusions-of-grandeur) into ‘Floki Bot’ (a Zeus-inspired malware.botnet), researchers used BotScout to investigate an IP associated with suspected botnet infrastructure and obtained information including registrant email addresses. The BotScout results were then considered alongside VirusTotal and other evidence to assess whether the IP was being used as a command-and-control server.

| **Capabilities**                                                       | **Limitations**                                                                 |
| ---------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| Checks usernames against known bot signatures.                         | A match does not prove that the current account is a bot.                       |
| Checks email addresses associated with previous bot activity.          | Coverage depends on what BotScout has previously observed and recorded.         |
| Checks IP addresses for previous bot activity.                         | IP addresses can be shared, reassigned or associated with compromised systems.  |
| Supports combined name, email and IP queries through the API.          | BotScout states that it cannot catch every bot.                                 |
| Provides match information that can support investigative hypotheses.  | Query/API limits may restrict large-scale investigations.                       |

### Summary

BotScout’s strongest OSINT use is in the verification/enrichment stage of the workflow, after an investigator has identified an account, email address or IP and wants an additional indication of previous bot activity.&#x20;

**Note:** A positive match can strengthen a hypothesis that an identifier has been associated with automated activity, while a negative result should not be interpreted as evidence that the identifier is legitimate or human.

### Ownership

Not publicly disclosed.

### Ethical Considerations

* Only investigate identifiers for a legitimate and proportionate investigative purpose.
* Treat BotScout matches as indicators, not proof of maliciousness, automation or identity.
* Avoid unnecessarily submitting or recording personal data.
* Consider applicable UK data-protection requirements and organisational handling policies.
* Do not use BotScout results alone to make decisions that could materially affect an individual.

### Related Tools:

* VirusTotal
* AlienVault OTX
* GreyNoise

#### Sources

[https://botscout.com/search.htm](https://botscout.com/search.htm)&#x20;

[https://botscout.com/about.htm](https://botscout.com/about.htm)&#x20;

[https://www.scworld.com/perspective/floki-bot-a-zeus-wannabe-with-delusions-of-grandeur](https://www.scworld.com/perspective/floki-bot-a-zeus-wannabe-with-delusions-of-grandeur)
