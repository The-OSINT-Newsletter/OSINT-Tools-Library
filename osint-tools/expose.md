---
description: >-
  Tool Description : A paid OSINT platform that turns an email, phone number,
  social profile URL, or domain into a structured report on a person, company,
  or school.
---

# Expose

| **Expose**       | **Quick Overview**                                                                                                                                                                                            |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://expose.team/](https://expose.team/)                                                                                                                                                                  |
| What it does     | Looks up a person, company, or school from one public identifier and returns a structured report. A person takes an email, phone number, or profile URL. A company or school takes a domain or a profile URL. |
| How to use it    | Sign in, choose the entity type, paste one identifier, then read, export, or file the report. The same search is available from the API, MCP server, CLI, agent skill, Zapier, and Apify.                     |
| Cost             | Paid. Plans start at $8 a month. One search uses one credit. There is no free trial.                                                                                                                          |
| Account required | Yes.                                                                                                                                                                                                          |
| Cookies          | Session, preference, security, and advertising cookies. The site honors Do Not Track.                                                                                                                         |
| Ownership        | Operated by Expose, servers are in the United States.                                                                                                                                                         |
| Use in Reporting | Useful when an investigation already has an email, phone number, profile URL, or domain and needs a documented public-record report, a PDF, or a place to connect several subjects.                           |

### What does Expose do?

Expose is a structured search platform for people, companies, and schools. You start from a single identifier rather than a name. The platform returns a report built from publicly available information, with the fields that the record actually contains.

A person search accepts:

- an email address
- a phone number in international format, beginning with `+`
- a social or profile URL on a supported host, such as LinkedIn, Facebook, X, Instagram, GitHub, YouTube, Reddit, Telegram, TikTok, and others shown in the product

A company search and a school search each accept a domain or a profile URL.

**The lowdown:** Expose is built for the step after you already hold an identifier. It is a poor fit for a name-only people search, and a strong fit for turning an email, number, profile, or domain into a report you can export or keep on an investigation.

### How to Use:

**1. Create an account at** [**https://expose.team/**](https://expose.team/) **and open the platform.**

**2. Choose Person, Company, or School, then choose the identifier type.**

For a person, paste an email, a phone number that starts with the country code, or a profile URL. For a company or a school, paste a domain or a profile URL. One identifier is one search, and one search uses one credit.

**3. Read the report.**

A person report can include profile URLs, names, other emails and phone numbers, identities, languages, locations, work experience, education, significant dates, vehicles, code repositories, skills, and photos. A company or school report can include names, profile URLs, locations, and a website panel with a description, screenshot, design details, and performance scores. A card with nothing behind it says there is not enough data to render it.

**4. Export a PDF, or add the subject to an investigation.**

An investigation can hold more than one subject. It includes link analysis, a timeline, points of interest on a map, findings, and a written report. Investigations can be shared with edit or view access.

**5. Run the same search outside the browser if that fits the workflow.**

The platform, REST API, MCP server, CLI (`npm install -g @expose-team/cli`), agent skill, Zapier, and Apify all draw from the same credit balance. A phone lookup on the CLI looks like `expose person +14155551234`. A company lookup looks like `expose company stripe.com`. `expose credits` shows the balance for the current billing cycle.

The site also publishes a few free utilities, including a username check at [https://expose.team/tools](https://expose.team/tools). Those utilities are separate from the paid person, company, and school search.

### Cost

- [ ] Free
- [ ] Partially Free
- [x] Paid

Paid subscription, billed monthly. Published plans as of this writing:

| Plan         | Price | Search credits / month | AI generations / month |
| ------------ | ----- | ---------------------- | ---------------------- |
| Beginner     | $8    | 40                     | 2                      |
| Builder      | $20   | 100                    | 5                      |
| Professional | $40   | 200                    | 10                     |
| Expert       | $100  | 500                    | 20                     |
| Master       | $200  | 1,000                  | 30                     |

Person, company, and school search, PDF export, investigations, and access through the API, MCP, CLI, and agent skill are included on every plan. Email support starts on the Professional plan. An unlimited plan is arranged through [support@expose.team](mailto:support@expose.team).

Credits renew with the billing cycle and unused credits do not roll over. Changing plan resets the billing date. There is no free trial. A subscription can be cancelled, and remaining credits are cleared at the end of that cycle.

AI generations are a separate allowance from search credits. They are used when compiling an AI report from findings.

## Data Processing

### Account Required:

- [x] Yes
- [ ] No

An account is required to search and to use the API, MCP server, CLI, and integrations.

### Cookies:

The privacy policy describes session cookies to operate the service, preference cookies for settings. The service honors Do Not Track signals. Refusing cookies can block parts of the site.

### Use in Reporting

Expose fits once an investigation already has a pivot:

- An email, phone number, or profile URL for a person, with the report showing other identifiers, profiles, roles, and education when those are in the public record.
- A domain or profile URL for a company or school, with the report showing the organization name, profiles, locations, and website detail when those are present.
- A PDF of a single report for a file or a disclosure packet.
- An investigation that keeps several subjects together, with link analysis, a timeline, mapped points of interest, and findings.

Treat the report as a lead and a record of what the public sources returned. Confirm anything that will be published or acted on. An empty section means that field was not in the result, which is different from proof that the fact does not exist. |

### Summary

Expose sits in the collection and analysis stage of an OSINT workflow, after an identifier is already in hand. It is most useful for people work that starts from an email, phone number, or social profile, and for company or school work that starts from a domain or a profile URL. It is a paid, account-gated product, and the report still needs independent verification.

### Ownership

[expose.team](https://expose.team/) is operated by Expose. Support contact: [support@expose.team](mailto:support@expose.team). Company profile: [Expose on LinkedIn](https://www.linkedin.com/company/expose-team), [Expose on X](https://x.com/exp0se_team), [Expose on YouTube](https://www.youtube.com/@expose-team-ai).

### Ethical Considerations

- The product is limited to publicly available information. The person running the search is still responsible for the law that applies where they work.
- A person search needs an email, phone number, or profile URL. Collecting those identifiers just to run them through a search tool has its own privacy cost.
- An empty result is not confirmation that a person, company, or claim is genuine, and a populated result is not confirmation that every field is current.

### Related Tools:

- [OSINT Industries](osint-industries.md)
- [Epieos](epieos.md)
- [BeenVerified](beenverified.md)
- [That's Them](thats-them.md)
- [Osint.ly](osintly.md)

#### Sources

[https://expose.team/](https://expose.team/)

[https://expose.team/pricing](https://expose.team/pricing)

[https://expose.team/tools](https://expose.team/tools)

[https://expose.team/legal/terms](https://expose.team/legal/terms)

[https://expose.team/legal/privacy](https://expose.team/legal/privacy)

[https://www.linkedin.com/company/expose-team](https://www.linkedin.com/company/expose-team)
