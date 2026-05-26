---
description: >-
  Tool Description : An interactive browser fingerprinting dashboard that
  generates and displays a range of unique identifiers based on the behaviour of
  your own browser
---

# Finger Printer

| **Finger Printer** | **Quick Overview**                                                                                                          |
| ------------------ | --------------------------------------------------------------------------------------------------------------------------- |
| URL                | [https://gonzosint.github.io/fingerprinter/](https://gonzosint.github.io/fingerprinter/)                                    |
| What it does       | Provides a detailed breakdown of your device’s digital footprint by analysing how your browser behaves and what it reveals  |
| How to use it      | Open Finger Printer on your browser, allow the scan to run automatically, and view results.                                 |
| Cost               | Free.                                                                                                                       |
| Account required   | No.                                                                                                                         |
| Cookies            | Minimal or no cookies used.                                                                                                 |
| Ownership          | Hosted as a public GitHub Pages project (GONZOsint), with no clearly stated commercial owner or organisation.               |
| Use in Reporting   | N/A - used to understand your own browser’s identifiability and tracking exposure.                                          |

### What does Finger Printer do?

When you browse online your device leaves a unique fingerprint that can be obfuscated using several methods if you choose; however, some data points are very difficult to spoof. Finger Printer allows you to see what information you expose to the internet.&#x20;

**The lowdown:**  It’s best used for understanding digital tracking risk and browser identity exposure rather than external website analysis or traditional OSINT reconnaissance.&#x20;

### How to Use:

**1. Open the Finger Printer dashboard in your browser and allow the page to run its fingerprinting checks automatically.**

<img src="../.gitbook/assets/unknown (126).png" alt="" height="303" width="602">

**2. Analyse the different identifiers produced which show how your browsing environment appears compared to others.**

<img src="../.gitbook/assets/unknown (127).png" alt="" height="301" width="602">

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

### Cookies:&#x20;

Minimal or no cookies used (none used during our session on 18.05.26). Finger Printer is generated via browser APIs rather than persistent tracking storage.

### Use in Reporting

Finger Printer is useful for:

* Explaining browser fingerprinting in OSINT or privacy reports.
* Demonstrating non-cookie tracking methods.
* Supporting research into anonymity and anti-tracking techniques.
* Highlighting risks in investigative or operational security contexts.
* Educating audiences on digital identity exposure online.

| **Capabilities**                                                                 | **Limitations**                                                     |
| -------------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| Generates multiple browser-based fingerprint identifiers in real time.           | Does not provide external OSINT or website reconnaissance data.     |
| Combines signals like Canvas, WebGL, and system attributes into unique profiles. | Results can vary between sessions or browser configurations.        |
| Visualises how trackable a browser/device is online.                             | Not suitable for forensic-grade attribution or investigations.      |
| Highlights differences between fingerprinting methods.                           | Limited ability to correlate fingerprints to real-world identities. |
| Runs fully in-browser with no installation/login required.                       | Depends heavily on browser support for fingerprinting APIs.         |

### Summary

Finger Printer is mainly used to understand your own browser’s identifiability and tracking exposure, best used before investigations to assess how uniquely identifiable your browser is, helping you adjust settings.

### Ownership

Hosted as a public GitHub Pages project [(GONZOsint)](https://github.com/GONZOsint), with no clearly stated commercial owner or organisation.&#x20;

### Ethical Considerations

* Results should not be used to de-anonymise individuals
* Avoid using fingerprinting data for targeting or profiling people.
* Always consider consent and lawful basis when discussing tracking techniques.

### Related Tools:

* AmIUnique
* [Cover Your Tracks](cover-your-tracks.md)
* TorBrowser

#### Sources

[https://gonzosint.github.io/fingerprinter/](https://gonzosint.github.io/fingerprinter/)&#x20;

[https://github.com/GONZOsint](https://github.com/GONZOsint)

[https://x.com/GONZOS\_int](https://x.com/GONZOS_int)&#x20;
