---
description: >-
  Tool Description : A simple OSINT tool that checks whether a username has been
  observed on known cybercriminal forums and underground platforms.
---

# Threat Actor Username Search

<table data-header-hidden><thead><tr><th width="259"></th><th></th></tr></thead><tbody><tr><td><strong>Threat Actor Username Search</strong></td><td><strong>Quick Overview</strong></td></tr><tr><td>URL</td><td><a href="https://threatactorusernames.com/">https://threatactorusernames.com/</a> </td></tr><tr><td>What it does</td><td>Checks whether a username has been observed on cybercriminal forums and underground platforms. </td></tr><tr><td>How to use it</td><td>Enter a username and review whether a match exists and, if so, the associated platforms. </td></tr><tr><td>Cost</td><td>Free.</td></tr><tr><td>Account required</td><td>No.</td></tr><tr><td>Cookies</td><td>Minimal/none logged during our site visit.</td></tr><tr><td>Ownership</td><td>Not publicly disclosed.</td></tr><tr><td>Use in Reporting</td><td>Useful for enriching threat actor profiles, validating aliases and identifying investigative leads </td></tr></tbody></table>

### What does Threat Actor Username Search do?

Threat Actor Username Search allows you to check if a username is associated with a threat actor. Unlike tools such as Sherlock, which search for usernames across public websites, Threat Actor Username Search simply answers whether the username appears within its threat intelligence dataset with a true/false result.&#x20;

**The lowdown:** It can quickly identify whether an alias has appeared on known hacking forums or marketplaces.

### How to Use:

**1. Simply enter the username or alias you wish to investigate and submit the search.**

<img src="../.gitbook/assets/unknown (284).png" alt="" height="432" width="602">

**2. Review whether a match exists and note any associated forums or platforms. Use those locations as pivots for additional OSINT, forum analysis or corroboration using other intelligence sources.**<br>

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

### Cookies:&#x20;

Minimal/none used during our site visit on 29 June 2026.

### Use in Reporting

Threat Actor Username Search is particularly useful for:

* Enriching threat actor or persona profiles.
* Supporting attribution hypotheses alongside other indicators.
* Identifying additional underground forums for manual investigation.
* Corroborating usernames recovered from malware analysis, data breaches or incident response.
* Demonstrating links between aliases observed across multiple intelligence sources.

**Note:** As always, findings should always be corroborated using additional intelligence sources before inclusion in formal reporting. Community discussions around the tool also emphasise that it should be treated as a starting point rather than standalone attribution evidence.

| **Capabilities**                                                                          | **Limitations**                                                                                                        |
| ----------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| Quickly determines whether a username has been observed within cybercriminal communities. | Does not prove the individual using the username is a threat actor.                                                    |
| Identifies forums/underground platforms where the username has appeared.                  | Returns a binary match/no-match rather than detailed profile information.                                              |
| Useful for enriching threat actor profiles and linking aliases across investigations.     | Shared/common usernames can lead to false assumptions if results are not verified.                                     |
| Supports both manual lookups and API integration for automation.                          | Coverage is limited to platforms included within the service’s dataset.                                                |
| Simple interface with no registration required for basic searches.                        | Does not provide supporting metadata such as email addresses, crypto wallets, or IP addresses for further attribution. |

### Summary

Threat Actor Username Search is most valuable during the analysis and enrichment stage of an OSINT investigation, after a username or alias has already been identified. However, results should always be corroborated with other sources.

### Ownership

Independent OSINT project. No detailed ownership information is publicly disclosed.

### Ethical Considerations

* A username match does not confirm that an individual is a threat actor or involved in criminal activity.
* Usernames are often reused across multiple platforms and may belong to different individuals.
* Some usernames may belong to legitimate researchers, journalists or law enforcement personnel who access cybercrime forums for professional purposes.
* Always corroborate findings with additional intelligence sources before making attribution or investigative decisions.
* Clearly distinguish between observed associations and verified evidence when reporting.
* Ensure any collection, storage and sharing of findings complies with relevant legal, organisational and privacy requirements.

### Related Tools:

* Sherlock
* Holehe
* [Intelligence X](intelligencex.md)
* [WhatsMyName](whatsmyname.md)

#### Sources

[https://threatactorusernames.com/](https://threatactorusernames.com/)&#x20;

[https://threatactorusernames.com/faq](https://threatactorusernames.com/faq) [https://www.reddit.com/r/threatintel/comments/1om6sns/threat\_actor\_username\_scrape\_project\_230k/](https://www.reddit.com/r/threatintel/comments/1om6sns/threat_actor_username_scrape_project_230k/)&#x20;

[https://apify.com/dev00/threat-actor-username-search-api](https://apify.com/dev00/threat-actor-username-search-api)&#x20;
