---
title: Chrome extension
parent: Getting started
nav_order: 4
permalink: /getting-started/chrome-extension/
---

# How do I install the Convicta Chrome extension?

The Convicta Pulse Chrome extension adds a Convicta layer directly on top of **polymarket.com**: news and the Edge estimate on every market page, a real-time notification center, trader-profile tools, and coverage indicators on market lists. The extension is built and works today via **developer ("unpacked") install**; a **Chrome Web Store listing is upcoming**. Installing the extension is free.

## What does the extension add to polymarket.com?

- **Market-page widget** — a panel next to the buy box with the latest matched news for that market, the experimental **Edge** fair-value estimate, recent large-trade activity, resolution status, and an "Open in Pulse" link.
- **"Notify me" button** — set a price-move notification for the market you are looking at, without leaving the page.
- **Notification center** — a gold bell in Polymarket's top bar opens a right-hand sidebar with your live Convicta alerts and an unread counter.
- **Newspaper** — a top-bar news icon opens a dropdown of matched news for your positions and the markets on screen.
- **Coverage dots** — a small 📰 marker on market cards in lists shows which markets have tracked news; hovering shows how many stories.
- **Trader pages** — on trader profiles: a "Follow all trades" bar, a following badge, extra stats, the latest trade, and how many Convicta users watch that trader.
- **Tab price flash** — the browser tab title blinks on price moves so you notice activity in a background tab.
- **Popup brief** — the extension's toolbar popup shows your sign-in status, a portfolio brief, and context for the page you are on.

Every one of these surfaces has its own on/off toggle in the extension's Options — see the [Settings map]({{ '/settings/' | relative_url }}#chrome-extension).

## Installing (developer install, current method)

1. Download the extension folder (`.zip`) from the link we share in the Telegram bots or the community channel, and unzip it.
2. Open `chrome://extensions` in Chrome.
3. Turn on **Developer mode** (top-right toggle).
4. Click **"Load unpacked"** and select the unzipped extension folder.
5. Open [polymarket.com](https://polymarket.com) — the Convicta surfaces appear automatically.

When the Chrome Web Store listing goes live, installation becomes one click and updates become automatic; until then, updating means loading a newer folder the same way.

## Do I need an account?

No — the market widget, news, Edge, and coverage dots work anonymously. Signing in (via the notification center's sign-in link) additionally unlocks your personal alerts, portfolio brief, and follow/watchlist actions, tied to the same account as [Polymarket Pulse]({{ '/getting-started/polymarket-pulse/' | relative_url }}).

## Is it safe?

The extension only reads public page context on polymarket.com and talks exclusively to Convicta's own backend. It never touches your funds, never places trades, and never asks for keys. It works alongside — not instead of — Polymarket's own interface.

Next: [Features]({{ '/features/' | relative_url }}) · [Settings map]({{ '/settings/' | relative_url }})
