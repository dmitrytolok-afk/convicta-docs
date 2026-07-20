---
title: Introduction
nav_order: 1
permalink: /
description: >-
  What Convicta is: a news-to-action ecosystem — 1,600+ sources in 20 languages, rule-based news-to-market matching for Polymarket, four surfaces. Start here.
---

# What is Convicta?

**Convicta is a news-to-action ecosystem for people who follow world events and prediction markets.** It ingests news from 1,600+ sources in 20 languages, works out what each story actually means, and — when the story moves a market — connects it to the exact [Polymarket](https://polymarket.com) prediction market it affects. You get one clean, relevant notification instead of monitoring fifty channels yourself.

The pipeline in one line: **news → meaning → action.** News comes in from everywhere; a rule-based matching engine reduces each story and each market to explicit relationships (*who did what to whom*) and links them only when those relationships line up; the result reaches you as a feed item, an alert, or a digest. Every news→market match is traceable to the exact rule that produced it — no black-box similarity scores.

## What products are in the Convicta ecosystem?

Convicta is one engine with four surfaces. Each works on its own; together they cover Telegram, the browser, and polymarket.com itself.

### Convicta News — a personal news feed in Telegram

**Bot: [@Convicta_news_bot](https://t.me/Convicta_news_bot)**

Convicta News is a Telegram Mini App that turns 1,600+ news sources in 20 languages into one personal feed. It filters, de-duplicates, and tags incoming stories so you see each story once, in the categories you chose; AI summaries compress each item to its point; a daily digest can replace the running stream entirely. Open to everyone. See [Getting started: Convicta News]({{ '/getting-started/convicta-news/' | relative_url }}).

### Polymarket Pulse — prediction-market alerts in Telegram

**Bot: [@Convicta_pulse_bot](https://t.me/Convicta_pulse_bot)**

Polymarket Pulse is a Telegram Mini App for people who follow or trade Polymarket prediction markets. It delivers alerts on trades, whale activity, price moves, and market resolutions; tracks your portfolio and the traders you follow; connects breaking news to the specific markets it moves; and shows **Edge** — an experimental AI fair-value estimate for a market. See [Getting started: Polymarket Pulse]({{ '/getting-started/polymarket-pulse/' | relative_url }}).

### Web app — the same products in a browser

The web app mirrors both Mini Apps in a regular browser. Sign in with Google, email, or Telegram; your plan and settings carry over between Telegram and the web. See [Getting started: Web app]({{ '/getting-started/web-version/' | relative_url }}).

### Chrome extension — a Convicta layer on top of polymarket.com

The extension adds Convicta directly onto Polymarket's own website: a real-time alert sidebar (notification center), news and the Edge estimate on every market page, a "Notify me" price-move button, extra context on trader profile pages, a newspaper view of news for the markets you hold, and coverage dots on market lists showing which markets have tracked news. The extension is built and installable today via developer install; a Chrome Web Store listing is upcoming. See [Getting started: Chrome extension]({{ '/getting-started/chrome-extension/' | relative_url }}).

## Who is Convicta for?

Convicta is not only for Polymarket traders — although traders get the most out of it. Use this matrix to pick your entry point:

| You are... | Start with | Add later |
|---|---|---|
| Following geopolitics or world markets, tired of juggling 50 channels | **Convicta News** — one dense feed or one daily digest | Fine-tune delivery in the [Settings map]({{ '/settings/' | relative_url }}) |
| An active Polymarket trader | **Polymarket Pulse** + the **Chrome extension** on polymarket.com | Convicta News for the underlying news flow |
| Trading on other platforms, using prediction-market prices as a signal | **Polymarket Pulse** (you can browse without a wallet) | Convicta News |
| An analyst or researcher who needs traceable news→market links | **Convicta News** + Pulse's news-trigger alerts | The web app for desktop work |
| Just curious what a market "knows" about a news story | The **Chrome extension** — news and Edge appear right on polymarket.com market pages | Pulse for alerts |

## Why does traceable matching matter?

- **Auditability.** Every news→market match traces to named entities and a named rule. If a story shows up in your feed, you can see the reason.
- **No invented connections.** The live matching decision is made by explicit rules, not by a language model guessing at runtime. Language models are used to *build* the underlying knowledge and to write summaries — never to decide the match.
- **Consistency.** The same input always produces the same output; there is no randomness on the path that decides what you see.

## Where is Convicta right now?

Convicta is in community testing and **free for your first two months** — we are collecting feedback, and some features are not yet working exactly as intended, which is why access is free right now. The AI-assisted surfaces (summaries, translations, and the experimental Edge estimate) are metered and may be limited while we test. News-to-market matching runs on a regular batch cadence: treat the feed as *timely*, not millisecond real-time. See the [Roadmap]({{ '/roadmap/' | relative_url }}) for what we are working on.

**Next steps:** [Getting started]({{ '/getting-started/' | relative_url }}) · [Features]({{ '/features/' | relative_url }}) · [Settings map]({{ '/settings/' | relative_url }}) · [Pricing]({{ '/pricing/' | relative_url }})
