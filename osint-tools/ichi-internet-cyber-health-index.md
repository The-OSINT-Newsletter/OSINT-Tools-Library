---
description: >-
  A free, publicly accessible daily cybersecurity index that aggregates threat
  intelligence from multiple vetted sources and synthesises them into a
  single health score for the internet's current threat landscape.
---

# ICHI — Internet Cyber Health Index

| **ICHI** | **Quick Overview** |
| -------- | ----------------------------------------- |
| URL | [https://ichi.global/](https://ichi.global/) |
| What it does | Aggregates cybersecurity signals from dozens of open-source feeds—CVEs, CISA KEV entries, DDoS data, malware research, vendor advisories—into a daily scored index (0–100) of the internet's overall threat pressure. |
| How to use it | Navigate to ichi.global to see today's health score, browse the priority vulnerability and incident feed, and examine the source evidence behind each entry. No account is required. |
| Cost | Free. |
| Account required | No. |
| Cookies | Analytics and functional cookies typical of a Netlify-hosted static web application. |
| Ownership | Built and maintained by Joe Bernik (bernik@gmail.com). Not affiliated with any commercial security vendor. |
| Use in Reporting | Useful for establishing daily threat context, identifying priority vulnerabilities under active exploitation, tracking DDoS trends, and corroborating threat-intelligence findings with direct source links. |

### What does ICHI do?

ICHI — Internet Cyber Health Index is a free, daily internet cyber-health barometer. It aggregates signals from multiple open-source threat intelligence sources — CISA KEV, CERT advisories, vendor security research, DDoS telemetry, and curated security news — into a single scored index representing the current pressure on the global digital ecosystem.

The daily score runs from 0 (minimal pressure) to 100 (critical), with thresholds at Elevated (≥50), High (≥70), and Critical (≥85). As of 21 October 2026, ICHI was reading **73/100 (HIGH)**.

ICHI displays:

* **Priority vulnerabilities** — including Pre-KEV and CISA KEV entries with severity classifications, source attribution, and direct evidence links.
* **Incident tracking** — major security incidents with source confirmation and timeline.
* **DDoS activity** — real-time and recent distributed denial-of-service events.
* **Priority intelligence** — curated threat actor activity, campaigns, and significant advisories.
* **Pressure history** — a 30-day rolling trend chart for pattern identification.
* **Evidence & sources** — every entry links back to its original public source.

ICHI does not publish raw IOCs (IP addresses, domains, or hashes), but instead provides a curated, sourced narrative of the current threat environment.

### How to Use:

**1. Open ichi.global and read the daily score.**

The headline figure (e.g. 73/100 — HIGH) reflects the aggregated pressure from all monitored signals. Threshold bands (Elevated, High, Critical) provide immediate situational awareness.

**2. Review priority vulnerabilities and incidents.**

Scroll through the vulnerability feed to identify actively exploited CVEs, Pre-KEV entries, and KEV-confirmed issues. Each entry shows the affected product, CISA/vendor source, and the date of publication. Click **Record** to view the full source evidence.

**3. Check the 30-day pressure trend.**

The rolling history chart allows you to place the current score in context — identifying whether threat pressure is rising, stable, or declining week-on-week.

**4. Follow source links to primary evidence.**

Every vulnerability or incident entry includes a direct link to its original advisory (CISA, vendor PSIRT, research blog, etc.), allowing independent verification and corroboration.

**5. Use the RSS alerts feed for automated monitoring.**

ICHI publishes a free alerts RSS feed at `https://ichi.global/api/alerts` that can be ingested by any feed reader, SIEM, or CTI aggregation tool.

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

Fully free with no account required. Includes a free export/subscription option.

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

No account is required to access the full dashboard, score history, and source evidence links.

### Cookies:&#x20;

Analytics and functional cookies standard to Netlify-hosted web applications were observed during testing.

### Use in Reporting

ICHI can be used to:

* Establish the current day's overall internet threat pressure as contextual background.
* Identify which vulnerabilities are receiving Pre-KEV or CISA KEV designations at a given point in time.
* Corroborate threat intelligence findings with direct links to primary advisories.
* Track the 30-day trend in global digital ecosystem pressure.
* Monitor DDoS activity patterns over time.
* Identify emerging incidents before they appear in mainstream news.
* Ingest automated alerts through the RSS feed for SIEM or feed-reader integration.
* Provide threat context for organisational risk and security posture assessments.

| **Capabilities** | **Limitations** |
| ------------------------------------------------- | ------------------------------------------------------------------ |
| Daily scored index gives immediate situational awareness. | Score reflects aggregated open-source signals, not internal telemetry. |
| Every entry links to the original primary source. | Does not publish raw IOC data (IPs, domains, hashes). |
| Free and requires no account. | Directional outside-in signal; not a substitute for organisation-specific risk assessment. |
| RSS feed supports automated SIEM or CTI tool integration. | No public methodology for exact score weighting is published (methodology page available at ichi.global/methodology). |
| 30-day trend enables pattern identification. | Coverage depends on publicly available feeds and may lag zero-day disclosures. |
| Source-transparent: every data point is attributed. | Historical data beyond 30 days requires the export/subscription option. |

### Summary

ICHI is a free, source-transparent cybersecurity intelligence index designed to give practitioners and investigators a daily, scored view of global internet threat pressure. It aggregates data from CISA, vendor security advisories, DDoS monitoring services, and research publications into a single dashboard with direct links to the underlying primary sources.

Its primary value in an investigation context is establishing threat context — understanding which vulnerabilities are currently under active exploitation, whether overall threat pressure is elevated, and which incidents are being reported across trusted public sources on a given day. Because every entry is source-attributed, findings can be independently corroborated.

### Ownership

ICHI is an independent, noncommercial cybersecurity resource created and maintained by Joe Bernik. It is not affiliated with any security vendor, government agency, or commercial entity. Contact: bernik@gmail.com.

### Ethical Considerations

* Treat ICHI's daily score as a directional signal, not an authoritative measure of your organisation's specific risk.
* Verify individual vulnerability and incident entries against the linked primary sources before including them in formal reporting.
* Do not assume that a vulnerability appearing in ICHI's feed implies exploitation of a specific target.
* Preserve the ICHI record URL, score, and observation date when documenting findings.
* Distinguish between ICHI's aggregated signal and independently verified evidence from the original source.

### Related Tools:

* [Alien Vault OTX](alien-vault-otx.md)
* [IBM-X Force Exchange](ibm-x-force-exchange.md)
* [Pulsedive](pulsedive.md)

#### Sources

[https://ichi.global/](https://ichi.global/)

[https://ichi.global/methodology](https://ichi.global/methodology)
