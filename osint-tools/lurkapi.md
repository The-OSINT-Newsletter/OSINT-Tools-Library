---
description: >-
  Tool Description: A public-data collection API and MCP server that retrieves
  structured information from 16 social media platforms in one consistent JSON
  format.
---

# LurkAPI

| **LurkAPI**      | **Quick Overview**                                                                                                                          |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| URL              | [https://lurkapi.com/](https://lurkapi.com/)                                                                                                |
| What it does     | Returns public posts, profiles, comments, transcripts and ads from 16 platforms as JSON.                                                    |
| How to use it    | Search through the website's free playground, make API requests using an API key, or connect it to a compatible AI application through MCP. |
| Cost             | Partially free: 100 free credits, then packs from $9.                                                                                       |
| Account required | Yes for the API (free signup). No for the free web tools.                                                                                   |
| Cookies          | Google Analytics, a first-party referral/visit-attribution cookie, and Microsoft Clarity tracking.                                          |
| Ownership        | LurkAPI (Mesmer s.r.o., Slovakia)                                                                                                           |
| Use in Reporting | Capture and quote public posts, comments, video transcripts and ad records.                                                                 |

### What does LurkAPI do?

LurkAPI is a web API with a set of free browser tools built on it. One GET request returns public data as JSON from 16 platforms: Facebook, Instagram, TikTok, YouTube, Reddit, X (Twitter), LinkedIn, Threads, Bluesky, Telegram, Snapchat, Truth Social, Google (Maps, News, autocomplete and the Ads Transparency Center), eBay, Linktree and any public web page.

It has 88 endpoints: account profiles, an account's posts and videos, single posts, comments and replies, search, video transcripts (with speech-to-text when a TikTok or Instagram video has no captions), and the ads in Meta's Ad Library, Google's Ads Transparency Center, LinkedIn's Ad Library and TikTok's ad library for the EU, UK, Switzerland and Turkey.

The same endpoints are available as an MCP server (https://api.lurkapi.com/mcp), so an AI assistant such as Claude or ChatGPT can run the lookups when asked in plain language.

Free web tools that need no account (5 tries a day) include a TikTok comment viewer and CSV exporter, an Instagram profile lookup, a LinkedIn profile viewer, YouTube, TikTok and Instagram transcript tools, a Facebook Ad Library search, a Google Ads Transparency search, a Snapchat story viewer, and Instagram and TikTok username checkers: https://lurkapi.com/free-tools.

**The lowdown:** It brings information from several platforms into a consistent, machine-readable format that can be searched, compared, and analysed.

### How to Use:

Without an account:

**1. Open a free tool, e.g.** [**https://lurkapi.com/free-tools/tiktok-comment-viewer**](https://lurkapi.com/free-tools/tiktok-comment-viewer)

<img src="../.gitbook/assets/unknown (830).png" alt="" height="277" width="602">

**2. Paste a link or username and run it. Export to CSV where the tool offers it.**

<img src="../.gitbook/assets/unknown (831).png" alt="" height="364" width="602">

With the API:

**1. Sign in at** [**https://lurkapi.com/login**](https://lurkapi.com/login) **with Google or an email code (100 free credits, no card).**

**2. Copy an API key from the dashboard.**

<img src="../.gitbook/assets/unknown (833).png" alt="" height="172" width="602">

\
**3. Send a request, e.g. curl "**[**https://api.lurkapi.com/v1/tiktok/profile?handle=nik**](https://api.lurkapi.com/v1/tiktok/profile?handle=nike) **"-H "x-api-key: YOUR\_API\_KEY"**

**4. Read the JSON. Each endpoint's docs page (https://lurkapi.com/docs) lists its parameters and fields, shows a real response and has a live playground.**

**With an AI assistant:** add [https://api.lurkapi.com/mcp](https://api.lurkapi.com/mcp)  as a custom connector in Claude (in ChatGPT, [https://api.lurkapi.com/mcp?compact](https://api.lurkapi.com/mcp?compact) ), sign in through the browser, and ask, e.g. "What ads is this page running on Facebook?"

### Cost

* [ ] Free
* [x] Partially Free
* [ ] Paid

100 free credits, then packs from $9.

## Data Processing

### Account Required:

* [x] Yes
* [x] No

Yes for the API (free signup). No for the free web tools.

### Cookies:&#x20;

LurkAPI uses Google Analytics cookies (\_ga and \_ga\_Q1TPNN4WTJ) to distinguish visitors and measure website usage. Its first-party lk\_first cookie records initial visit attribution information, including the landing page, referral source, country and timestamp. A Microsoft MUID cookie on the third-party .clarity.ms domain supports visitor recognition and analytics through Microsoft services.&#x20;

### Use in Reporting

LurkAPI can be used to:

* Capture a public post, profile or comment thread as structured JSON (IDs, dates and counts as the platform shows them), to cite or archive alongside screenshots.
* Get the full transcript of a YouTube, TikTok or Instagram video, to search a long video and quote it word for word.
* Check which ads a page, company or domain has run in Meta's Ad Library, Google's Ads Transparency Center or LinkedIn's Ad Library, with run dates and, where published, payer and reach details.
* Export every comment on a TikTok or YouTube video for analysis of coordinated behaviour or reactions.
* Follow accounts across X, Threads, Bluesky, Telegram and Truth Social in one format.

**Important Note:** As LurkAPI is a relatively new service, there are no cited published investigations/reports yet.&#x20;

| **Capabilities**                                                                | **Limitations**                                                                                              |
| ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| 16 platforms, 88 endpoints, one consistent JSON format.                         | Public data only: no private profiles, private messages or content behind a login.                           |
| Profiles, posts, comments and replies, search, video transcripts.               | Results show what the platform displays publicly at request time; responses may be cached for a short while. |
| Ad libraries: Meta, Google Ads Transparency, LinkedIn, TikTok (EU, UK, CH, TR). | No archive of deleted content: it reads current pages.                                                       |
| Speech-to-text for TikTok and Instagram videos without captions.                | A platform change can break an endpoint for a while (checked hourly, results at https://lurkapi.com/status). |
| Any public web page as HTML, markdown or text.                                  | TikTok's ad library covers only the EU, UK, Switzerland and Turkey.                                          |
| Free browser tools with no account (5 tries a day), several with CSV export.    | Without an account, 5 tries a day; with one, 50 requests per 10 seconds.                                     |
| MCP server for Claude, ChatGPT, Cursor and other AI clients.                    | Read-only: it can't post, like, follow or message.                                                           |
| Code samples in curl, Node.js, Python, Go, PHP and Ruby; an OpenAPI 3.1 spec.   | <p><br></p>                                                                                                  |

### Summary

LurkAPI is a useful public-data collection tool if you need to gather information from multiple social-media platforms, advertising libraries and websites without building separate collection systems for each source.

It’s most useful at the collection stage of social media investigations: capturing posts, comments, transcripts and ad records for analysis and citation.Important findings should always be checked against the original platform, with dates, URLs and supporting evidence preserved.

### Ownership

LurkAPI is built and run by Mesmer Lord, a solo founder, and operated by Mesmer s.r.o., a company in Slovakia. It launched in 2026 and is self-funded. Contact: support@lurkapi.com

### Ethical Considerations

* Public is not the same as fair game: consider the privacy of the people whose posts and comments you collect, especially private individuals and minors.
* Collect only what the investigation needs and delete it when done; GDPR and similar laws may apply to personal data.
* Don't use it to harass, dox, or stalk anyone.
* The data is a snapshot of what a platform showed at one moment; verify it and archive the original page before citing.
* Platform terms of service may restrict automated collection; check what applies to your use.
* Transcripts, especially speech-to-text, can contain errors; check quotes against the original video.

### Related Tools:

* ScrapeCreators&#x20;
* Apify&#x20;
* Bright Data&#x20;
* Data365&#x20;
* [Export Comments](export-comments.md)
* [Social Searcher](social-searcher.md)

#### Sources

[https://lurkapi.com/](https://lurkapi.com/)&#x20;

[https://lurkapi.com/docs](https://lurkapi.com/docs)&#x20;

[https://lurkapi.com/free-tools](https://lurkapi.com/free-tools)&#x20;

[https://lurkapi.com/pricing](https://lurkapi.com/pricing)&#x20;

[https://lurkapi.com/privacy](https://lurkapi.com/privacy)&#x20;

[https://lurkapi.com/terms](https://lurkapi.com/terms)&#x20;

[https://lurkapi.com/status](https://lurkapi.com/status)&#x20;

[https://lurkapi.com/openapi.json](https://lurkapi.com/openapi.json)&#x20;



_With thanks to Mesmer Lord for submitting this tool to the OSINT Tool Library._
