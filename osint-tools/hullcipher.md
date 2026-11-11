---
description: >-
  Tool Description: A maritime OSINT platform that detects when sanctioned
  vessels change their name, MMSI, or flag, or broadcast an identity that does
  not match listed records.
---

# HullCipher

| **HullCipher**   | **Quick Overview**                                                                                                                                                         |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://hullcipher.com/](https://hullcipher.com/)                                                                                                                         |
| What it does     | Tracks ships on 8 authorities' sanctions lists using terrestrial AIS and records where a ship's broadcast differs from the lists, when it goes silent, and where it stops. |
| How to use it    | Search a ship by name, IMO or MMSI, or select one on the map, and read its page and timeline.                                                                              |
| Cost             | Free to browse (7 days of history). Paid accounts available for fuller functionality.                                                                                      |
| Account required | No for browsing and browser alerts. Yes for 14 days of history instead of 7, email alerts and saved fleets.                                                                |
| Cookies          | Mainly Clerk authentication/session cookies plus Cloudflare security cookies associated with HullCipher.                                                                   |
| Ownership        | HullCipher LLC, Pennsylvania, USA.                                                                                                                                         |
| Use in Reporting | Useful for documenting vessel movements, identity changes, AIS gaps/dark events, prohibited port calls and potential sanctions-evasion indicators.                         |

### What does HullCipher do?

HullCipher draws every ship on the UN, US (OFAC), UK, EU, Canadian, Australian, New Zealand and Swiss sanctions lists on one map, using positions from the AISHub terrestrial AIS network.

The lists against the broadcast: For each ship it shows the name, IMO and MMSI each list publishes, the date each authority designated it and, where HullCipher saw it happen, removed it, beside the name and MMSI the ship is broadcasting now. It records name, MMSI and flag changes, dated from the ship's own broadcast, and flags an MMSI that no list publishes or a second transponder broadcasting the same IMO. A ship newly added to a list arrives with its earlier track filled in, back to 1 August 2026.

**What the ship did:** It records periods when a listed ship stops transmitting, with how long the silence lasted and how many other ships nearby were still being received at the time; an hourly AIS coverage layer shows where the network receives signals, so a silence can be judged against reception. It records calls at ports that sanctions programs restrict, dated from the ship's arrival, and two ships stopped alongside each other away from any known port, with a control that moves the map to both ships at that moment. Positions that imply an impossible speed are drawn and marked with how far past possible each leg was, not removed. Tracks can be replayed for one ship, or for all listed ships at a chosen time, and every view has a shareable link.

**Ownership:** The owner, manager, related companies and people that the authorities publish, shown as a network and never inferred. A listed company or person can be searched by name.

**Other ships:** Any ship can be searched by name, IMO or MMSI; for a ship on no list, the last 7 days of positions are shown, with no findings.

**Keeping watch:** A watched ship sends a browser or email alert for a new silence and its end, a port call, a meeting at sea, a name or MMSI change, another transponder claiming its IMO, or a new listing or removal. A list of IMOs can be pasted in to save a fleet, which narrows the map, counts and ship list to those ships. Pro and Teams can export any table, and a track fix by fix, as CSV.



**The lowdown:** It puts the lists and the broadcast on the same page, with dates, so a discrepancy can be checked against the authority's own record.

### How to Use:

**1. Search a ship by name, IMO or MMSI (for example IMO 9310525), or click a ship on the map.**

<img src="../.gitbook/assets/unknown (692).png" alt="" height="277" width="602">

**2. Examine the vessel's available AIS information, including its current position and historical movement/activity information. Pay particular attention to changes in vessel name, MMSI and flag-related identifiers.**&#x20;

<img src="../.gitbook/assets/unknown (691).png" alt="" height="293" width="602">

**Note:** The top of the page lists each authority's name for the ship beside the name and MMSI it is broadcasting. The timeline lists designations, name and MMSI changes, silences, port calls and meetings at sea. A row with a place has a button that shows it on the map; the play control replays the track.

**You can turn on "AIS coverage" to see whether other ships were being received where the ship went silent:**

<img src="../.gitbook/assets/unknown (693).png" alt="" height="255" width="602">

**3. Check the available dark-event history and prohibited-port-call records, then compare those findings against independent sources such as official sanctions lists, port records, satellite imagery and other AIS providers.**

<img src="../.gitbook/assets/unknown (694).png" alt="" height="484" width="602">

**4. Use the bell to receive a browser or email alert when a new event is recorded for that ship. A list of IMOs can be pasted in to save a fleet.**

<img src="../.gitbook/assets/unknown (695).png" alt="" height="264" width="602">

### Cost

* [ ] Free
* [x] Partially Free
* [ ] Paid

Free to browse with no account (7 days of history).&#x20;

Free account, signed up with email or Google: 14 days and email alerts.&#x20;

Pro: full history and CSV export ($50/month, waitlist).&#x20;

Teams: from $250/month, by contact.&#x20;

Full comparison: [https://hullcipher.com/pricing](https://hullcipher.com/pricing)

## Data Processing

### Account Required:

* [x] Yes
* [x] No

No for browsing and browser alerts. Yes for 14 days of history instead of 7, email alerts and saved fleets.

### Cookies:&#x20;

The site uses Clerk for authentication and Cloudflare for security. Captured cookies include Clerk authentication/session cookies (\_\_client, \_\_client\_uat and a Clerk instance-specific \_\_client\_uat\_\* cookie), together with Cloudflare security cookies (\_\_cf\_bm and \_cfuvid). The \_\_client cookie contains a signed JWT and should be treated as sensitive authentication/session material. These cookies are primarily security/authentication rather than advertising cookies.&#x20;

### Use in Reporting

HullCipher can be useful for:

* Checking whether a sanctioned ship still broadcasts the name and MMSI the lists publish, and when that changed.
* Dating when a listed ship stopped transmitting, and checking whether other ships nearby were still received.
* Verifying port calls at restricted ports and ships stopped alongside each other at sea.
* Comparing how different authorities list the same ship, including different names.
* Following a ship over time through alerts.
* Generating leads for further investigation using satellite imagery, official registries, and independent AIS sources.&#x20;

You can find case studies at [https://hullcipher.com/findings](https://hullcipher.com/findings) , each with its map fixed at the time of writing, and feed uptime at [https://hullcipher.com/stats](https://hullcipher.com/stats).&#x20;

| **Capabilities**                                                                                            | **Limitations**                                                                                                     |
| ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| Ships on 8 authorities’ sanctions lists on one map, with each list’s name, IMO, MMSI, and designation date. | Terrestrial AIS only, no satellite AIS: ships far offshore drop out of range.                                       |
| Name, MMSI and flag changes as heard on air; MMSIs no list publishes; two transponders with one IMO.        | History begins 1 August 2026; 7 days without an account, 14 with a free signed-up account, full history on Pro.     |
| Silences, with the number of nearby ships still received; an hourly AIS coverage layer.                     | A removal from a list is dated only if it happened after HullCipher began reading that list.                        |
| Port calls at restricted ports; two ships stopped alongside each other away from port.                      | AIS is self-reported and can be spoofed or switched off.                                                            |
| Positions implying impossible speeds are shown and marked, not removed.                                     | Silences, identity changes and meetings are computed from AIS; they are leads to check, not evidence of wrongdoing. |
| Track replay for one ship or all listed ships at a chosen time; shareable links.                            | Ownership is limited to what the authorities publish; no registry or corporate data.                                |
| Browser and email alerts; saved fleets from a list of IMOs; CSV export (Pro).                               | Ships not on any list: the last 7 days of positions only, on every plan, and no findings.                           |

### Summary

HullCipher is a useful maritime OSINT tool that can provide live AIS positions, historical dark-event information and prohibited-port-call records, while public examples demonstrate its use for investigating changes in vessel names and MMSIs associated with sanctioned vessels.

It’s most useful for lead generation (a listed ship that went silent or renamed), verification (its current identity and recent movements before you cite them), and monitoring a set of ships through an investigation.

### Ownership

HullCipher LLC, a company registered in Pennsylvania, USA.

### Ethical Considerations

* AIS information should not automatically be treated as proof of what physically happened.
* A “dark event” can have multiple explanations and requires contextual investigation.
* Verify sanctions claims against primary sources. HullCipher can provide useful leads, but the relevant government sanctions list should be checked directly.
* Use IMO numbers where possible. Vessel names and MMSIs can change, making IMO numbers useful for maintaining identity continuity.
* A prohibited port call or unusual identity change is an investigative lead, not automatically evidence of sanctions evasion or criminal conduct. Remember, a ship's crew is usually not the sanctioned party.
* Avoid unnecessarily exposing sensitive operational information where doing so could create safety risks.

### Related Tools:

* [OpenSanctions](open-sanctions.md)
* [MarineTraffic](marinetraffic.md)
* VesselFinder
* [Global Fishing Watch](global-fishing-watch.md)
* Equasis

#### Sources

[https://hullcipher.com/](https://hullcipher.com/)&#x20;

[https://hullcipher.com/data-sources](https://hullcipher.com/data-sources)

[https://hullcipher.com/pricing](https://hullcipher.com/pricing)

[https://hullcipher.com/terms](https://hullcipher.com/terms)

[https://hullcipher.com/vessel/9310525](https://hullcipher.com/vessel/9310525)



_With thanks to Josh Plumley for submitting this tool to the OSINT Tool Library._<br>
