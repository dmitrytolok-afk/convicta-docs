---
title: Features
nav_order: 3
permalink: /features/
---

# Features

Everything below runs on the one deterministic engine described in the [Introduction]({{ '/' | relative_url }}). Features marked **⏳ warming up** are AI-assisted and metered — while we're in community testing they may be limited or paused, while the deterministic features run normally.

## The news feed (Convicta News)

- **Multi-source aggregation.** Convicta watches hundreds of channels plus RSS sources and brings them into one feed.
- **Curated at scale.** Across all sources we curate up to ~500,000 news items a day and filter them down to what matters for you — you get the relevant handful, not the firehose. *(A breadth/throughput figure, not an accuracy claim.)*
- **Deduplication.** Near-identical reposts of the same story are collapsed, so you see the story once instead of dozens of times.
- **Deterministic tagging & filtering.** Each item is tagged by rule and sorted into your chosen categories — no black-box scoring.
- **"Why you got this."** Cards carry context explaining why the item reached you, so the feed stays auditable.
- **World-wires preview.** A curated world-news stream every free user gets automatically, so your feed is never empty.

## Personal words & filters

- **Categories & presets.** Choose the topics you want and start from presets, then refine.
- **Your own sources.** On the paid plan you can add your own sources and import an **OPML** file to bring an existing subscription list with you.

## Alerts

**Convicta News**
- Feed delivery and an optional **daily digest** roundup.

**Polymarket Pulse**
- **Price / threshold alerts** — get pinged when a market crosses a level you set (multiple triggers supported).
- **Market resolution status** — track a market through proposed → disputed → resolved, with the dispute-window countdown.
- **Trader-activity signals** — activity from followed traders and notable wallets, with per-trade context.

> Pulse's free tier includes **2 alerts** and no trader-watch or digests; higher tiers raise those limits. See [Pricing]({{ '/pricing/' | relative_url }}).

## Edge (Pulse) — ⏳ warming up

**Edge** is an AI-assisted fair-value read on a Polymarket market: an estimate you can weigh against the current market price. Three things to know about it:

- **AI-computed.** Edge is an AI-generated fair-value / mispricing estimate — produced by our models, not a hand-set number.
- **Improves over time.** As our models and data get better, Edge gets more accurate. (We're honest that it's improving — we don't publish an accuracy figure.)
- **Not financial advice.** Edge is **not** financial advice. It's an additional metric that may help you make a decision on prediction markets — the decision is always yours.

Because Edge is a metered AI feature, it may be limited or paused while we're in this testing phase. When Edge is paused, the rest of your Pulse signals continue to work.

## Digests

- **Convicta News** offers a configurable **daily digest** (part of the paid plan; free to try during the testing phase).
- **Pulse** offers digests on higher tiers.

> Some digest content is AI-assisted (summaries, translations) and is **⏳ warming up** during community testing. The digest structure and deterministic content are delivered regardless; the AI-written summaries are what may be limited.

## AI summaries & translations — ⏳ warming up

Convicta can summarize and translate news into your language. These are metered AI features and may be limited or paused during community testing. When they're paused, you'll see the original text (often English) rather than a translated summary — the underlying story is still delivered.

## What we deliberately don't claim

- **Not real-time news alerts.** News-to-market matching runs on a batch cadence. It's built to be timely and complete, not millisecond-live.
- **No accuracy percentage — yet.** We lead with *auditability and determinism* because those are properties of the design you can verify today. We don't publish a hit-rate or accuracy figure until it's been measured on a labeled benchmark. When we have one, we'll show the methodology.
