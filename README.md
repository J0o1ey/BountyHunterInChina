# BountyHunterInChina — Reborn as a Bounty Hunter in China

**[English](README.md)** | **[简体中文](README.zh-CN.md)**

A collection of real-world bug bounty / SRC (Security Response Center) hunting stories from China — how vulnerabilities were actually found, chained, and reported, written by working security engineers.

> The Chinese series title, 重生之我在安全行业讨口子, literally reads *"Reborn: Scraping Out a Living in China's Security Industry"* — a self-deprecating nod to the tough years the industry has been through. All articles are educational write-ups.

## Articles

English translations live in the [`en/`](en/) directory; the original Chinese PDFs are in the repository root.

| # | Article (English) | Author |
| :-- | :-- | :-- |
| 1 | [An Easy SOAP Injection on an SRC](en/01-easy-soap-injection-on-an-src.pdf) | J0o1ey |
| 2 | [Reverse-Engineering an App to Crack Its Packet Signature for Arbitrary Data Replay](en/02-reverse-engineering-app-signature-for-arbitrary-replay.pdf) | J0o1ey |
| 3 | [A No-Brains-Needed Getshell on an SRC](en/03-a-no-brains-needed-getshell-on-an-src.pdf) | J0o1ey |
| 4 | [A Fun Case of Client-Side RCE Plus Server-Side XXE](en/04-client-side-rce-plus-server-side-xxe.pdf) | J0o1ey |
| 5 | [Multiple Techniques to Bypass a WAF and Find XSS at a Well-Known Vendor](en/05-multiple-techniques-bypass-waf-xss.pdf) | J0o1ey |
| 6 | [Aggressive FUZZing: From SSRF to Redis Password Spraying and Mass Reverse Shells](en/06-aggressive-fuzzing-ssrf-to-redis-mass-reverse-shells.pdf) | J0o1ey |
| 7 | [From FUZZ to XSS: Stealing Your Personal Information from an SRC's Official Site](en/07-from-fuzz-to-xss-stealing-personal-info.pdf) | RG |
| 8 | [A Sleight-of-Hand Getshell](en/08-a-sleight-of-hand-getshell.pdf) | RG |
| 9 | [From an Untriggerable XSS to a Dream Chain of XSS in Multiple Critical APIs](en/09-untriggerable-xss-to-dream-chain-xss.pdf) | h0af3ng |
| 10 | [From an Abandoned SSO Login to Executive Profiles Across the Country](en/10-abandoned-sso-login-to-executive-profiles.pdf) | Cat |
| 11 | [Stored XSS with Multiple WAF Bypasses on an SRC](en/11-stored-xss-multiple-waf-bypasses.pdf) | h0af3ng |
| 12 | [A File Upload Battle Against Fortinet Traffic Inspection](en/12-file-upload-vs-fortinet-traffic-inspection.pdf) | J0o1ey |
| 13 | [A Midnight Clutch Kill on an Agent Backend](en/13-midnight-clutch-kill-on-an-agent-backend.pdf) | J0o1ey |
| 14 | [Leveraging Target Domain Quirks for Four RCEs on a Newly Launched SRC](en/14-domain-quirks-four-rces-on-a-new-src.pdf) | J0o1ey |
| 15 | [An SSRF Journey from "Ignored" to "Triaged"](en/15-ssrf-journey-from-ignored-to-triaged.pdf) | J0o1ey |
| 16 | [A GraphQL Bug Hunt That Ended Up Ignored](en/16-graphql-bug-hunt-that-ended-up-ignored.pdf) | J0o1ey |
| Extra #1 | [Notes on a Layer-by-Layer Breakthrough in an Attack-Defense Exercise](en/extra-1-layer-by-layer-breakthrough-ad-exercise.pdf) | J0o1ey |
| Extra #2 | [A City-Wide Attack-Defense Exercise: Pwning N Targets Without a Single 0day](en/extra-2-citywide-exercise-no-0day-needed.pdf) | J0o1ey |
| Extra #3 | [Passing the CISSP Exam in 60 Days: My Experience](en/extra-3-passing-cissp-in-60-days.pdf) | J0o1ey |
| Collection | [Reborn as a Bounty Hunter in China — The Collection (Works Before April 2023)](en/reborn-as-a-bounty-hunter-in-china-collection.pdf) | J0o1ey |
| To be continued… | | |
| Contributions welcome | | |

Each English PDF keeps the original figures from the Chinese edition; only the body text has been translated.

## Community

By popular request there is a project discussion group (WeChat). If the QR code has expired or the group is full, contact the author on WeChat to be invited in. Everyone is welcome to discuss cutting-edge bug hunting and attack-defense cases — or simply what life is like scraping out a living in the security industry.

Feel free to reach out to the author for technical exchanges too. (Hopefully we all learn something from the conversation, rather than one side doing all the asking.)

To help make ends meet, the author also runs full-stack white-box/black-box vulnerability hunting and attack-defense training. If you are interested, or have other compliant project needs, feel free to get in touch via private message — your understanding is appreciated.

![project](https://j0o1ey-1251589192.cos.ap-beijing.myqcloud.com/202402021520821.jpg)

## Update History

### February 2024

I suddenly realized it has been almost a year since the last update. This past year I haven't done much offensive/Pentest work — most of my time went into learning, thinking about, and practicing enterprise security building, so there was no quality content to publish. My apologies for the slow updates.

Considering how rough the security industry has been over the past year, and my own first-hand experience living and working in Beijing, **on Feb 1, 2024 this project was renamed to "Reborn: Scraping Out a Living in China's Security Industry"** (重生之我在安全行业讨口子). The new title reflects the reality of surviving in this field while still telling a few interesting technical stories — that was the whole point of the rename.

### April 2023

After a full year of internet-industry winter under the pandemic, spring finally arrived at the start of the year and the pandemic era essentially ended. Sadly, after last year's losses, my small business won't survive past mid-year. As an entrepreneur in my twenties, I'm preparing to transfer my equity — quite emotional about it. After running around for two years, in the end I still have to honestly let go of unrealistic ideas and accept the cruelty of reality and the market.

Over those two years of running a company and a business, I experienced a lot. Apart from the few blossoming moments of closed deals, most of what I got were bruises from human nature and other people's hearts. Constantly worrying whether the company could survive the next quarter left a twenty-something physically and mentally exhausted — lost, anxious, restless, and drifting away from my original passion. So I chose to give myself enough time to settle down and find my original heart, instead of rushing for quick success at the youngest age of my life.

Looking back now, for people doing both technology and business, perhaps the purest thing left in their hearts is technology itself. I was drawn to hacker stories as a kid, and before I knew it I've been studying security for many years. Limited by IQ and talent, I'm still a script kiddie after all these years. The question I've been asked most by friends over the years is: *"After learning the OWASP Top 10 vulnerability basics, how do I actually hunt bugs effectively?"* Every time, my tongue-tied answer is: "Build up your fundamentals. Build up your fundamentals. Build up your fundamentals."

Within my limited knowledge, I firmly believe — on both the offensive and defensive side — that if you truly understand how developers build things, how ops engineers operate, and how human nature works, you can be unstoppable.

So I compiled the articles from these two years into a collection: 12 sections, 12,890 characters, hoping to show everyone some interesting security problems. All images in the articles were edited and imply no "actual vulnerabilities." In an era of paid knowledge, underpaid engineers scraping by, and struggling small businesses, keeping this free is not easy. As the ancient saying goes, *"one knows honor and disgrace only when well-fed and well-clothed."* Sadly, I'm a poor guy worrying about betrothal gifts who can't afford a house, so there won't be updates for a while — I need to save time to fight life itself. Thank you for understanding.

Hope that someday, somewhere, we meet again at the next mountain and sea.

## Q&A

1. About white-box/black-box bug hunting, many people ask me — *"What if I have no ideas?"*

**My answer: don't pin your hopes on tricks. The bug bounty scene is no longer the era when a script kiddie could own everything.**

**The wise choice is to honestly build a solid foundation in development and security. When your fundamentals are thick enough, ideas and inspiration come as byproducts — accumulate deep, and release thin.**

## Star Trend

[![Stargazers](https://starchart.cc/J0o1ey/BountyHunterInChina.svg)](https://starchart.cc/J0o1ey/BountyHunterInChina.svg)

## License

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

This project is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/) (CC BY-NC-SA 4.0) © J0o1ey.

In short: you are free to share and adapt the articles (including translating them) for **non-commercial** purposes, as long as you credit the original authors and release adaptations under the same license. **Commercial use requires the author's prior written permission.** The Chinese originals are the authoritative version; English translations are community contributions for reference.
