---
title: Settings map
nav_order: 4
permalink: /settings/
---

# Settings map — every Convicta setting, by product

This page is the complete map of user-facing settings across the Convicta ecosystem: what each setting does, what turning it **off** means, and where it lives. Settings are grouped by product — [Convicta News](#convicta-news), [Polymarket Pulse](#polymarket-pulse), and the [Chrome extension](#chrome-extension). Changes apply within a few minutes of saving.

## Convicta News

All Convicta News settings live in the **Mini App hub** (open [@Convicta_news_bot](https://t.me/Convicta_news_bot) → menu button → Configuration), with quick toggles also available via bot commands under posts.

### Categories, sources, and groups

| Setting | What it does | What "off" / removal means |
|---|---|---|
| **Categories** | Choose the topics your feed covers (start from presets, then refine). | An unselected category never reaches you. |
| **Sources** | Enable or disable individual sources inside your categories; on News+ add your own sources and import an **OPML** list. | A disabled source is skipped for you even if its category is on. |
| **RSS groups** | Wire/RSS sources are organized in groups (world, regional, economics, sport, tech...). Each group has its own delivery mode (below). | Removing a group removes its stories from your feed. |

### Translation

The **translate** toggle controls every translation path — the feed, summaries, and digests. It works as a hierarchy; the most specific setting wins:

1. **Global** — translate everything into your language, or nothing.
2. **Per category** — override the global choice for one category.
3. **Per source** — override again for a single source.

**Off = original language.** With translate off, stories, summaries, and digests are delivered in the language the source published in. (Russian↔Ukrainian is never machine-translated.) Translation is AI-assisted and metered during community testing.

### Reading and delivery

| Setting | What it does | What "off" means | Default |
|---|---|---|---|
| **Summarize** | AI compresses each post to a short summary. | Off = **smart clip**: the original text is trimmed instead of summarized — you get the raw excerpt, no AI. | **On** |
| **Preview** | Link/image previews under posts. | Off = text-only posts. | On |
| **Post buttons** | Action buttons under each post (snooze, "why", thread). | Off = clean posts without buttons. | On |
| **Quiet hours** | Pauses delivery overnight (default 23:00–08:00, your timezone). Queued items are delivered in the morning in batches. | Off = delivery around the clock. Breaking-news flashes bypass quiet hours. | On |
| **Snooze** | Pause one source or one category for 24 hours or a week — from the 💤 button under a post or from Configuration. | No snooze = everything flows continuously. | — |
| **Collapse repeats** | The first post of a story stays; later duplicates are not sent — instead a "+N sources" line grows under the original. | Off = each new confirming source may arrive as its own post (deduplication still applies). | Off (opt-in) |
| **Breaking flashes** | 🚨 flash when a story is confirmed by several independent sources. Threshold adjustable (2–10 sources) and can be toggled per category. Flashes bypass quiet hours and digest mode. | Off = no flashes; the story still arrives through the normal feed. | On |
| **Mute / highlight words** | Personal word lists per category: mute-words suppress matching posts, highlight-words force them through. | Empty lists = category rules alone decide. | — |

### Feed pacing (RSS modes) and digest

| Setting | What it does | Notes |
|---|---|---|
| **Per-group delivery mode** | For each RSS group choose **instant** (each story as its own post) or a batched summary every **1h / 2h / 3h / 4h**. | Batched groups arrive as compact grouped roundups (up to ~12 items per message). |
| **Daily digest** | A once-a-day roundup of your topics instead of (or alongside) the running stream. | Part of News+; free to try during the testing period. Digest summaries are AI-assisted. |

## Polymarket Pulse

Pulse settings live in the **Pulse Mini App** ([@Convicta_pulse_bot](https://t.me/Convicta_pulse_bot) → menu button → notification settings). The model is two layers: **modules** (master switches per notification type, each with scope and frequency) and **per-alert switches** (each alert you create has its own on/off). A real-time alert fires only if its own switch is on **and** its module is not switched off.

### Notification modules

| Module | What it does | What "off" means | Default |
|---|---|---|---|
| **Market move** ⚡ | Notifies on significant price changes in markets in scope (checked every ~30 min). | No move notifications. Your explicit "Notify me" price alerts are **not** affected — they always work while switched on. | On |
| **Top movers** 🔥 | Daily list of the biggest movers. | No movers digest. | On |
| **Whales** 🐋 | Real-time alerts on large trades above a dollar threshold. | Whale alerts stop, including per-market ones you created. | On |
| **Trader alerts** 📡 | Real-time trades by traders you follow. *(paid tier)* | All followed-trader realtime alerts stop. | On (when available) |
| **Trader daily** 👤 | Daily digest of your followed traders' activity. | No trader digest. | On |
| **News triggers** 📰 | Breaking news matched to your markets (see sub-toggles below). *(paid tier)* | The personal news line stops entirely — Telegram delivery and its mirror in the web feed. | On (when available) |
| **New markets** 🆕 | Newly listed markets in your scope. | No new-market notices. | On |
| **Category digest** 🗂 | Daily digest per chosen category. | No category digest. | On |
| **Weekly recap** 📅 | Weekly summary. | No weekly recap. | On |
| **Portfolio** 💼 | Daily portfolio summary for your connected wallet — managed from the "My portfolio" hub rather than the module list. | No portfolio summary. | On |

Each module also carries a **scope** selector (watchlist / categories / all markets, where applicable) and a **frequency** selector (realtime / 30m / daily..., where applicable).

### News-trigger sub-toggles

Inside the **News triggers** module, independent switches choose *what gets matched*:

| Sub-toggle | Matches news to... | Default |
|---|---|---|
| ⭐ Watchlist markets | Markets you starred. | On |
| 📍 My positions | Markets where you hold a position. | On |
| 🐳 Traders' markets | Markets your followed traders are active in. | On |
| 🗂 Topic markets | Markets in your chosen categories. | On |
| 🔭 Discover | Relevant markets from the whole Polymarket universe, beyond your lists. | Off |
| 📈 Market analysis | Analyst interpretations and commentary, not only factual events. | Off |
| 🌍 Foreign-language sources | News from non-English sources (normalized/translated); regional sources are often first on their own topics. | On |
| 🏛 State-media sources | Include state/propaganda-linked outlets as signal sources (never counted as independent confirmation). | On |

### Alert-level settings

| Setting | What it does | Where |
|---|---|---|
| **Per-alert on/off** | Every alert you create (price threshold, whale watch, trader follow...) has its own switch. | The alert's card in the Mini App. |
| **Notify on move ("Notify me")** | An explicit price-move alert on a specific market. Deliberately independent of the Market-move module — if you asked for it, it fires. | Market page in the Mini App, web app, or the [extension]({{ '/getting-started/chrome-extension/' | relative_url }}). |
| **Sensitivity presets** | *Loose* (≥1 pp move, whales ≥$5k), *Balanced* (≥5 pp, ≥$10k), *Strict* (≥8 pp, ≥$50k). Adjusting thresholds manually switches you to *Custom*. | Notification settings. Default: **Balanced**. |

## Chrome extension

Extension settings live on its **Options page**: `chrome://extensions` → Convicta Pulse → **Details** → **Extension options**. Every toggle applies live — no reload needed. **All toggles default to on**, except "below the buy box" placement.

### Market widget

| Toggle | What it does | What "off" means |
|---|---|---|
| **Show in-page widget** | The Convicta panel (news + Edge + activity) on market pages. | No widget at all on market pages. |
| **Place widget below the buy box** | Moves the widget under Polymarket's order box. | Off (default) = widget sits above/beside the order box. |
| **Show Edge estimate** | The experimental AI fair-value badge in the widget. | Widget shows news/activity without Edge. |
| **Show "Notify me" button** | The in-page button that creates a price-move alert. | Set alerts from the Mini App or web app instead. |

### Trader pages

| Toggle | What it does | What "off" means |
|---|---|---|
| **Follow bar & "Following" badge** | The "Follow all trades" bar and badge on trader profiles. | Follow traders from Pulse instead. |
| **Last trade line** | The trader's most recent trade, inline on the profile. | Hidden. |
| **"Watched by N" line** | How many Convicta users watch this trader. | Hidden. |

### Market page extras

| Toggle | What it does | What "off" means |
|---|---|---|
| **New user trade (24h) line** | Recent notable trade activity for the market. | Hidden. |
| **Per-leg Edge chips** | Small Edge estimates next to each outcome's price. | Only the widget-level Edge (if on). |

### Global surfaces

| Toggle | What it does | What "off" means |
|---|---|---|
| **Coverage dots on market lists** | 📰 markers on market cards that have tracked news. | Plain Polymarket lists. |
| **Topbar news icon (newspaper)** | The 📰 button opening news for your positions and on-screen markets. | No newspaper dropdown. |
| **Portfolio brief in popup** | Portfolio summary in the extension's toolbar popup. | Popup shows only page context. |
| **Right-click "Follow" on 0x addresses** | Context-menu action to follow any wallet address you select. | No context-menu entry. |
| **Watchlist toast on market pages** | A small confirmation toast for watchlist actions. | Silent watchlist actions. |
| **Notification center (gold bell)** | The live alert sidebar in Polymarket's top bar. | Alerts arrive only in Telegram / web. |
| **Tab price flash** | Blinks the browser tab title on price moves. | Static tab title. |

---

Related: [Features]({{ '/features/' | relative_url }}) · [Pricing]({{ '/pricing/' | relative_url }}) (which settings need which plan) · [Getting started]({{ '/getting-started/' | relative_url }})
