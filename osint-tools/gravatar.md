---
description: >-
  Tool Description : An avatar service that allows you  to determine whether an
  email address is associated with a publicly available Gravatar profile.
---

# Gravatar

<table data-header-hidden><thead><tr><th width="256.33331298828125"></th><th></th></tr></thead><tbody><tr><td><strong>Gravatar</strong></td><td><strong>Quick Overview</strong></td></tr><tr><td>URL</td><td><a href="https://gravatar.com/site/check">https://gravatar.com/site/check</a> </td></tr><tr><td>What it does</td><td>Checks whether an email address is linked to a Gravatar profile and returns any publicly available profile information associated with that account. </td></tr><tr><td>How to use it</td><td>Enter an email address into the search barto determine whether a public profile exists and review any available profile details. </td></tr><tr><td>Cost</td><td>Free.</td></tr><tr><td>Account required</td><td>No.</td></tr><tr><td>Cookies</td><td>Standard functional and analytics cookies.</td></tr><tr><td>Ownership</td><td>Owned by San Francisco based Automattic Inc. </td></tr><tr><td>Use in Reporting</td><td>Useful for attributing email addresses, identifying profile images and usernames, and linking an email address to other online accounts.</td></tr></tbody></table>

### What does Gravatar do?

Gravatar is a profile management service that associates an email address with a publicly visible avatar and optional profile information. Many websites including WordPress, GitHub, Stack Overflow and discussion forums can automatically display a user's Gravatar image when the same email address is used.

Where available, you may discover profile photographs, display names, usernames, biographies, websites, social media links and other self-published information.

**The lowdown:** As Gravatar profiles are tied to email addresses rather than usernames, they can provide valuable attribution opportunities when investigating online identities.&#x20;

### How to Use:

**1. Enter your target email address into the search bar to determine whether a public profile exists.**

**2. Review any available profile image, display name, biography, linked websites or social profiles. Record relevant identifiers for further investigation.**&#x20;

<img src="../.gitbook/assets/unknown (321).png" alt="" height="261" width="602">

**3. Cross-reference discovered usernames, profile photographs and websites with social media platforms, search engines and other OSINT resources to verify identity and identify additional online accounts.**

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

### Cookies:&#x20;

The site uses standard functional and analytics cookies to support website performance, visitor analytics and user preferences. Examples include tk\_ai (anonymous analytics identifier) and tk\_qs (short-term referral and analytics tracking). Users accessing the service through Google may also encounter Google security (SIDCC, SSID) and consent (SOCS) cookies.

### Use in Reporting

Gravatar can support reporting by:

* Verifying whether an email address has a public online identity.
* Identifying profile photographs associated with an email address.
* Discovering usernames and aliases.
* Identifying linked websites and public profiles.
* Supporting attribution of online accounts.
* Providing corroborating evidence during identity investigations.

As a real world example, investigative journalists exploited Gravatar's MD5 email hashes to identify anonymous users, including politicians posting under pseudonyms. You can view the article [here.](https://arstechnica.com/information-technology/2013/12/crypto-weakness-in-web-comment-system-exposes-hate-mongering-politicians/)

| **Capabilities**                                                      | **Limitations**                                                             |
| --------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| Determines whether an email address has a public Gravatar profile.    | Only returns information that users have chosen to make publicly available. |
| Reveals publicly available profile images linked to an email address. | Many email addresses will have no associated Gravatar profile.              |
| Identifies usernames, display names and biographies where available.  | Doesn’t verify ownership of an email address or online identity.            |
| May expose linked personal websites and social media profiles.        | Profile information may be outdated or no longer maintained.                |
| Free to use with no account required for basic profile checks.        | Limited to accounts registered with the Gravatar service.                   |

### Summary

Gravatar is most effective as an enrichment tool rather than a discovery tool. Its findings should be combined with search engines, social media investigations, username searches and other identity-focused OSINT techniques to build a more complete profile.

### Ownership

Owned by Automattic Inc., the company behind WordPress.com, Tumblr and other online publishing platforms. It’s co-founded and headed up by [Matt Mullenweg](https://www.linkedin.com/in/mattm/) and headquartered in San Francisco.

### Ethical Considerations

* Only investigate information that has been made publicly available by the account owner.
* A Gravatar profile alone does not confirm ownership of an email address or associated accounts.
* Avoid making attribution decisions based solely on profile photographs or usernames.
* Verify identity through multiple independent OSINT sources before reporting findings.
* Respect privacy and applicable data protection legislation when handling personal information.

### Related Tools:

* [Have I Been Pwned?](have-i-been-pwned.md)
* [Epieos](epieos.md)
* Holehe
* [WhatsMyName](whatsmyname.md)
* Sherlock

#### Sources

[https://gravatar.com/site/check](https://gravatar.com/site/check)&#x20;

[https://automattic.com/about/](https://automattic.com/about/)&#x20;

[https://en.wikipedia.org/wiki/Matt\_Mullenweg](https://en.wikipedia.org/wiki/Matt_Mullenweg)&#x20;

[https://www.linkedin.com/in/mattm/](https://www.linkedin.com/in/mattm/)&#x20;

[https://arstechnica.com/information-technology/2013/12/crypto-weakness-in-web-comment-system-exposes-hate-mongering-politicians/](https://arstechnica.com/information-technology/2013/12/crypto-weakness-in-web-comment-system-exposes-hate-mongering-politicians/)
