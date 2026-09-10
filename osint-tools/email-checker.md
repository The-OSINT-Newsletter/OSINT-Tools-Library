---
description: >-
  Tool Description: A free online email-verification tool that checks whether an
  email address appears valid and whether the associated mailbox exists.
---

# Email Checker

| **Email Checker** | **Quick Overview**                                                                                                                |
| ----------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| URL               | [https://email-checker.net/](https://email-checker.net/)                                                                          |
| What it does      | Checks email format, domain validity, disposable-email status and attempts to determine whether the mailbox exists.               |
| How to use it     | Enter an email address and select the check option. Review and record the result.                                                 |
| Cost              | Free for basic checking. Premium/API options are available for bulk verification.                                                 |
| Account required  | No for basic checking.                                                                                                            |
| Cookies           | A mixture of Google Analytics cookies, Google reCAPTCHA, Google's advertising/consent cookies, and an application session cookie. |
| Ownership         | Not publicly disclosed.                                                                                                           |
| Use in Reporting  | Useful for quickly validating candidate email addresses before carrying out further OSINT research.                               |

### What does Email Checker do?

Email Checker is a simple online service designed to determine whether an email address is likely to be valid. It checks the email format, validates the domain, checks for disposable email addresses, retrieves MX records and then attempts to connect to the mail server using SMTP to determine whether the mailbox exists.&#x20;

**Note:** The service can return an unknown result where email providers restrict or block verification attempts, meaning that an inconclusive result does not necessarily indicate that an address is invalid.

**The lowdown:** It’s a quick way of ascertaining whether an email address exists.

### How to Use:

**1. Simply enter the email address being assessed and run the check.**

<img src="../.gitbook/assets/unknown (562).png" alt="" height="441" width="602">

\
**2. View returned result.**&#x20;

The platform will assess the address format, domain and disposable-email status before attempting mailbox verification through the domain's mail infrastructure.

<img src="../.gitbook/assets/unknown (563).png" alt="" height="189" width="602">

**3. Record the result, date/time and email address checked. Treat the outcome as an initial indicator and corroborate important findings using independent OSINT sources.**

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

Free for basic checking. Premium/API options are available for bulk verification.

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

No for basic checking.

### Cookies:&#x20;

Email Checker uses several categories of cookies. Google Analytics cookies (\_ga\_\* and \_gid) are used to measure website usage and distinguish visitors/sessions. Google reCAPTCHA uses \_GRECAPTCHA for human/anti-bot verification. FCCDCF and FCNEC are associated with Google's advertising and consent-management framework. The site also uses a rack.session cookie to maintain application session state and security information, including a CSRF token.&#x20;

**Note:** Be aware of third-party popups/external links.&#x20;

### Use in Reporting

Email Checker can be useful for:

* Validating candidate email addresses identified during an OSINT investigation.
* Establishing whether an address appears technically valid before pursuing further research.
* Supporting the triage of multiple candidate email addresses and identifying addresses worth investigating further.
* Providing a technical indicator that can be considered alongside other evidence when assessing an email address.
* Recording validation results as part of an investigative audit trail, including the address checked, result, date/time and source.
* Supporting further investigation by providing a starting point for pivots into other sources, rather than being treated as proof of identity or ownership.

| **Capabilities**                                                   | **Limitations**                                                                                    |
| ------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------- |
| Checks email syntax and domain validity.                           | A valid result does not prove who owns or controls the email address.                              |
| Checks whether an address appears to be disposable.                | Some mail servers restrict verification attempts, producing inaccurate or unknown results.         |
| Checks MX records and attempts mailbox verification through SMTP.  | Results are technical indicators, not evidence of a person's identity.                             |
| Provides a quick way to triage candidate email addresses.          | Mailbox status can change, so results represent the position at the time of checking.              |
| Basic checking is available without an account.                    | Submitting addresses to a third-party service creates data-processing and privacy considerations.  |

### Summary

Email Checker is best positioned in the discovery, triage and validation stages of the OSINT workflow and is particularly useful after an email address has been identified in a document, website, social-media profile, corporate record or other source.&#x20;

However it should not be used as a standalone identity-verification tool as a positive result only indicates that the address appears to exist rather than establish who operates the account/whether the address belongs to the person under investigation.

### Ownership

Not publicly disclosed.

### Ethical Considerations

* Only validate email addresses where there is a legitimate investigative or research purpose.
* Do not treat mailbox existence as evidence that a particular person owns or operates the account.
* Avoid submitting sensitive, confidential or unnecessary email datasets to third-party services.
* Consider applicable data-protection requirements when processing personal email addresses.
* Be aware that verification attempts involve communication with third-party mail infrastructure.
* Record the date and context of checks because mailbox status and verification results can change over time.

### Related Tools:

* EmailRep
* Hunter
* [Have I Been Pwned?](have-i-been-pwned.md)
* [BeenVerified](beenverified.md)

#### Sources

[https://email-checker.net/ ](https://email-checker.net/)
