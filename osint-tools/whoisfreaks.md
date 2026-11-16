---
description: >-
  Tool Description : A domain and IP intelligence platform for investigating
  internet infrastructure.
---

# WhoisFreaks

| **WhoisFreaks**  | **Quick Overview**                                                                                                                                                                           |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://whoisfreaks.com/](https://whoisfreaks.com/)                                                                                                                                         |
| What it does     | Helps discover who registered a domain, when, and what else they own. It provides current and historical WHOIS records, reverse WHOIS, DNS history, subdomains and SSL data.                 |
| How to use it    | Enter a domain, IP, email, name or keyword in the web tools, or call the REST API with an API key.                                                                                           |
| Cost             | Partially Free.                                                                                                                                                                              |
| Account required | Yes for full results and API access. No for some web lookups but with limited results.                                                                                                       |
| Cookies          | Google account/security cookies, a WhoisFreaks timezone preference and a third-party Tawk.to live-chat visitor cookie.                                                                       |
| Ownership        | Commercial service. Site footer states it is made in Lahore, Pakistan.                                                                                                                       |
| Use in Reporting | Investigating domain registration, identifying associated infrastructure, examining historical DNS and WHOIS changes, checking IP reputation and identifying potentially suspicious domains. |

### What does WhoisFreaks do?

WhoisFreaks is a domain and IP intelligence service. It returns parsed WHOIS records for domains across 7,839 TLDs, plus WHOIS for IP addresses and ASNs. Its historical WHOIS database (4.6B+ snapshots, going back to 1986) shows every recorded change in a domain's registrant, registrar, nameservers and dates, including pre-GDPR registrant details that current lookups now redact.

Reverse WHOIS lets you search by email, name, company or keyword to find other domains registered by the same party. DNS lookup, DNS history and reverse DNS show where a domain pointed over time and which domains share an IP or nameserver. Subdomain, SSL certificate, domain availability, typosquatting and domain reputation tools round it out.

**The lowdown:** It’s particularly useful for investigating the technical infrastructure behind websites, online services, and potentially suspicious domains.

### How to Use:

**1. Enter a domain name into the platform and click search.**

<img src="../.gitbook/assets/Pasted image 2026-11-16 10.18.18.png" alt="" height="215" width="602">

**2. Review the timeline of WHOIS snapshots: registrant, registrar, nameservers and dates for each change. Without an account only the first record is shown so you'll need to sign in to see the full history.**

<img src="../.gitbook/assets/Pasted image 2026-11-16 10.18.50.png" alt="" height="228" width="602">

**3. Take an email, name, or organisation from an older record and search it in Reverse WHOIS (https://whoisfreaks.com/tools/whois/reverse/search) to find other domains registered by the same party.**

<img src="../.gitbook/assets/Pasted image 2026-11-16 10.19.29.png" alt="" height="311" width="602">



**4. Use DNS History (https://whoisfreaks.com/tools/dns/history/lookup) to see past IPs and nameservers, then Reverse DNS to find domains sharing that infrastructure.**

<img src="../.gitbook/assets/Pasted image 2026-11-16 10.19.56.png" alt="" height="239" width="602">

**5. For bulk or automated work, create an account, get an API key and use the REST API: https://whoisfreaks.com/documentation**                                            &#x20;

### Cost

* [ ] Free
* [x] Partially Free
* [ ] Paid

Limited free web lookups. 500 one-time API credits on signup, paid plans after.

## Data Processing

### Account Required:

* [x] Yes
* [x] No

Yes for full results and API access. Some web lookups work without an account but show limited results.

### Cookies:&#x20;

The site uses a first-party timezone cookie to store the user's timezone preference, with the captured value Europe/London indicating the timezone used for displaying localised dates and times.&#x20;

Google cookies (SEARCH\_SAMESITE, SID, SIDCC, SOCS and SSID) were also observed during browsing and are associated with Google's search, authentication, security and privacy-consent functions.&#x20;

A Tawk.to-style twk\_uuid visitor-identification cookie was observed on the third-party .ipgeolocation.io domain, supporting live-chat visitor recognition.&#x20;

### Use in Reporting

WhoisFreaks can be used to:&#x20;

* Establish when a domain was created, updated and by which registrar.
* Recover older, pre-GDPR registrant names, emails and organisations from historical records to link a domain to a person or company.
* Pivot with Reverse WHOIS to find other domains registered with the same email, name or organisation.
* Use DNS history and reverse DNS to map shared hosting and track infrastructure changes over time.
* Find typosquatting and lookalike domains in phishing and brand-impersonation investigations.

| **Capabilities**                                                 | **Limitations**                                                                                                                         |
| ---------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| Live WHOIS lookup across 7,839 TLDs, plus IP and ASN WHOIS.      | Since GDPR, most current WHOIS records redact registrant details; historical records only help where older, unredacted snapshots exist. |
| Historical WHOIS: 4.6B+ snapshots going back to 1986.            | Coverage depends on what each registry publishes; some country-code TLDs return few fields or none.                                     |
| Reverse WHOIS by email, name, company or keyword.                | Without an account, web lookups show limited results (e.g. only the first historical record).                                           |
| DNS lookup, DNS history and reverse DNS / reverse IP.            | Free API credits are one-time; regular or bulk use is paid.                                                                             |
| Subdomain discovery and SSL certificate lookup.                  | Historical records reflect what was published at the time and can include privacy-proxy details or outdated information.                |
| Domain availability, typosquatting and domain reputation checks. | <p><br></p>                                                                                                                             |
| Newly registered, expiring and dropped domain feeds.             | <p><br></p>                                                                                                                             |
| REST API, bulk lookups and downloadable datasets.                | <p><br></p>                                                                                                                             |

### Summary

WhoisFreaks is most useful at the domain-attribution and infrastructure-mapping stage of an investigation: finding who registered a domain, who owned it before, and which other domains and hosts are connected to it.&#x20;

Its main strengths are the depth of historical WHOIS and the reverse WHOIS and DNS history pivots. Its main weaknesses are GDPR redaction in current records, uneven ccTLD coverage, and the need for an account or paid plan to see full results.

### Ownership

WhoisFreaks is a commercial service. Its website footer states it is made in Lahore, Pakistan and it’s part of the same product family as IPGeolocation.io and APIFreaks.

**Disclosure:** This entry was submitted by a member of the WhoisFreaks team.

### Ethical Considerations

* WHOIS records, especially historical ones, can contain personal data of private individuals; handle it under applicable data-protection law (e.g. GDPR).
* Past ownership does not prove current ownership; confirm attribution with more than one source before naming a person or organisation.
* Shared emails or hosting can produce false links between unrelated parties; corroborate pivots.
* Queries are sent to a third-party provider; consider operational security for sensitive cases.

### Related Tools:

* WHOIS API&#x20;
* Whoisology
* [DNS Dumpster](dns-dumpster.md)
* [ActiveDNS](activedns.md)

#### Sources

[https://whoisfreaks.com/](https://whoisfreaks.com/)&#x20;

[https://whoisfreaks.com/tools/whois/history/lookup](https://whoisfreaks.com/tools/whois/history/lookup)&#x20;

[https://whoisfreaks.com/tools/whois/reverse/search](https://whoisfreaks.com/tools/whois/reverse/search)&#x20;

[https://whoisfreaks.com/tools/dns/history/lookup](https://whoisfreaks.com/tools/dns/history/lookup)&#x20;

[https://whoisfreaks.com/documentation](https://whoisfreaks.com/documentation)&#x20;

[https://whoisfreaks.com/privacy-policy](https://whoisfreaks.com/privacy-policy)&#x20;

[https://x.com/whoisfreaks](https://x.com/whoisfreaks)&#x20;

[https://www.linkedin.com/company/whoisfreaks/](https://www.linkedin.com/company/whoisfreaks/)&#x20;



_With thanks to Furqan Ashraf for submitting this tool to the OSINT Tool Library._
