---
title: Polymarket Pulse
parent: Getting started
nav_order: 2
permalink: /getting-started/polymarket-pulse/
description: >-
  How to set up Polymarket Pulse: start @Convicta_pulse_bot, optionally connect a wallet, and get alerts on trades, whales, prices and resolutions.
---

# How do I set up Polymarket Pulse?

Polymarket Pulse is a Telegram Mini App that delivers prediction-market alerts: trades, whale activity, price moves, market resolutions, and breaking news matched to the specific [Polymarket](https://polymarket.com) markets it moves. Setup: start the bot, pick a language, connect a wallet (or browse without one). This page walks through it.

## Before you start

Pulse personalizes around your **Polymarket wallet** — the markets you hold and the traders you follow. You get the full experience by connecting a Polymarket **0x wallet address**, but you can also browse markets read-only without connecting anything. If you mainly want news rather than market alerts, start with [Convicta News]({{ '/getting-started/convicta-news/' | relative_url }}) instead.

## 1. Start the bot

Open **[@Convicta_pulse_bot](https://t.me/Convicta_pulse_bot)** in Telegram and tap **Start** (or send `/start`). Use the **menu button** to open the Pulse Mini App.

## 2. Pick your language

Choose your language when prompted.

## 3. Connect your Polymarket wallet — or browse first

Pulse asks for your **Polymarket 0x wallet address**. This is a public address: Pulse only reads public data with it, and it never gets access to your funds — no keys, no trades. Once connected, Pulse tailors alerts and the news feed to the markets you hold or follow.

> **Prefer to look around first?** Use the read-only **"Browse Explore without a wallet"** path. You can browse markets, but you will not get a personalized feed or personal alerts.

## 4. Your first alerts

With your wallet connected, Pulse builds your personalized feed and starts alerting. Depending on your plan, alerts include:

- **Price / threshold alerts** — a market crosses a level you set ("Notify me").
- **Whale alerts** — large trades above a size threshold.
- **Trader alerts** — real-time trades by traders you follow.
- **Market resolution status** — proposed → disputed → resolved, with the dispute-window countdown.
- **News triggers** — breaking news matched to your watchlist, positions, followed traders, or chosen topics.
- **Edge** — an experimental AI fair-value estimate on a market (see below).

Every notification module has its own toggle, and each alert has an on/off switch — see the [Settings map]({{ '/settings/' | relative_url }}) for the full list.

**What Edge is:** an AI-computed fair-value estimate for a market — an early, experimental version that improves as our models and data improve. Edge is **not financial advice**; it is one more metric to weigh, and the decision is always yours.

## What is free and what is paid?

The Pulse free tier includes **2 alerts** and the core alert types; paid tiers add unlimited alerts, trader-watch, digests, and (on the top tier) the full Edge. While Convicta is in community testing, every new user starts with a **two-month free grant** on the full-featured tier — access is free right now because we are still collecting feedback. See [Pricing]({{ '/pricing/' | relative_url }}).

## How fast are the alerts?

Price, whale, and trader alerts fire off live market data. **News-to-market matching runs on a batch cadence** — news-derived alerts are timely, not millisecond real-time. We do not advertise real-time news alerts.

Next: [Chrome extension]({{ '/getting-started/chrome-extension/' | relative_url }}) — the same alerts directly on polymarket.com.
