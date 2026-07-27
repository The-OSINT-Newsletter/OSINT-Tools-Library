---
description: >-
  Tool Description : A web-based tool that captures and preserves online content
  as verifiable digital evidence.
---

# GetProofAnchor

| **GetProofAnchor** | **Quick Overview**                                                                                                                                                                                        |
| ------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL                | [https://getproofanchor.com/](https://getproofanchor.com/)                                                                                                                                                |
| What it does       | Creates a proof package containing captured content, metadata, cryptographic hashes, and trusted timestamps, allowing the integrity of the captured material to be independently verified.                |
| How to use it      | Submit a URL and create a capture. The platform processes the online content and generates a verifiable proof package which can be exported and independently checked using the public verification tool. |
| Cost               | Paid.                                                                                                                                                                                                     |
| Account required   | Yes for creating and managing captures. No for public proof verification.                                                                                                                                 |
| Cookies            | Minimal/Google Analytics cookies.                                                                                                                                                                         |
| Ownership          | Operated by forehead s.r.o., Czech Republic.                                                                                                                                                              |
| Use in Reporting   | Proof IDs, verification results, and exported proof packages can be referenced in OSINT reports, investigations, legal documentation, or research.                                                        |

### What does GetProofAnchor do?

GetProofAnchor is designed to preserve online content in a way that makes later integrity verification possible. This is particularly useful in OSINT investigations where web pages, posts, or other online material may be edited, deleted, or become inaccessible.

When a capture is created, GetProofAnchor records the relevant content and associated metadata, calculates cryptographic hashes, and anchors the evidence with a trusted timestamp. The resulting proof can be exported as a proof package and independently verified.

Unlike a standard screenshot, the purpose of GetProofAnchor is not only to show what was visible at a particular moment, but to provide technical mechanisms for checking whether the preserved evidence has been altered after capture.

**The lowdown:** The tool supports those who need to preserve online material and later demonstrate its integrity.

### How to Use:

**1. Create a GetProofAnchor account and sign in, then from the ‘dashboard’, enter the URL of the webpage you want to preserve.**

<img src="../.gitbook/assets/unknown (366).png" alt="" height="363" width="602">

**2. Start the capture process, then review and manage the preserved evidence including timestamps, metadata, and cryptographic verification.**&#x20;

<img src="../.gitbook/assets/unknown (367).png" alt="" height="253" width="602">

**3. Download, share, or reference the proof within reports, investigations, or case files to demonstrate the authenticity of the captured content.**&#x20;

<img src="../.gitbook/assets/unknown (368).png" alt="" height="312" width="602">



### Cost

* [ ] Free
* [ ] Partially Free
* [x] Paid

Subscription plans are available, and Assisted Capture can be purchased separately for individual URLs.&#x20;

**Note:** You can sign up for a free 7-day trial on the professional plan.&#x20;

## Data Processing

### Account Required:

* [x] Yes
* [x] No

Yes, for creating and managing captures. Public proof verification does not require an account.

### Cookies:&#x20;

Minimal/the site may use essential cookies required for security, authentication, and core platform functionality. We only noted a couple of Google Analytics cookies during our session on 18 July 2026.

### Use in Reporting

GetProofAnchor can be used to preserve online sources referenced in OSINT reports, investigative findings, legal documentation, reputation investigations, and research. A Proof ID can be referenced alongside a finding so that the integrity of the preserved evidence can later be checked. The exported Evidence ZIP provides supporting files, metadata, hashes, and timestamp information that can be retained with the investigation case file.

**Potential reporting uses include:**

* Preserving social media posts before deletion or editing.
* Documenting public statements made by individuals or organisations.
* Preserving webpages used as sources in investigative reporting.
* Recording scam, impersonation, or fraudulent websites.
* Documenting counterfeit listings or intellectual property infringement.
* Preserving defamatory or threatening online content.
* Supporting chronology and timeline reconstruction.
* Retaining online evidence before submitting a platform report or takedown request.
* Providing independently verifiable integrity information alongside an OSINT report.

**Note:** The tool does not determine whether content is true, lawful, or admissible in a specific jurisdiction. Analysts remain responsible for interpretation, source evaluation, and appropriate reporting methodology.

<table data-header-hidden><thead><tr><th width="260.333251953125"></th><th></th></tr></thead><tbody><tr><td><strong>Capabilities</strong></td><td><strong>Limitations</strong></td></tr><tr><td>Creates cryptographically verifiable captures of webpages.</td><td>Does not discover or search for OSINT data. It only preserves content already identified.</td></tr><tr><td>Produces trusted timestamps for online content.</td><td>Cannot capture content that requires inaccessible authentication or permissions.</td></tr><tr><td>Preserves evidence even if the original webpage changes or is deleted later.</td><td>Dynamic/highly interactive webpages may not always render perfectly.</td></tr><tr><td>Captures supporting metadata alongside webpage content.</td><td>Long-term storage and advanced features require a paid subscription.</td></tr><tr><td>Enables sharing and exporting of verified evidence records. </td><td>Verification is limited to what was visible and accessible at the time of capture.</td></tr></tbody></table>

### Summary

GetProofAnchor is most useful during the collection and evidence preservation stage of the OSINT workflow.

Its main advantage over ordinary screenshots is that captured evidence is designed to be tamper-evident and independently verifiable. Cryptographic hashes, timestamping, Proof IDs, and portable Evidence ZIP packages make it easier to demonstrate that preserved files have not been modified after capture.

The tool is particularly useful when investigators expect online content to be edited, deleted, disputed, or removed following a report or takedown request.

### Ownership

GetProofAnchor is operated by forehead s.r.o., a Czech company based in Prague, Czech Republic. The platform is independently developed as a digital evidence preservation and verification service focused on tamper-evident online evidence.

### Ethical Considerations

* Consider privacy and potential harm before preserving or sharing personal information.
* Avoid unnecessarily including unrelated personal data in reports or exported evidence.
* Follow applicable data protection laws, including GDPR where relevant.
* Do not treat successful integrity verification as proof that the underlying claim is true.
* Clearly distinguish captured source material from analytical conclusions.
* Consider the safety of vulnerable individuals before publishing Proof IDs or evidence references.
* Avoid publicly exposing evidence packages containing sensitive personal information.
* Preserve content before interacting with a subject when interaction could cause evidence to be deleted or altered.
* Maintain appropriate investigator notes and document the wider collection context.

### Related Tools:

* Hunchly
* WebPreserver by PageFreezer
* Page Vault
* [Wayback Machine](wayback-machine.md)
* [Forensic OSINT](forensic-osint.md)

#### Sources

[https://getproofanchor.com/](https://getproofanchor.com/)&#x20;

[https://getproofanchor.com/assisted-capture](https://getproofanchor.com/assisted-capture)

[https://getproofanchor.com/pricing](https://getproofanchor.com/pricing)

[https://getproofanchor.com/solutions](https://getproofanchor.com/solutions)



_With thanks to Robert Bernášek for submitting this tool to the OSINT Tool Library._
