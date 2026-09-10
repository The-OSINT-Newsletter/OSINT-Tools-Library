---
description: >-
  Tool Description: A source-code search engine that allows investigators to
  search the HTML, JavaScript, CSS and other indexed elements of websites for
  specific words, phrases, code snippets etc.
---

# PublicWWW

| **PublicWWW**    | **Quick Overview**                                                                                                                                             |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://publicwww.com/](https://publicwww.com/)                                                                                                               |
| What it does     | Searches indexed website source code for keywords, code snippets, identifiers, technologies and other technical signatures.                                    |
| How to use it    | Enter a keyword, phrase, code fragment or technical identifier into the search box; use operators such as site:, ip:, filetype: and depth: to refine results.  |
| Cost             | Basic searching is free. Advanced access requires a paid plan.                                                                                                 |
| Account required | No for basic searches. Yes for broader access.                                                                                                                 |
| Cookies          | Mostly site functionality, session management and analytics cookies.                                                                                           |
| Ownership        | Not publicly disclosed.                                                                                                                                        |
| Use in Reporting | Useful for identifying technical links between websites and corroborating relationships through shared code, scripts, identifiers or infrastructure.           |

### What does PublicWWW do?

PublicWWW indexes website source code and allows searches across HTML, JavaScript, CSS, plain text and certain technical information such as HTTP response headers. It can therefore be used to find websites that share particular pieces of code or technical identifiers.

This makes it useful for website attribution, infrastructure research, technical link analysis and discovery of related websites.&#x20;

**The lowdown:** It’s a web-source-code search engine that’s ideal for technical OSINT.

### How to Use:

**1. Enter a keyword, phrase, code snippet, identifier or other technical signature into the PublicWWW search box.**

<img src="../.gitbook/assets/unknown (568).png" alt="" height="127" width="602">

**2. Review the returned websites and source-code snippets to identify common technical features or potential relationships between domains.**

<img src="../.gitbook/assets/unknown (569).png" alt="" height="305" width="602">

**3. Use advanced search operators such as site:, ip:, filetype:css, filetype:js and depth:all to narrow the search and investigate particular technical characteristics.**&#x20;

<img src="../.gitbook/assets/unknown (570).png" alt="" height="271" width="602">

### Cost

* [ ] Free
* [x] Partially Free
* [ ] Paid

Basic searching is free. Advanced access requires a paid plan.

## Data Processing

### Account Required:

* [x] Yes
* [x] No

No for basic searches. Yes for broader access.

### Cookies:&#x20;

PublicWWW uses first-party session/functionality cookies, including PHPSESSID, as well as Matomo analytics cookies (\_pk\_id and \_pk\_ses) to measure website usage. Additional site-specific cookies such as m1, m2, r7 and \_lpg are present, but their precise functions are not publicly documented. These cookies are generally relevant to website operation and analytics rather than the OSINT data returned by searches.

### Use in Reporting

PublicWWW can be used to:

* Identify websites containing a specific keyword, code snippet, script, tracking identifier or other technical signature.
* Discover potentially related websites that share distinctive source code or technical elements.
* Cross-reference domains, analytics IDs, advertising identifiers, JavaScript libraries and other technical indicators.
* Identify websites using the same technology, widget, template or embedded resource.
* Develop leads when investigating websites, online infrastructure, organisations or unknown domains.
* Corroborate technical relationships identified through other OSINT sources.
* Inform further research by identifying additional domains or technical identifiers that can be independently investigated.

As a working example,[ DFRLab explicitly says](https://dfrlab.org/2026/03/31/polskanews-org-a-foreign-influence-operation-masquerading-as-polish-news/) its infrastructure-forensics methodology used PublicWWW to search for shared tracking identifiers and identify related domains re a likely foreign influence operation.

| **Capabilities**                                                                             | **Limitations**                                                                        |
| -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| Searches HTML, JavaScript, CSS and plain-text content in indexed webpages                    | Only searches content that has been indexed by PublicWWW.                              |
| Can identify websites sharing distinctive code, scripts, widgets and technical identifiers.  | A shared piece of code does not necessarily establish common ownership or control.     |
| Supports operators including site:, ip:, filetype: and depth:                                | Free access provides only limited access to the overall database.                      |
| Can search technical characteristics such as server headers and technologies.                | Results may become outdated as websites change their source code.                      |
| Results can be downloaded and the service provides an API on paid plans.                     | Some advanced searches, larger result sets and API functionality require paid access.  |

### Summary

PublicWWW allows investigators to move beyond conventional keyword searches and identify websites that share code, tracking identifiers, widgets, technologies or other distinctive technical characteristics. It best fits within the discovery, enrichment, analysis and verification stages of the OSINT workflow but remember that a technical match should be corroborated with other evidence before making claims about ownership, attribution, or coordination.

### Ownership

Not publicly disclosed.

### Ethical Considerations

* Only investigate websites and technical identifiers for a legitimate and proportionate investigative purpose.
* Treat shared code, analytics IDs or infrastructure as indicators, not proof of common ownership or control.
* Avoid using PublicWWW results alone to make allegations about individuals or organisations.
* Respect applicable UK data-protection requirements and organisational handling policies.

### Related Tools:

* [URLscan](urlscan.md)
* [Shodan](shodan.md)
* [Censys](censys.md)

#### Sources

[https://publicwww.com/](https://publicwww.com/)&#x20;

[https://dfrlab.org/2026/03/31/polskanews-org-a-foreign-influence-operation-masquerading-as-polish-news/](https://dfrlab.org/2026/03/31/polskanews-org-a-foreign-influence-operation-masquerading-as-polish-news/)&#x20;

[https://publicwww.com/terms.html](https://publicwww.com/terms.html)&#x20;
