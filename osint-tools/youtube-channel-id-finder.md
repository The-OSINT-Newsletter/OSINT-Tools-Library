---
description: >-
  Tool Description: A free web tool that turns any YouTube channel URL, @handle,
  video or Shorts link, custom URL or legacy username into the channel's
  permanent ID.
---

# YouTube Channel ID Finder

| **YouTube Channel ID Finder** | **Quick Overview**                                                                                                                                           |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| URL                           | [https://www.collabpals.com/tools/youtube-channel-id-finder](https://www.collabpals.com/tools/youtube-channel-id-finder)                                     |
| What it does                  | Finds the permanent channel ID behind a YouTube URL, @handle, video or Shorts link, or username, one at a time or in bulk.                                   |
| How to use it                 | Paste a channel URL, @handle, video or Shorts link and press Find; use the Bulk Lookup tab for up to 10 at once.                                             |
| Cost                          | Free.                                                                                                                                                        |
| Account required              | No.                                                                                                                                                          |
| Cookies                       | \_\_Host-COLAB cookie (Likely a security-related or session-management cookie).                                                                              |
| Ownership                     | Built and run by CollabPals, a YouTube creator growth platform based in Toronto, Canada.                                                                     |
| Use in Reporting              | Helps identify and consistently reference YouTube channels, links videos to their publishing channels, and prepare channel lists for further OSINT research. |

### What does YouTube Channel ID Finder do?

YouTube channels are known by several names: a display name, an @handle, sometimes an old custom URL or username. All of these can change. The channel ID (UC followed by 22 characters) never does.

YouTube Channel ID Finderl takes whatever the investigator has (a channel link, an @handle, a video link, a Shorts link, an embed link or a legacy username) and returns the channel ID, the channel name, the current @handle and the avatar. It also builds the related links: the canonical channel URL, the channel's RSS feed URL (useful for monitoring new uploads), the YouTube Data API v3 URL and a subscribe link. For a video or Shorts input it also shows the video ID with its watch, short, embed and maximum-resolution thumbnail URLs.

It reads only the public YouTube page, so it needs no API key, no YouTube login and no account.

**The lowdown:** Its main value is turning a channel handle, URL or video link into a consistent identifier that can be used in research records and other tools.

### How to Use:

**1. Open the platform on your web browser then paste a channel URL, @handle, video link, Shorts link, or username into the box and press Find.**

<img src="../.gitbook/assets/unknown (779).png" alt="" height="356" width="602">

**2. Copy the channel ID or any of the generated links (channel URL, RSS feed, API URL, subscribe link) with one click.**

<img src="../.gitbook/assets/unknown (780).png" alt="" height="429" width="602">

**3. For several channels, open the Bulk Lookup tab, paste up to 10 entries (one per line) and copy or export the results table.**

<img src="../.gitbook/assets/unknown (781).png" alt="" height="301" width="602">

### Cost

* [x] Free
* [ ] Partially Free
* [ ] Paid

## Data Processing

### Account Required:

* [ ] Yes
* [x] No

### Cookies:&#x20;

The site uses a \_\_Host-COLAB cookie (Likely a security-related or session-management cookie but unable to verify). No YouTube login and no YouTube cookies are needed.

### Use in Reporting

YouTube Channel ID Finder can help:

* Identify channels consistently: Convert handles and channel URLs into channel IDs for case files and research databases.
* Link videos to channels: Use supported video URLs to find the associated channel ID, then verify the relationship on YouTube.
* Prepare monitoring lists: Create a standardised list of channel IDs for manual monitoring or compatible research workflows.
* Support RSS monitoring: Generate or construct channel-specific RSS feed URLs for tracking new public uploads.
* Support API research: Use channel IDs as inputs for compatible YouTube Data API workflows or other tools.
* Reduce ambiguity: Distinguish channels with similar names by retaining their unique identifiers rather than relying on display names alone.
* Document changes: Preserve the channel ID alongside historical handles and URLs when a creator rebrands.
* Improve reproducibility: Record the original input, returned ID, access date, and independent verification source.
* Build investigative leads: Use a verified channel ID as a starting point for examining public videos, descriptions, linked accounts and other publicly available material.
* Create structured datasets: Use the advertised CSV export for bulk results, checking the exported data before incorporating it into a report.

**Note from the developer:** Channel names and @handles change, which breaks attribution in reports written weeks earlier. Recording the permanent channel ID lets a report cite a stable identifier that can be re-checked later even after a rename. It also helps confirm that two differently named channels are the same account, link a video or Short back to the channel that uploaded it, and set up an RSS feed to monitor a channel's new uploads.

| **Capabilities**                                                                                                                   | **Limitations**                                                                                                                |
| ---------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| Accepts channel URLs (/channel/, /@handle, /c/, /user/), bare @handles, video links, Shorts links, embed links and raw channel IDs | Works only on public channels and videos; private, deleted or terminated channels cannot be resolved.                          |
| Returns channel ID, name, current handle and avatar.                                                                               | Bulk mode is limited to 10 entries per run.                                                                                    |
| Generates channel URL, RSS feed URL, YouTube Data API v3 URL and subscribe link.                                                   | It is a lookup, not an analytics tool: it does not return subscriber history, upload history or comments.                      |
| Extracts video IDs with watch, short, embed and thumbnail URLs.                                                                    | Because it reads the public YouTube page, a change to YouTube's page layout could interrupt lookups until the tool is updated. |
| Bulk lookup of up to 10 entries. One-click copy.                                                                                   | A channel ID does not prove the real-world identity or ownership of a channel                                                  |

### Summary

YouTube Channel ID Finder is a free, no sign-up YouTube Channel ID Finder that converts any channel link, @handle, video or Shorts link into the channel's permanent ID, plus its RSS feed and API URLs, singly or in bulk.

Its bulk lookup and export functions make it useful for organising channel lists and preparing further research and it’s best treated as a starting point for identifier resolution, with important findings verified against YouTube or another authoritative source.

### Ownership

[CollabPals](https://www.collabpals.com/), a YouTube creator growth platform based in Toronto, Canada. The tool is one of its free public tools.

### Ethical Considerations

* Use the tool to investigate publicly accessible content and comply with applicable laws and platform terms.
* Do not treat a channel ID as proof of a person's real-world identity.
* Verify significant findings independently, particularly where a video URL is used to infer which channel uploaded it.
* Avoid conflating channels with similar names or assuming that linked channels have the same operator.
* Be careful when publishing bulk channel lists if they could expose individuals to harassment or other foreseeable harm.
* Follow applicable copyright rules when preserving or reproducing video content.

### Related Tools:

* [MW Metadata](mw-metadata.md)
* YouTube Studio advanced settings (for your own channel)
* Amnesty YouTube DataViewer

#### Sources

[https://www.collabpals.com/tools/youtube-channel-id-finder](https://www.collabpals.com/tools/youtube-channel-id-finder) &#x20;

[https://www.collabpals.com/](https://www.collabpals.com/)&#x20;

[https://www.collabpals.com/privacy](https://www.collabpals.com/privacy)&#x20;

[https://support.google.com/youtube/answer/3250431](https://support.google.com/youtube/answer/3250431)&#x20;



_With thanks to Andrew for submitting this tool to the OSINT Tool Library._&#x20;
