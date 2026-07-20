---
title: Support & FAQ
nav_order: 7
permalink: /support-faq/
description: >-
  How to reach Convicta support (the /feedback command in the Telegram bots) and answers to the most common questions across the Convicta ecosystem.
---

# Support & frequently asked questions

This page covers how to reach us and answers the most common questions about the Convicta ecosystem — Convicta News, Polymarket Pulse, the web app, and the Chrome extension.

## How do I get help?

The fastest way is the **`/feedback`** command inside the Telegram bots:

- **Convicta News:** send `/feedback` to [@Convicta_news_bot](https://t.me/Convicta_news_bot)
- **Polymarket Pulse:** send `/feedback` to [@Convicta_pulse_bot](https://t.me/Convicta_pulse_bot)

Tell us what you were doing, what you expected, and what happened. Screenshots help. Convicta is in community testing, so feedback directly shapes what we fix and ship next.

## Products and setup

**What is the difference between Convicta News and Polymarket Pulse?**
Convicta News is a personal, multi-source news feed for everyone. Polymarket Pulse turns news and market data into prediction-market alerts for people who follow or trade on [Polymarket](https://polymarket.com). They share one engine but are separate Telegram Mini Apps. The [Introduction]({{ '/' | relative_url }}) has a "who is it for" matrix.

**Which product do I need?**
If you want one dense news feed instead of fifty channels — Convicta News. If you trade or follow Polymarket — Pulse, plus the Chrome extension if you spend time on polymarket.com itself. See the matrix in the [Introduction]({{ '/' | relative_url }}).

**Do I have to connect a wallet to use Pulse?**
For the personalized feed and personal alerts, yes — a Polymarket 0x wallet address. There is also a read-only "Browse Explore without a wallet" path. See [Getting started: Polymarket Pulse]({{ '/getting-started/polymarket-pulse/' | relative_url }}).

**Does adding a wallet give Convicta access to my funds?**
No. Convicta never manages or touches funds — no keys, no trades, no access. A wallet address only lets us read public data to personalize your alerts. Any address works, even an empty one.

**How do I sign in on the web?**
With Google, email, or Telegram — see [Web app]({{ '/getting-started/web-version/' | relative_url }}). One account, one plan, everywhere.

## Chrome extension

**Is the extension in the Chrome Web Store?**
Not yet — the store listing is upcoming. Today you install it as an unpacked extension in developer mode; the steps take about a minute. See [Getting started: Chrome extension]({{ '/getting-started/chrome-extension/' | relative_url }}).

**Do I need a Convicta account to use the extension?**
No. The market widget, news, Edge, and coverage dots work anonymously. Signing in adds your personal alerts, portfolio brief, and follow/watchlist actions.

**Can I turn off parts of the extension?**
Yes — every surface (widget, Edge, notification center, coverage dots, trader tools, tab flash, and more) has its own toggle in the extension's Options. See the [Settings map]({{ '/settings/' | relative_url }}#chrome-extension).

**Does the extension trade for me or touch my Polymarket account?**
No. It reads public page context and talks only to Convicta's backend. It never places trades and never asks for keys.

## Feed and alerts

**Why did a particular story show up in my feed?**
Because it matched an explicit rule. Every item traces back to named entities and the rule that connected them — not a hidden similarity score. Cards carry a "why you got this" context line.

**Do I get real-time news alerts?**
No — and we do not claim to. News-to-market matching runs on a regular batch cadence: timely and complete, not a millisecond-live ticker. Pulse's price, whale, and trader alerts do run off live market data.

**An alert stopped arriving — what should I check?**
Three switches, in order: the alert's own on/off toggle, the master toggle of its notification module, and (for News) quiet hours or a snooze. The [Settings map]({{ '/settings/' | relative_url }}) lists where each one lives.

**Can I use my own news sources?**
Yes — on the News+ plan you can add your own sources and import an OPML file. Free to try during the testing period. See [Pricing]({{ '/pricing/' | relative_url }}).

**Why is a summary or translation missing?**
AI-assisted surfaces (summaries, translations, the experimental Edge estimate) are metered while we test, and may be temporarily limited. When they are, you get the original text or a trimmed excerpt instead — the story itself still arrives.

## Pricing

**Is Convicta really free right now?**
Yes. Convicta is in open community testing: every new user gets a two-month free grant on the full-featured tier. Access is free because we are still collecting feedback and some features are not yet fully polished. Nothing charges automatically afterwards — you choose a plan or stay on Free. See [Pricing]({{ '/pricing/' | relative_url }}).

**What are the plans after the free period?**
Free ($0), News+ ($6/mo), Pulse Pro ($12/mo), and Pulse Edge ($20/mo, includes News+). Annual billing gives two months free. Full feature↔plan map: [Pricing]({{ '/pricing/' | relative_url }}).

**Is Edge financial advice?**
No. Edge is an experimental, AI-computed fair-value estimate — one additional metric to weigh. Decisions are always yours.

## Data

**How is my data handled?**
See the [Privacy Policy]({{ '/privacy-policy/' | relative_url }}) and [Terms of Service]({{ '/terms-of-service/' | relative_url }}).
