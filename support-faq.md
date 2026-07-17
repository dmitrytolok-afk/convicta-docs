---
title: Support & FAQ
nav_order: 5
permalink: /support-faq/
---

# Support & FAQ

## Getting help

The fastest way to reach us is the **`/feedback`** command inside the Telegram bots:

- **Convicta News:** send `/feedback` to [@Convicta_news_bot](https://t.me/Convicta_news_bot)
- **Polymarket Pulse:** send `/feedback` to [@Convicta_pulse_bot](https://t.me/Convicta_pulse_bot)

Tell us what you were doing, what you expected, and what happened. Screenshots help.

> This is a community testing version, so we're actively reading feedback — it directly shapes what we fix and ship next.

## Frequently asked questions

**What's the difference between Convicta News and Polymarket Pulse?**
Convicta News is a personal, multi-source news feed for everyone. Polymarket Pulse turns news into prediction-market signals and is built for people who already trade on [Polymarket](https://polymarket.com). They share the same engine but are two separate Telegram Mini Apps. See the [Introduction]({{ '/' | relative_url }}).

**How do I get into Pulse?**
Pulse is a community testing version. It's aimed at existing Polymarket traders, since it personalizes around your Polymarket wallet. See [Getting started: Polymarket Pulse]({{ '/getting-started/polymarket-pulse/' | relative_url }}).

**Is it really free?**
Yes — free for your first two months while we're in community testing (a 60-day trial on News, a 60-day grant on Pulse's full tier). Access is free right now because we're still collecting feedback and some features aren't yet fully polished. After that you can stay on a free tier or subscribe. See [Pricing]({{ '/pricing/' | relative_url }}).

**Why are some features "warming up"?**
The AI-assisted surfaces — news summaries, translations, and the Pulse **Edge** read — are metered and may be limited or paused while we're in community testing. The deterministic core (feed, dedup, tagging, price/resolution/trader alerts) runs normally. We flag these features as ⏳ warming up in the docs.

**Do I get real-time news alerts?**
No — and we don't claim to. News-to-market matching runs on a regular batch cadence. It's designed to be timely and complete, not a millisecond-live ticker. Pulse's price and market-status alerts, however, run off live market data.

**Why did a particular story show up in my feed?**
Because it matched an explicit rule. Convicta's matching is deterministic and auditable: every item traces back to named entities and the rule that connected them, not a hidden similarity score. Cards carry a "why you got this" context line.

**Can I use my own news sources?**
Yes, on the paid News Standard plan you can add your own sources and import an OPML file. It's free to try during the 2-month trial. See [Getting started: Convicta News]({{ '/getting-started/convicta-news/' | relative_url }}).

**Do I have to connect a wallet to use Pulse?**
For the personalized feed and alerts, yes — a Polymarket 0x wallet address. There's also a read-only "Browse Explore without a wallet" path if you just want to look around.

**How do I sign in on the web?**
With Google, email, or Telegram. See [Web version]({{ '/getting-started/web-version/' | relative_url }}).

**How is my data handled?**
See our [Privacy Policy]({{ '/privacy-policy/' | relative_url }}) and [Terms of Service]({{ '/terms-of-service/' | relative_url }}).
