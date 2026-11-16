---
description: >-
  Tool Description : An IP intelligence platform that provides geographic,
  network and technical information about IPv4 and IPv6 addresses.
---

# IPGeolocation.io

| **IPGeolocation.io** | **Quick Overview**                                                                                                                                                           |
| -------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL                  | [https://ipgeolocation.io/](https://ipgeolocation.io/)                                                                                                                       |
| What it does         | Looks up IP addresses and provides approximate geographic location, network ownership, ASN, timezone and other technical information.                                        |
| How to use it        | Enter an IP address into one of the web lookup tools, or call the REST API with an API key. Review the returned location and network information.                            |
| Cost                 | Partially Free.                                                                                                                                                              |
| Account required     | Yes for the API (free account and key). Web tools are available on the public site                                                                                           |
| Cookies              | Cloudflare/Apollo-related security infrastructure, Google Analytics and advertising measurement, first-party visit attribution, and Tawk.to live-chat functionality cookies. |
| Ownership            | Commercial service, running since 2017. Site footer states it is made in Lahore, Pakistan.                                                                                   |
| Use in Reporting     | Useful for enriching IP addresses found in online activity, suspicious emails, server logs, website infrastructure and cyber investigations.                                 |

### What does IPGeolocation.io do?

IPGeolocation.io is an IP intelligence service. Given an IPv4 or IPv6 address, it returns the approximate country, region, city and coordinates, plus the ISP, organisation, ASN, timezone and local currency. The security module (paid) adds VPN, proxy, Tor and bot detection with a threat score, and separate APIs cover ASN details with abuse contacts, timezone lookup, and user-agent parsing.

Data is available through a REST API, bulk lookups and downloadable databases, so it can be used for one-off checks or for enriching large log files offline.

**The lowdown:** It helps you understand the technical and geographic context of an IP address encountered during an investigation.

### How to Use:

**1. Enter the IP address you want to check and run the lookup in the web tool.**

<img src="../.gitbook/assets/Pasted image 2026-11-16 10.25.07.png" alt="" height="263" width="602">

**2. Review the location, ISP, organisation, ASN and timezone fields. Treat city-level results as approximate.**<br>

<img src="../.gitbook/assets/Pasted image 2026-11-16 10.25.41.png" alt="" height="479" width="566">

**3. For repeated or bulk lookups, sign up for a free account, copy your API key and call the API, e.g.** [**https://api.ipgeolocation.io/v3/ipgeo?apiKey=YOUR\_KEY\&ip=8.8.8.8**](https://api.ipgeolocation.io/v3/ipgeo?apiKey=YOUR_KEY\&ip=8.8.8.8)<br>

**4. Use the ASN details and abuse contact to identify the network operator, and (on paid plans) the security fields to check for VPN, proxy or Tor use.**

API docs: [https://ipgeolocation.io/documentation/ip-location-api.html](https://ipgeolocation.io/documentation/ip-location-api.html)&#x20;

### Cost

* [ ] Free
* [x] Partially Free
* [ ] Paid

1,000 API requests/day free. VPN/proxy detection and higher volumes are paid.

## Data Processing

### Account Required:

* [x] Yes
* [x] No

Yes for the API (free account and key). No for web tools which are available on the public site.

### Cookies:&#x20;

IPGeolocation.io uses Google Analytics cookies (\_ga and \_ga\_KP1S0MVDZG) to distinguish website visitors, recognise returning browsers and measure website usage. It also uses the Google advertising cookie (\_gcl\_au) for advertising conversion measurement.

The first-party ipg\_attr cookie stores website attribution information, including the initial visit timestamp, landing page and recorded page paths. Tawk.to cookies (TawkConnectionTime and twk\_uuid\_\*) support live-chat connection management and returning-visitor recognition.

An f\_bm cookie was also observed on the third-party .apollo.io domain.

### Use in Reporting

IPgeolocation.io is useful for:&#x20;

* Identifying the network, ISP and approximate location behind IPs found in server logs, email headers or leaked data.
* Checking whether an IP belongs to a hosting provider, VPN, proxy or Tor exit node before drawing conclusions about a person's location.
* Using ASN and abuse-contact data to identify who operates infrastructure linked to phishing, scams or malware.
* Enriching large lists of IPs in bulk for pattern analysis (shared providers, regions, timezones).

| **Capabilities**                                                                                         | **Limitations**                                                                                                                    |
| -------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| IPv4 and IPv6 lookup: country, region, city, coordinates, ISP, organisation, ASN, timezone and currency. | IP geolocation is approximate: city-level results can be off, and mobile, satellite and carrier-grade NAT IPs are harder to place. |
| VPN, proxy, Tor and bot detection with threat scoring (paid).                                            | An IP's location is where the network routes from, not necessarily where a person is.                                              |
| ASN lookup with abuse contacts.                                                                          | VPN/proxy/Tor detection is only on paid plans in the API.                                                                          |
| Timezone, astronomy and user-agent parsing APIs.                                                         | The free plan is capped at 1,000 requests a day. Databases and higher volumes are paid.                                            |
| Bulk IP lookup.                                                                                          | IP assignments change over time, so results reflect current data, not where an IP was on a past date.                              |
| Downloadable IP geolocation and security databases for offline use.                                      | <p><br></p>                                                                                                                        |
| Responses in 13 languages; 13 official SDKs.                                                             | <p><br></p>                                                                                                                        |

### Summary

IPGeolocation.io is most useful early in network-focused investigations: turning raw IP addresses into an approximate location, an ISP or hosting provider, and an ASN owner, and flagging anonymised traffic.&#x20;

It’s best used as a supporting source in an investigation. An IP address's reported location should never be treated as proof of where a person was physically located, and important findings should be corroborated using other technical and documentary evidence.

### Ownership

IPGeolocation.io is a commercial service that has been running since 2017. Its website footer states it’s made in Lahore, Pakistan. It’s part of the same product family as WhoisFreaks and APIFreaks.

Disclosure: This entry was submitted by a member of the IPGeolocation.io team.

### Ethical Considerations

* IP location is approximate. Never treat it as a person's exact location or use it alone to identify someone
* VPNs, proxies, shared and mobile IPs mean one IP can represent many people; so corroborate with other evidence
* IP addresses can be personal data under laws such as GDPR so handle and store results accordingly
* Lookups are sent to a third-party provider. Consider operational security for sensitive cases.

### Related Tools:

* [IPinfo](ipinfo.md)
* MaxMind GeoIP / GeoLite2
* [DNS Dumpster](dns-dumpster.md)

#### Sources

[https://ipgeolocation.io/](https://ipgeolocation.io/)&#x20;

[https://ipgeolocation.io/tools](https://ipgeolocation.io/tools)&#x20;

[https://ipgeolocation.io/pricing.html](https://ipgeolocation.io/pricing.html)&#x20;

[https://ipgeolocation.io/documentation/ip-location-api.html](https://ipgeolocation.io/documentation/ip-location-api.html)&#x20;

[https://ipgeolocation.io/privacy.html](https://ipgeolocation.io/privacy.html)&#x20;

[https://ipgeolocation.io/gdpr.html](https://ipgeolocation.io/gdpr.html)&#x20;

[https://ipgeolocation.io/subprocessors.html](https://ipgeolocation.io/subprocessors.html)&#x20;

[https://x.com/ipgeolocationio](https://x.com/ipgeolocationio)&#x20;

[https://www.linkedin.com/company/ipgeolocation-io](https://www.linkedin.com/company/ipgeolocation-io)&#x20;



_With thanks to Furqan Ashraf for submitting this tool to the OSINT Tool Library._
