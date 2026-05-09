---
description: >-
  Tool Description : Instantly recovers hidden spoiler text on MacOS within a
  Telegram chat.
---

# Telegram Spoiler Decoder

| **Telegram Spoiler Decoder** | **Quick Overview**                                                                                                       |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| URL                          | [https://spoiler.soxoj.com/](https://spoiler.soxoj.com/)                                                                 |
| What it does                 | Reveals hidden text from Telegram messages by decoding spoiler formatting resembling braille.                            |
| How to use it                | Simply upload an image/screenshot with the spoiled text you want to decode and the tool will instantly do this for you.  |
| Cost                         | Free                                                                                                                     |
| Account required             | No                                                                                                                       |
| Cookies                      | Google analytics cookies that do not capture personal information.                                                       |
| Ownership                    | Dmitry Danilov, a prominent OSINT investigator, researcher & developer from Ukraine.                                     |
| Use in Reporting             | Enrichment purposes. (No solid reporting examples yet but widely discussed as a useful tool in OSINT forums.)            |

### **What does the Telegram Spoiler Decoder do?**

The Telegram Spoiler Decoder is a third-party tool that removes Telegram’s spoiler formatting, allowing users to view text that has been intentionally hidden in braille-type messages via Telegram client on MacOS.&#x20;

Essentially, if a user has shared their Telegram screen/taken a screenshot and used spoilers to hide certain information, this tool can help reveal said info.&#x20;

Usually, a spoiler is only revealed on tapping the direct message but in some parts of the MacOS Telegram client, it works by the last message in the chat list and pinned message using a fallback that turns text into pseudo-Braille characters with one-way mapping.

See here: [https://github.com/overtake/TelegramSwift/blob/579cebbf0c01fd41b712eff3647fa7f69db9665d/Telegram-Mac/Extensions.swift#L1805](https://github.com/overtake/TelegramSwift/blob/579cebbf0c01fd41b712eff3647fa7f69db9665d/Telegram-Mac/Extensions.swift#L1805)&#x20;

**The lowdown:** The decoder strips this formatting so the full message can be read in plain text. You can upload your own screenshots, play with dictionaries, adjust region detection, or enter pseudo-Braille by hand.

### How to Use:

1. Head to [https://spoiler.soxoj.com/](https://spoiler.soxoj.com/) to view the screen below.&#x20;

![](<../.gitbook/assets/unknown (2) (1) (1) (1) (1) (1) (1) (1).png>)

&#x20;                                                            &#x20;

2\. Obtain your image (from a Telegram channel, saved file or web scraping and upload it for decoding.

![](<../.gitbook/assets/unknown (3) (1) (1) (1) (1) (1) (1) (1).png>)

3\. Let the Decoder do its magic and voila! Your decoded text should appear in the blue box, in the same way as the below:

<br>

![](<../.gitbook/assets/unknown (4) (1) (1) (1) (1) (1) (1) (1).png>)



### Cost:

* [ ] Paid
* [ ] Partially Free
* [x] Free

\
Data Processing
---------------

### Account required:

* [ ] Yes
* [x] No

### Cookies:&#x20;

The decoder uses Google Analytics and session-tracking cookies to identify visitors and measure website usage and engagement.

### &#x20;Use in Reporting

There are currently no cited examples of use in reporting (yet) but the tool has been widely discussed as a useful tool in OSINT forums.&#x20;

Once decoded, the recovered text can be analysed for reportable insights such as:

* Identifying leaked login details, private messages, or code words
* Extracting email addresses, links, websites, or usernames
* Finding signs of cyber threats or security issues (indicators of compromise)

| **Capabilities**                                                              | **Limitations**                                                             |
| ----------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| Decodes hidden spoiler text from Telegram messages/screenshots.               | Cannot identify the sender or reveal personal account information.          |
| Works entirely on data provided by the user with no account access required.  | Cannot access Telegram servers or decrypt end-to-end encrypted messages.    |
| Works best on well-formed spoiler messages/screenshots with complete content. | Does not guarantee recovery if the spoiler content is corrupted/incomplete. |

### Summary

A local, privacy-safe decoder for Telegram spoilers, the tool is useful for the enrichment phase of an OSINT workflow, designed purely to reveal hidden content provided by the user, without accessing personal accounts or sensitive information.

### Ownership

Dmitry Danilov, under the pseudonym [‘Soxoj’](https://soxoj.com/), is a prominent OSINT investigator, researcher & developer from Ukraine, who developed and owns this Telegram Spoiler Decoder.&#x20;

### Ethical Considerations

* Respect user privacy when revealing hidden or obscured content.
* Use the tool only for legitimate research, security, or investigative purposes.
* Avoid causing harm by exposing sensitive or personal information.
* Ensure use complies with laws and platform terms of service.
* Be transparent about how the tool was used in your investigation.

### Related Tools:

* CyberChef
* Unicode Inspector<br>

#### Sources:

[https://spoiler.soxoj.com/](https://spoiler.soxoj.com/)&#x20;

[https://soxoj.com/](https://soxoj.com/)&#x20;

[https://tgstat.com/channel/@soxoj\_insides](https://tgstat.com/channel/@soxoj_insides)&#x20;

[https://telemetr.io/ru/channels/1949785803-soxoj\_insides/posts](https://telemetr.io/ru/channels/1949785803-soxoj_insides/posts)&#x20;

[https://github.com/rawrdcore/tg-hidden-messages-decoder](https://github.com/rawrdcore/tg-hidden-messages-decoder)&#x20;

[http://undercodetesting.com/unmasking-hidden-messages-how-this-free-osint-tool-cracks-telegrams-secret-spoiler-code-video/](http://undercodetesting.com/unmasking-hidden-messages-how-this-free-osint-tool-cracks-telegrams-secret-spoiler-code-video/)

