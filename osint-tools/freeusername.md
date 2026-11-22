---
description: >-
  Tool Description : Search a username across 3,450+ sites in the browser, with
  blocked and unknown checks reported separately from confirmed hits
---

# FreeUsername

| **FreeUsername** | **Quick Overview** |
| ---------------- | ------------------ |
| URL | [https://freeusername.com/](https://freeusername.com/) |
| What it does | Checks whether a username exists across 3,457 sites and returns direct links to each profile found, with a separate status for sites that blocked or failed the check. |
| How to use it | Enter a username and choose a Quick scan (around 1,000 sites) or a Full scan (all 3,457). Results stream in as each site answers. Open each hit to verify it manually. |
| Cost | Free. |
| Account required | No. |
| Cookies | Standard browser functionality cookies; no account or sign-in required. |
| Ownership | FreeUsername, independent tool. Not affiliated with the WhatsMyName project, Sherlock or Maigret. |
| Use in Reporting | Username enumeration, digital footprint mapping, identity correlation across niche platforms, and early-stage OSINT triage. |

### **What does FreeUsername do?**

FreeUsername checks a single handle against its full site list and reports where a public profile answered. It runs on its own engine, built on WhatsMyName, Sherlock and Maigret site data plus sites added by the project, and the list is weighted toward small communities: of 3,457 sites, 58 are major platforms, 1,004 are niche sites and 2,395 are forum and fediverse servers.

The distinguishing feature for investigative work is that every check resolves to one of four states rather than a binary. A site that rate-limited or challenged the request is reported as **blocked**, and one that gave an unreadable answer as **unknown**, instead of being folded into "not found". In the project's own published testing, 8.8% of checks came back blocked and 5.1% unknown or error, so roughly one check in seven carries no usable answer either way.

**The lowdown:** a fast, no-install first pass that reaches further into small forums than most browser tools, with honest reporting of what it could not check. As with any username tool, hits are leads and not identity confirmation.

### How to Use:

1. **Go to the** [**FreeUsername website.**](https://freeusername.com/)
2. **Enter the username into the search field.**
3. **Choose Quick (around 1,000 sites, roughly 45 seconds) or Full (3,457 sites, roughly 3 minutes).**
4. **Review results as they stream in. Filter by category - social, gaming, coding, blogs, music, art, business, shopping - or search only one category.**
5. **Check the blocked and unknown lists, not just the hits: those sites gave no answer and need checking by hand.**
6. **Open each found profile and verify it belongs to the subject before relying on it.**

### Cost:

* [ ] Paid
* [ ] Partially Free
* [x] Free

## Data Processing

### Account required:

* [ ] Yes
* [x] No

### Cookies:

Standard browser functionality cookies. No account is required and the project states the searched username is not stored or logged.

### Use in Reporting

FreeUsername suits username enumeration and digital footprint mapping, particularly where the subject's activity is likely to sit on small forums, fediverse servers or regional communities rather than major platforms. Analysts typically use hits to pivot into profile analysis, social graph mapping or image analysis.

The project publishes its measurement data under CC BY 4.0, including a nightly site-health tracker, a 60-handle collision study across 3,166 sites and a benchmark of Sherlock, Maigret and Blackbird on the same handles, which makes its coverage claims checkable rather than asserted.

| **Capabilities** | **Limitations** |
| ---------------- | --------------- |
| Checks 3,457 sites with no install, sign-up or terminal. | Matching usernames do not confirm the same person; false positives occur on common handles. |
| Four result states separate blocked and unknown from not found. | No API, no CLI and no proxy or Tor support. |
| Results export to JSON or CSV. | Hosted only; queries run through the project's infrastructure, not the analyst's. |
| Site list weighted toward forums and fediverse servers. | Cannot be self-hosted or run offline. |
| Published methodology and open CSV data. | Some platforms, including Instagram and Spotify, return no clear answer and must be checked by hand. |
| Android app available. | Requires manual verification of every hit. |

### Summary

FreeUsername is a browser-based username search with unusually wide coverage of small and legacy sites, and it is candid about the checks it cannot complete. It is most useful at the triage stage of an investigation, and on machines where installing a CLI tool is not practical. Results need manual validation, as a username alone does not establish identity.

### Ownership

FreeUsername is an independent project, editorially maintained by David James. It states it is not affiliated with or endorsed by the WhatsMyName project, Sherlock, Maigret or any site it checks. It publishes an editorial policy and a corrections process.

### Ethical Considerations:

* Use only for legitimate investigative, research or self-audit purposes.
* The tool's own guidance asks users not to use it for employment or tenant screening.
* Avoid harassment, stalking or misuse of discovered accounts.
* Respect privacy and data protection regulations.
* Treat a hit as a lead, not proof, and verify before drawing conclusions about an individual.

### Related Tools:

* WhatsMyName
* Sherlock
* Maigret

#### Sources:

[https://freeusername.com/](https://freeusername.com/)

[https://freeusername.com/research/](https://freeusername.com/research/)

[https://freeusername.com/blog/username-data-study-2026/](https://freeusername.com/blog/username-data-study-2026/)
