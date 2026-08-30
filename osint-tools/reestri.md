---
description: >-
  Tool Description : Looks up companies in the public business registers of
  Georgia (the country) and Armenia, including Armenian beneficial-owner
  declarations, Armenian public contracts and a person-to-companies search.
---

# Reestri

| **Reestri**       | **Quick Overview**                                                                                                                                                       |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| URL               | [https://apify.com/reestri](https://apify.com/reestri)                                                                                                                   |
| What it does      | Returns structured records from the official company registers of Georgia (NAPR) and Armenia (state register), with evidence links on every record.                     |
| How to use it     | Pick a tool, enter a company name, ID code or person name, run it in the browser or via API; results come back as JSON. Also available as MCP tools for AI assistants.   |
| Cost              | Paid.                                                                                                                                                                    |
| Account required  | Yes.                                                                                                                                                                     |
| Cookies           | Apify platform cookies.                                                                                                                                                  |
| Ownership         | Soso Pkhakadze, Kutaisi, Georgia (independent developer).                                                                                                                |
| Use in Reporting  | Useful for verifying counterparties, mapping a person's companies and checking Armenian beneficial owners and state contracts.                                           |

### What does Reestri do?

Reestri is a set of lookup tools over public company registers in the South Caucasus, published on the Apify platform. The Georgian tools search the NAPR business register (enreg.reestri.gov.ge) by company name or 9-digit ID code and, in reverse, by a person or organisation name to list every company they participate in. The Armenian tools search the state register (e-register.am) by name or tax ID and return status and registration data together with the company's official beneficial-ownership declarations, which the register publishes in BODS format, plus every public contract the company has won from the state procurement registry. A separate screen tool runs one name across Georgia, Armenia and Moldova in a single call.

**The lowdown:** It turns two portal-only registers in Georgian and Armenian script into searchable English JSON with the source URL, retrieval time and content hash on each record, so a finding can be cited and re-checked.

### How to Use:

**1. Open the tool page on Apify (for example the Georgia company lookup) and enter a company name or ID code in the input form, then press Start. The result table and JSON appear under the run.**

**2. For a person, use the Georgia person search: enter the name and each row is one company, role and status.**

**3. For Armenia, use the Armenia company lookup: the record includes the beneficial-owner declarations and, with the contracts tool, the public procurement history by tax ID.**

**4. The same tools can be added to an AI assistant as MCP tools through Apify's MCP endpoint.**

### Cost

* [ ] Free
* [ ] Partially Free
* [x] Paid

Pay per lookup and per record returned, billed through Apify (from $0.05 per search). Apify's free monthly credit covers a first set of lookups.

## Data Processing

### Account Required:

* [x] Yes
* [ ] No

A free Apify account is required to run the tools.

### Cookies:&#x20;

The tools run on the Apify platform, which sets its own session and analytics cookies. The registry data itself is fetched server-side.

### Use in Reporting

Reestri is useful for:

* Confirming that a Georgian or Armenian company exists, its legal form and whether it is active.
* Listing every Georgian company a named person or organisation is a partner, director or founder of.
* Identifying declared beneficial owners of Armenian companies and their public-contract exposure.
* Screening one name across Georgia, Armenia and Moldova before deeper research.

### Limitations

Georgian results are search-level only: NAPR's ownership extracts sit behind a captcha and a fee and are not automated. Armenian beneficial-owner coverage depends on what each company has declared. Personal identification numbers and home addresses are never returned.
