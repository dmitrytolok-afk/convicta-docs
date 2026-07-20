---
title: Features
nav_order: 3
permalink: /features/
---

# What can Convicta do?

This page details the features of each product in the Convicta ecosystem — Convicta News, Polymarket Pulse, the web app, and the Chrome extension — and explains how they connect. Everything runs on one engine: a rule-based news→market matching graph where every match is traceable to the rule that produced it. Features marked **⏳ warming up** are AI-assisted and metered; during community testing they may be limited, while the rule-based features run normally.

## How does the shared engine work?

One pipeline feeds all four surfaces:

1. **Ingest.** 1,600+ news sources in 20 languages — Telegram channels, RSS/wire feeds, and more — flow into one stream.
2. **Understand.** Each story is de-duplicated, tagged, and reduced to explicit relationships (*who did what to whom*). AI summaries compress it to the point (⏳).
3. **Match.** The story's relationships are checked against a graph of topics and Polymarket market definitions. A match happens only when the relationships line up under an explicit rule — **every match is traceable back to that rule**, not to a hidden similarity score.
4. **Deliver.** The result reaches you wherever you are: the News feed, a Pulse alert, a digest, the web app, or the extension's surfaces on polymarket.com.

That is why the products feel consistent: a story that appears in your News feed, triggers a Pulse alert, and shows up in the extension's market widget is the *same* story, matched by the *same* rule.

## Convicta News features

- **Multi-source aggregation.** 1,600+ sources in 20 languages, brought into one feed — Telegram channels plus RSS and wire feeds.
- **Deduplication.** Near-identical reposts collapse into one story, so you see it once instead of dozens of times.
- **Rule-based tagging and filtering.** Each item is tagged and sorted into your chosen categories — no black-box scoring.
- **AI summaries** (⏳). Each item is compressed to a short summary instead of a raw clipped excerpt; summaries are on by default.
- **Translation** (⏳). News delivered in your language, controllable globally, per category, and per source.
- **"Why you got this."** Cards carry context explaining why the item reached you.
- **Breaking-news flashes.** When enough independent sources confirm the same event, you get a flash even during quiet hours.
- **Daily digest.** A configurable once-a-day roundup instead of (or alongside) the running stream.
- **Delivery control.** Quiet hours, per-source and per-category snooze, collapse of repeats, per-group delivery frequency (instant or batched every 1–4 hours), personal mute/highlight words. Full list: [Settings map]({{ '/settings/' | relative_url }}#convicta-news).
- **Your own sources.** On the paid plan, add your own sources and import an **OPML** file.
- **World-wires preview.** A curated world-news stream every free user gets automatically.

## Polymarket Pulse features

**Alerts** — each type has its own module toggle and per-alert switches ([Settings map]({{ '/settings/' | relative_url }}#polymarket-pulse)):

- **Price / threshold alerts ("Notify me")** — a market crosses a level you set; multiple triggers per market.
- **Market-move and top-movers alerts** — significant price changes across markets you follow, with sensitivity presets (loose / balanced / strict).
- **Whale alerts** — large trades above a configurable dollar threshold.
- **Trader alerts** — real-time trades by traders you follow, plus a daily trader digest.
- **Market resolution tracking** — proposed → disputed → resolved, with the dispute-window countdown.
- **News triggers** — breaking news matched to markets in your watchlist, your open positions, your followed traders' markets, or your chosen topics; optional Discover mode surfaces relevant markets from the whole Polymarket universe.
- **Digests** — category digests, weekly recaps, and a portfolio summary.

**Portfolio and traders:**

- **Portfolio tracking** — positions and value for your connected wallet, with a daily portfolio module.
- **Trader-watch** — follow specific traders/wallets and see their activity with per-trade context.

**Edge** (⏳ experimental):

- **Edge** is an AI-computed fair-value estimate for a market — a number to weigh against the current price. It is an early, experimental version that improves as our models and data improve. Edge is **not financial advice**; the decision is always yours.

## Web app features

The web app mirrors both Mini Apps in a browser: the news feed, market browsing, portfolio, and all settings. Sign in with Google, email, or Telegram; the same plan applies everywhere. Alerts and digests are still delivered in Telegram — the web is the reading-and-managing surface. See [Getting started: Web app]({{ '/getting-started/web-version/' | relative_url }}).

## Chrome extension features

The extension puts the same engine's output directly on **polymarket.com**:

- **Market-page widget** — matched news, the Edge estimate, recent large trades, and resolution status for the market you are viewing, plus per-outcome Edge chips and a Watch button.
- **"Notify me" on the page** — set a price-move alert without leaving polymarket.com.
- **Notification center** — a gold bell in the top bar opens a live sidebar of your Convicta alerts.
- **Newspaper** — a top-bar dropdown of news for your positions and the markets on screen.
- **Coverage dots** — 📰 markers on market lists showing which markets have tracked news.
- **Trader-page tools** — follow bar, latest trade, extra stats, and watcher counts on trader profiles.
- **Tab price flash** — the tab title blinks on price moves.

Anonymous by default; signing in unlocks the personal surfaces. Install guide: [Getting started: Chrome extension]({{ '/getting-started/chrome-extension/' | relative_url }}). Every surface has a toggle: [Settings map]({{ '/settings/' | relative_url }}#chrome-extension).

## What does Convicta deliberately not claim?

- **Not real-time news alerts.** News-to-market matching runs on a batch cadence — timely and complete, not millisecond-live. (Price, whale, and trader alerts do run off live market data.)
- **No accuracy percentage.** We lead with auditability and traceability — properties you can verify — and do not publish a hit-rate or accuracy figure until it has been measured on a labeled benchmark.
- **No trading execution.** Convicta informs decisions; it does not place trades. Automated execution is in development and not available — see the [Roadmap]({{ '/roadmap/' | relative_url }}).
