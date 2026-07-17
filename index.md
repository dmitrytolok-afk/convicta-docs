---
title: Introduction
nav_order: 1
permalink: /
---

# Introduction

**Convicta is a news engine that understands what a headline actually means — and, when it matters, what that means for a market.**

Most alerting tools match on keywords or on a black-box similarity score: you get a ping, but you can't see *why*. Convicta is built the opposite way. At its core is a deterministic matcher that reduces both a news event and a topic (or a prediction market) to explicit relationships — *who did what to whom* — and connects them only when those relationships line up. The result is a feed you can audit: every item can be traced back to the exact entities and the exact rule that put it in front of you.

The ecosystem has two products, built on that one engine:

## Convicta News — your personal, multi-source news feed

**Bot: [@Convicta_news_bot](https://t.me/Convicta_news_bot)**

Convicta News watches hundreds of channels and RSS sources — up to ~500,000 news items a day across all of them — then filters, de-duplicates, and tags everything so you see the story once, in the categories you care about — not fifty near-identical reposts. It is multilingual, works as a Telegram Mini App, and can deliver a daily digest. It's open to everyone: anyone can start it today.

## Polymarket Pulse — news, turned into prediction-market signals

**Bot: [@Convicta_pulse_bot](https://t.me/Convicta_pulse_bot)** *(a community testing version)*

Pulse takes the same engine and points it at [Polymarket](https://polymarket.com). It connects breaking news to the specific markets that news moves, and layers on price alerts, market-resolution status, and trader-activity signals — plus an AI-assisted **Edge** read that estimates a fair value for a market. Pulse is an early community-testing product, built for people who already trade on Polymarket.

Both products are presented together on the web, but they are **two separate Telegram Mini Apps** with their own onboarding. Pick the one that fits — or use both.

## Why deterministic, explainable matching matters

- **Auditability.** Every match traces to named entities and a named rule over open, inspectable data — not a hidden embedding score. If a story shows up in your feed, you can see the reason.
- **No hallucinated matches.** The matching decision is made by explicit rules, not by a language model guessing at runtime. Language models are used only to *build* the underlying knowledge — never to make the live match. That keeps the feed grounded: it won't invent a connection that isn't there.
- **Consistency.** The same input always produces the same output. There is no randomness on the path that decides what you see.

As a point of scale, the matching graph currently spans roughly 1,600 entities, 260+ relationship types, and 1,200+ Polymarket market definitions *(coverage figures as of 2026-07-09; these describe breadth, not an accuracy score)*.

## An honest note on where we are

Convicta is a community testing version, and it's **free for your first two months** — we're actively collecting feedback, and some features aren't yet working exactly as intended, which is why access is free right now. The ones still warming up are the AI-assisted surfaces — news summaries, translations, and the market **Edge** read — which are metered and may be limited or paused while we test. We flag these throughout the docs so you always know what's live and what's coming. News matching runs on a regular batch cadence, so treat the feed as *timely*, not millisecond real-time.

Ready to start? Head to [Getting started]({{ '/getting-started/' | relative_url }}).
