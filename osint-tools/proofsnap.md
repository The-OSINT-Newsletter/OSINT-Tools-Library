---
description: >-
  Tool Description : A browser extension that captures a live web page from the
  rendering browser and seals it as a verifiable archive.
---

# ProofSnap

| **ProofSnap**    | **Quick Overview**                                                                                                    |
| ---------------- | --------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://getproofsnap.com/](https://getproofsnap.com/)                                                                |
| What it does     | Captures a web page as it is rendered in your own browser and packages it as a sealed evidence archive.               |
| How to use it    | Install the extension, open the page you want to preserve, open the side panel and start a capture.                   |
| Cost             | Paid.                                                                                                                 |
| Account required | Yes, to capture. No, to verify.                                                                                       |
| Cookies          | None through the extension. The getproofsnap.com website uses Google Analytics 4.                                     |
| Ownership        | Founded by Radim Motycka.                                                                                             |
| Use in Reporting | Useful for preserving online evidence and demonstrating provenance, integrity and the approximate/exact capture time. |

### What does ProofSnap do?

ProofSnap captures a live web page from the browser rendering it and packages it as a sealed, independently verifiable archive. An optional forensic mode reloads the page under the debugger with network observation, producing a WARC/1.0 archive, HAR, every sub-resource with its own SHA-256, the real TLS certificate chain and an MHTML copy, alongside a full-page image, HTML, extracted text, an image inventory, DNS and WHOIS results.

Everything is hashed into a manifest signed with a per-capture RSA key, timestamped by NTP and optionally by an OpenTimestamps Bitcoin anchor or an EU qualified RFC 3161 timestamp, with an ISO/IEC 27037 chain of custody record and a hash-chained forensic log. Packages verify offline, with no account and no involvement from the vendor.

**The lowdown:** It’s a digital evidence preservation tool that allows an investigator to preserve the state of a webpage at a particular point in time.

### How to Use:

**1. Install from the Chrome Web Store or Edge Add-ons and sign in. Open the page you want to preserve, including pages behind your own login. Open the side panel and pick a scope: visible area, full page, or a multi-tab session that snapshots every tab you visit.**

<img src="../.gitbook/assets/unknown (530).png" alt="" height="296" width="602">

**2. Enable forensic mode if you need the WARC and TLS chain (This is only available for subscriptions rather than one-off credits). It reloads the page under the debugger. Optionally add an OpenTimestamps anchor, an EU qualified timestamp, screen recording or AI-image analysis. Run the capture and download the ZIP.**

<img src="../.gitbook/assets/unknown (531).png" alt="" height="919" width="522">

<img src="../.gitbook/assets/unknown (532).png" alt="" height="424" width="602">

**3. Verify with the free web verifier, the open source CLI verifier, or the verify.sh / verify.ps1 script inside the package. None need an account.**

### Cost

* [ ] Free
* [ ] Partially Free
* [x] Paid

A 7 day free trial may be available with a payment card required. Subscriptions start from 8.99 USD per month (Essential, 100 captures) through Professional 16.99 and Enterprise 28.99, plus one-off credit packs. The forensic mode with WARC output is available from Professional upwards. Verification of a package is free and needs no account.

## Data Processing

### Account Required:

* [x] Yes
* [x] No

Yes, to capture. No, to verify. Anyone can check a package with the free web verifier, the open source command line verifier, or the scripts shipped inside the package itself.

### Cookies:&#x20;

The extension does not read or export the cookies of the page being captured into the archive. The getproofsnap.com website uses Google Analytics 4. The extension authenticates through Firebase and stores a session token locally.

### Use in Reporting

The output is built to survive being handed to someone who does not trust you: a third party can re-verify the hashes, manifest signature and timestamps offline, years later, using the MIT-licensed CLI verifier or the scripts inside the package.

**Typical uses:**&#x20;

* Preserving a post, listing, review or profile before it is edited or deleted
* Recording a browsing trail across tabs
* Fixing what a page looked like at a verified time
* Documenting image provenance signals at the moment of capture

**Note:** US packages include a Rule 902(13)/(14) declaration template with the technical facts pre-filled and the declarant block left blank.

| **Capabilities**                                                                                                                                                                           | **Limitations**                                                                                                                                                     |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Preserves webpages as forensic evidence, including screenshots and HTML.                                                                                                                   | Chromium only. No Firefox, no Safari.                                                                                                                               |
| Generates SHA-256 hashes and RSA-4096 digital signatures.                                                                                                                                  | Forensic mode with WARC needs the mid tier or above.                                                                                                                |
| Provides OpenTimestamps/Bitcoin blockchain anchoring.                                                                                                                                      | One page at a time. No bulk or scheduled crawling, so it does not replace an archiving crawler.                                                                     |
| Can capture metadata, TLS information, forensic logs and chain-of-custody information.                                                                                                     | AI-generation signals are heuristic and indicative, not determinative.                                                                                              |
| Works on authenticated and session-dependent content, with dedicated handling for virtualised scroll containers on WhatsApp Web, Telegram, Discord, Slack, Messenger, LinkedIn and Airbnb. | Captures only what the operator can already access. It does not bypass access controls.                                                                             |
| 29 languages, and a separate mode for certifying local files.                                                                                                                              | A cryptographic timestamp demonstrates integrity/existence of the captured package but does not by itself establish that the underlying webpage's claims are true.  |

### Summary

ProofSnap sits at the collection and preservation step of the OSINT workflow, right after you find something and before it changes. It does not search, enrich or pivot, so it complements discovery tools rather than replacing them.

### Ownership

Founded by[ Radim Motycka.](https://www.linkedin.com/in/radim-motycka-63b6a6108/) Qualified timestamps are issued by Disig a.s., a Qualified Trust Service Provider on the EU Trusted List.

### Ethical Considerations

* Anything preserved from a logged-in session was visible to you, but the subject may not expect it archived. Consider whether preservation is proportionate.
* Packages from authenticated sessions contain session state including cookies. Check metadata.json before sharing, to protect your own account and to avoid handing over access material.
* Preserved pages routinely contain personal data about people who are not the subject. Apply the usual minimisation.
* The AI-generation signals are indicators, not conclusions. Presenting them as a determination would overstate what the tool measures.
* Layout changes made to stabilise the page are listed in the chain of custody record. Disclose that record, not just the image.
* The tool documents when and how a page was captured. It does not establish that the contents are true.

### Related Tools:

* [Lookyloo](lookyloo.md)
* [Wayback Machine](wayback-machine.md)
* [Hunchly](hunchly.md)
* Page Vault
* ArchiveBox

#### Sources

[https://getproofsnap.com/](https://getproofsnap.com/)&#x20;

[https://getproofsnap.com/verify/index.html](https://getproofsnap.com/verify/index.html)&#x20;

[https://getproofsnap.com/author/radim-motycka.html](https://getproofsnap.com/author/radim-motycka.html)&#x20;

[https://www.linkedin.com/in/radim-motycka-63b6a6108/](https://www.linkedin.com/in/radim-motycka-63b6a6108/) <br>

_With thanks to Radim Motycka for submitting this tool to the OSINT Tool Library._ <br>
