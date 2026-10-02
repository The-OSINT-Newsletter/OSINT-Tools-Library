---
description: >-
  Tool Description : A free lookup for IP addresses and domain names that
  combines DNS records, hosting provider, ASN, RDAP registration data, mail
  security (SPF/DMARC) and public blocklist listings, with Internet-wide
  statistics and open datasets.
---

# Whoami.xj1.fr

| **Whoami.xj1.fr** | **Quick Overview**                                                                                                                                                                                                  |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL               | [https://whoami.xj1.fr/](https://whoami.xj1.fr/)                                                                                                                                                                    |
| What it does      | Looks up an IP address or a domain name and returns its DNS records, hosting provider and network (ASN), approximate geolocation, RDAP registration data, SPF/DMARC records, public blocklist listings and the other domains on the same IP. |
| How to use it     | Type an IP or a domain in the search box, or open `/ip/<address>` or `/domain/<name>` directly. Add `?format=json` or `?format=text` to any lookup for machine-readable output.                                     |
| Cost              | Free, with fair-use rate limits.                                                                                                                                                                                    |
| Account required  | No.                                                                                                                                                                                                                 |
| Cookies           | No tracking cookies. Analytics are a self-hosted, cookieless Matomo. A theme-preference cookie (`xj1-theme`) is set only if the visitor switches between light and dark theme.                                      |
| Ownership         | An independent, self-hosted project run from France under the xj1.fr domain. Not a company product.                                                                                                                 |
| Use in Reporting  | Useful for identifying who hosts a site and which network announces an IP, spotting shared infrastructure, checking mail spoofing protection, and sourcing infrastructure statistics for reporting.                 |

### What does Whoami.xj1.fr do?

Whoami.xj1.fr is a lookup tool for IP addresses and domain names. For an IP address it shows the reverse DNS name, approximate geolocation, the network (ASN) and company that announce it, any listing in public IP blocklists, and the domains known to resolve to that address. For a domain name it shows the addresses it resolves to, its NS, MX, SPF (TXT) and DMARC records, the hosting, DNS and email providers behind them, registration data from RDAP (registrar, creation and expiry dates, status, DNSSEC) and its Tranco popularity rank.

Domain answers come from a continuously refreshed dataset of more than 90 million domains (registry zone files, popularity lists and Certificate Transparency logs). A domain that is not in the dataset is resolved live.

Beyond single lookups, the site publishes Internet-wide statistics built from the same data: hosting market share by country and by extension, DNS and email provider share, DMARC and SPF adoption, and phishing listings per extension. The aggregates are available as CSV files under a CC BY 4.0 licence, with the method and its limits documented at [https://whoami.xj1.fr/research/](https://whoami.xj1.fr/research/).

**The lowdown:** a quick, no-account first look at the infrastructure behind an IP or a domain, plus ready-made context (who hosts what, how common a setup is) for reporting. It is not a replacement for a live scan engine or a passive DNS history service.

### How to Use:

**1. Enter an IP address or a domain name** in the search box on the home page, or go straight to a URL such as `https://whoami.xj1.fr/ip/8.8.8.8` or `https://whoami.xj1.fr/domain/example.org`.

**2. Read the result:** network and company (ASN), geolocation, DNS and mail records, registration data and blocklist listings. Click an ASN or provider to see its network page and the domains it hosts.

**3. Pivot:** from an IP, open the list of domains on that address; from a provider, open its market share page (`/hosting/`, `/dns/`, `/mail/`).

**4. Export:** append `?format=json` or `?format=text` to the same URL to collect the data in a script.

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

### Cookies:&#x20;

The site sets no tracking cookies. Visit statistics use a self-hosted Matomo instance configured without cookies. A preference cookie named `xj1-theme` (one year, first party) is written only when a visitor switches between light and dark theme.

### Use in Reporting

Whoami.xj1.fr can support reporting by:

* Identifying the hosting company and network behind a website or an IP address.
* Showing how many other domains share an IP, which helps judge whether an address is dedicated or shared hosting.
* Checking whether a domain publishes SPF and an enforced DMARC policy (relevant to spoofing and phishing stories).
* Providing citable, dated statistics on hosting, DNS and email markets, with downloadable CSV files and a documented method.

| **Capabilities**                                                                        | **Limitations**                                                                                          |
| --------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| Combines DNS, ASN, geolocation, RDAP and blocklist data in one page.                    | Geolocation is approximate (city or country level) and says nothing about who operates the site.         |
| No account, JSON and text output on every lookup.                                       | Data comes from a dataset refreshed periodically; very recent changes may not appear.                    |
| Shows other domains on the same IP and provider-level statistics.                       | No passive DNS history and no port or service scanning.                                                  |
| Open CSV datasets (CC BY 4.0) with documented method for hosting, DNS, mail, DMARC.     | Blocklist listings are reported as published by third-party lists and are not verified by the tool.      |

### Summary

Whoami.xj1.fr is a lightweight infrastructure lookup that is most useful at the start of the infrastructure analysis stage of an investigation: you have an IP or a domain and want the hosting company, network, mail setup and registration facts in one place, then move to a scan engine or a passive DNS service for depth. Its research datasets are a useful source when a story needs market-level numbers on hosting, DNS, email security or phishing listings.

### Ownership

Whoami.xj1.fr is an independent, self-hosted project run from France under the xj1.fr domain. It is not backed by a company and has no paid tier.

### Ethical Considerations

* Network or hosting ownership is not the same as responsibility for a site's content or activity, and shared hosting means one IP can serve thousands of unrelated sites.
* Treat geolocation as approximate and never as a person's location.
* Blocklist listings are third-party claims: corroborate them before reporting a domain or an IP as malicious.
* Use the JSON and text outputs within the fair-use limits and avoid bulk scraping; the CSV datasets exist for bulk use.
* Cite the datasets with their snapshot date and distinguish measured counts of domains from traffic or user numbers.

### Related Tools:

* [Shodan](shodan.md)
* [Censys](censys.md)
* [IPinfo](ipinfo.md)
* [ARIN](arin.md)
* [Domain Dossier](domain-dossier.md)
* [DNS Dumpster](dns-dumpster.md)

#### Sources

[https://whoami.xj1.fr/](https://whoami.xj1.fr/)

[https://whoami.xj1.fr/research/](https://whoami.xj1.fr/research/)

[https://github.com/xavfmp/whoami-internet-research](https://github.com/xavfmp/whoami-internet-research)
