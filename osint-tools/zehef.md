---
description: >-
  Tool Description : An email-focused OSINT tool that automates account
  discovery, breach checks, and paste site lookups
---

# Zehef

| **Zehef**        | **Quick Overview**                                                                                                                                    |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://github.com/N0rz3/Zehef](https://github.com/N0rz3/Zehef)                                                                                      |
| What it does     | Takes a single email address and runs it through multiple OSINT modules to uncover where it appears online.                                           |
| How to use it    | Run the tool from the command line with a target email address.                                                                                       |
| Cost             | Free.                                                                                                                                                 |
| Account required | No.                                                                                                                                                   |
| Cookies          | None (runs locally).                                                                                                                                  |
| Ownership        | Developed and maintained by GitHub user N0rz3, based in France.                                                                                       |
| Use in Reporting | Strong for initial email reconnaissance, mapping exposure across platforms and breaches, and supporting risk assessments (e.g. compromised accounts). |

### What does Zehef do?

Zehef bundles multiple email investigation techniques into one tool and runs them all in one go, helping investigators quickly map an email’s digital footprint without missing key steps.

It combines:

* Account discovery (via Holehe-style checks)
* Breach exposure checks (using pwned password data)
* Paste site lookups (e.g. Pastebin mentions)

**The lowdown:** Simply put, it tells you where an email has been used, exposed, or leaked.

### How to Use:

**1. Open your Terminal and clone the Zehef repository from GitHub:** git clone https://github.com/N0rz3/Zehef.git

**2. Install required Python dependencies.**

**3. Run the tool:** python zehef.py **and enter a target email address.**

**4. Review results across modules (accounts, breaches, pastes).**

You can [view our full guide to Zehef on The OSINT Newsletter here.](https://osintnewsletter.com/p/zehef)     &#x20;

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

### Cookies:&#x20;

None (runs locally).

### Use in Reporting

Zehef is useful for:

* Identifying exposed accounts linked to an email.
* Highlighting breach exposure risk.
* Supporting attribution leads.
* Demonstrating digital footprint breadth.

[A private investigator on Reddit](https://www.reddit.com/r/OSINT/comments/1dd06rx/critique_my_set_up_long_post/) has reportedly used Zehef (amongst other tools) for background checks, fraud investigations, and subject profiling.

| **Capabilities**                       | **Limitations**                                          |
| -------------------------------------- | -------------------------------------------------------- |
| Multi-module email investigation.      | False positives possible, especially with common emails. |
| Account enumeration across platforms.  | Dependent on external data sources/modules.              |
| Breach and exposure detection.         | Limited depth—requires manual follow up.                 |
| Paste site intelligence gathering.     | Command-line setup may be a barrier for beginners.       |

### Summary

Zehef is ideal for quickly assessing an email’s exposure and footprint but still relies on analyst judgment to verify and build the full picture.

### Ownership

Developed and maintained by GitHub user [N0rz3](https://github.com/N0rz3), based in France.

### Ethical Considerations

* Use only for lawful, legitimate investigations.
* Avoid targeting individuals without justification.
* Treat breach data sensitively.
* Do not assume identity based solely on email matches.

### Related Tools:

* Holehe (email account discovery)
* Have I Been Pwned (breach lookup)
* Maigret (username enumeration)

#### Sources

[https://github.com/N0rz3/Zehef](https://github.com/N0rz3/Zehef)&#x20;

[https://osintnewsletter.com/p/zehef](https://osintnewsletter.com/p/zehef)&#x20;

[https://espysys.com/blog/zehef-the-osint-tool-for-email-tracking-espy/](https://espysys.com/blog/zehef-the-osint-tool-for-email-tracking-espy/)&#x20;

[https://medium.com/@loyalonlytoday/find-information-about-your-target-email-osint-08735d81c8b0](https://medium.com/@loyalonlytoday/find-information-about-your-target-email-osint-08735d81c8b0) [https://www.reddit.com/r/OSINT/comments/1dd06rx/critique\_my\_set\_up\_long\_post/](https://www.reddit.com/r/OSINT/comments/1dd06rx/critique_my_set_up_long_post/)&#x20;

<br>

