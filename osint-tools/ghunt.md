---
description: >-
  Tool Description : A command line tool that obtains information about Google
  accounts.
---

# GHunt

| **GHunt**        | **Quick Overview**                                                                                                                                                                                |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://github.com/mxrch/GHunt/tree/master/ghunt](https://github.com/mxrch/GHunt/tree/master/ghunt)                                                                                              |
| What it does     | Gathers publicly accessible information about Google accounts using OSINT techniques.                                                                                                             |
| How to use it    | Enter a Google account email into GHunt and run the tool to retrieve publicly available information linked to that account, such as profile details, associated services, and possible locations. |
| Cost             | Free.                                                                                                                                                                                             |
| Account required | Yes - a Google Account.                                                                                                                                                                           |
| Cookies          | Google authentication cookies                                                                                                                                                                     |
| Ownership        | Developed and maintained by security researcher mxrch (likely based in France).                                                                                                                   |
| Use in Reporting | Can help verify the existence of a Google account, identify linked services, and support attribution when investigating online identities.                                                        |

### **What does GHunt do?**&#x20;

GHunt is designed to gather publicly accessible information about Google accounts. By querying Google services, it can reveal details connected to a specific account, usually using an email address as the starting point.

The tool works by using authenticated access to Google services and analysing the data that can be returned through them.

_Note: It does not hack or bypass security, but instead collects information that is exposed through Google’s systems and services._

Typical information GHunt may uncover includes:

* The account’s Google profile information
* Profile photos
* Possible YouTube channel associations
* Google Maps reviews or contributions
* Account creation details
* Some linked services or activity traces

**The lowdown:** It’s super useful for uncovering publicly available information linked to a Google account, but the results depend on what the user has made public and may be limited by Google’s privacy settings and data protections.

### How to Use:

#### <sup>1. Install GHunt by downloading the tool from the GitHub repository, then use Python and the required dependencies (pip).</sup> [<sup>See here.</sup>](https://pip.pypa.io/en/stable/installation/)

#### <sup>2.Log in to a Google account (advisably a test account that doesn’t link to your own account) and provide the required authentication cookies so GHunt can query Google services.</sup>

#### <sup>3. Run a search by using the command line to query a target Google account (typically using an email address) and review the information returned by the tool.</sup>

You can find[ our full guide here.](https://osintnewsletter.com/p/ghunt?hide_intro_popup=true)

**Note:** There is currently an email lookup error where GHunt authenticates successfully and loads the stored session correctly, but crashes during the email lookup phase with a `KeyError: 'container'`. (Correct at time of writing; 25 June 2026).&#x20;

### Cost:

* [ ] Paid
* [ ] Partially Free
* [x] Free



## Data Processing

### Account required:

* [x] Yes
* [ ] No

You'll need a Google account to use GHunt.

### Cookies:&#x20;

GHunt requires Google authentication cookies in order to access certain Google services and retrieve information linked to an account.

### &#x20;Use in Reporting

GHunt can support investigations by:

* Verifying whether a Google account exists
* Identifying public Google profile information
* Linking an email address to Google services (e.g., YouTube or Maps activity)
* Gathering supporting evidence for digital identity investigations

This makes GHunt useful in investigations involving online identities, fraud investigations, digital footprints, and attribution work.

For example, Bellingcat has used GHunt to investigate [Cartel leaders](https://www.bellingcat.com/news/2024/03/30/kinahan-cartel-wanted-narco-boss-exposes-whereabouts-by-posting-google-reviews/) (by identifying their travel partners and tracking their locations over time by analysing Google reviews and associated images). GHunt is also actively used by law enforcement.

| **Capabilities**                                      | **Limitations**                                               |
| ----------------------------------------------------- | ------------------------------------------------------------- |
| Identifies whether a Google account exists.           | Results heavily depend on user privacy settings.              |
| Retrieves Google profile information.                 | Some data previously available has been restricted by Google. |
| Locates profile pictures.                             | Requires technical setup and command line use.                |
| Detects linked YouTube channels.                      | Cannot access private/protected information.                  |
| Shows Google Maps contributions and reviews.          | <p><br></p>                                                   |
| Helps map a digital footprint across Google services. | <p><br></p>                                                   |

### &#x20;Summary

While GHunt is an incredibly powerful tool which helps build a clearer picture of a target’s digital footprint across Google services, its results ultimately depend on what information the account owner has made visible. As always, information gathered should also be verified and corroborated with additional sources before being included in reports.

### Ownership

GHunt is developed and maintained by security researcher [mxrch.](https://github.com/mxrch) Limited info available but according to their [X account](https://x.com/mxrchreborn), they appear to be based in France.&#x20;

### Ethical Considerations:

* Only use authentication cookies from your own Google account.
* Do not attempt to bypass Google security or access private data.
* Ensure findings are accurate and verified to prevent misidentification.
* When using GHunt findings in reports, sensitive details (such as personal photos, locations, or usernames) should be handled carefully, redacted if necessary, and shared only with appropriate audiences.



### Related Tools:

* Holehe
* Sherlock&#x20;
* SpiderFoot&#x20;
*   theHarvester



#### Sources:

[https://github.com/mxrch/GHunt/tree/master/ghunt](https://github.com/mxrch/GHunt/tree/master/ghunt)&#x20;

[https://bellingcat.gitbook.io/toolkit/more/all-tools/ghunt](https://bellingcat.gitbook.io/toolkit/more/all-tools/ghunt) &#x20;

[https://www.linkedin.com/pulse/kali-linux-footprinting-using-ghunt-orgito-leka-n0cvf/](https://www.linkedin.com/pulse/kali-linux-footprinting-using-ghunt-orgito-leka-n0cvf/)&#x20;

[https://www.securitydojo.net/blog/en/article/google-osint-with-ghunt/](https://www.securitydojo.net/blog/en/article/google-osint-with-ghunt/)&#x20;

[https://osintnewsletter.com/p/ghunt](https://osintnewsletter.com/p/ghunt)&#x20;

[https://www.bellingcat.com/news/2024/03/30/kinahan-cartel-wanted-narco-boss-exposes-whereabouts-by-posting-google-reviews/#:\~:text=Inputting%20several%20email%20addresses%20suspected,of%20the%20christopher%2Dvincent%20website](https://www.bellingcat.com/news/2024/03/30/kinahan-cartel-wanted-narco-boss-exposes-whereabouts-by-posting-google-reviews/).&#x20;

[https://github.com/mxrch](https://github.com/mxrch)&#x20;

[https://x.com/mxrchreborn](https://x.com/mxrchreborn)
