---
title: Privacy Policy
nav_order: 8
permalink: /privacy-policy/
description: >-
  Convicta Privacy Policy (testing/evaluation phase): what data the Service collects, how it is used, and how to delete it. Provider: Adoriasoft LLC.
---

# Privacy Policy

> This Privacy Policy applies while the Service is in a **testing/evaluation phase**. It may be updated as the Service evolves; the "Last updated" date below always reflects the current version. Questions: contact us (Section 2).

**Last updated:** 2026-07-17 (testing/evaluation phase)
**Applies to:** the Convicta News Telegram bot/Mini App, the Pulse Telegram Mini App, and their web versions (together, the "Service").
**Provider:** Adoriasoft LLC ("we", "us", "our").

---

## 1. About this policy and the current phase

The Service is currently in a **testing/evaluation phase**. It is early-stage software offered to users while we test and improve it. This policy explains what personal data we collect, why, who we share it with, how long we keep it, and the rights you have. We have written it in plain language and tried to describe our real data practices honestly. Because the product is evolving, this policy may change (see Section 11).

We are a small team. We do not sell your personal data, and we do not use it for advertising profiling.

## 2. Who we are and how to contact us

- **Data controller:** Adoriasoft LLC (United States). Registered address available on request and to be published on our website.
- **Contact for privacy questions and to exercise your rights:** through the in-app feedback option — send `/feedback` in `@Convicta_news_bot` or `@Convicta_pulse_bot`. A dedicated privacy email will be published when our website launches.
- **Data Protection Officer:** not appointed — a DPO is not legally required at our current scale. You can reach us using the contact options above.

## 3. What personal data we collect

We collect only what we need to run the Service. What we hold depends on which parts you use and how you sign in.

### 3.1 Account and identity

Depending on your sign-in method, we store one or more of the following:

- **Telegram sign-in:** your Telegram user ID, your Telegram username (@handle) if you have one, and your Telegram language code. We receive these from Telegram's verified sign-in data. (We do **not** receive or store your Telegram phone number or contacts.)
- **Email sign-in:** your email address. Login codes we send you are stored only as a temporary, hashed value in memory to verify the code — we do not keep your login codes in our database.
- **Google sign-in:** the unique account identifier ("subject") from your verified Google token, your display name, and your locale.
- **Apple sign-in:** the unique account identifier ("subject") from your verified Apple token only.
- **UI language** and **referral information** (the account that invited you, if you arrived via a referral link).

**Linking your sign-in methods.** If you sign in with more than one method, we link them to a single account so you keep one profile and one subscription. To support this, we may store a human-readable label for each linked login (for example, your email address or your Telegram @handle) so you can recognise them on the "linked logins" screen.

### 3.2 Pulse (prediction-market companion)

If you use Pulse, we additionally store:

- **Your Polymarket wallet address** — the public on-chain proxy-wallet address you provide during onboarding. This is a public blockchain address, not a private key. **We never ask for, receive, or store your private keys, seed phrase, or any credentials that could move your funds.**
- **Portfolio and P&L information derived from public data.** Using the wallet address you provide, we read **publicly available** Polymarket and on-chain data (your positions, trade history, portfolio value, and profit/loss) and cache it to show you your dashboard and to power alerts. This is public market data associated with a public address — we obtain it by reading, not by connecting to your account.
- **Your watchlist** of markets.
- **Alert and notification preferences** (for example, quiet hours, minimum price move, whale-size thresholds, and per-alert filters).
- **Traders you choose to follow** — the public wallet addresses of other traders you add, and public snapshots of their positions.

### 3.3 Convicta News

If you use Convicta News, we store:

- **Your news preferences** — selected categories/groups, included and excluded sources, personal keyword follows/stops, imported personal feeds, connected channels, timezone, quiet hours, and delivery/format toggles.
- **Delivery statistics** — a per-day, per-source count of how many items we delivered to you (used to manage volume and improve delivery).
- **A short-lived "already shown" ledger** — which stories we have recently shown you, so we don't repeat them.
- **Referral attribution** — the account that referred you and how many people you have referred.

### 3.4 Notifications

If you enable push notifications, we store the technical tokens needed to deliver them:

- **Mobile push tokens** (Expo push tokens) for the mobile app, and/or
- **Web-push subscription details** (the browser push endpoint and its associated keys) for the web version.

### 3.5 Payments and subscriptions

- **Crypto payments (CryptoPay / @CryptoBot):** when you pay with crypto, we store only the identifier of the pending invoice and your resulting subscription window (for example, "paid until" date). We do **not** receive or store your card details, crypto wallet used to pay, or transaction amounts — those are handled by the payment processor.
- **In-app purchases (Apple App Store / Google Play), where offered:** we store the store transaction identifier, product id, status, expiry, and the raw store confirmation as an audit record. Card/payment details stay with Apple/Google.

### 3.6 Technical data

Like any online service, our servers automatically process basic technical data needed to operate and secure the Service (for example, connection metadata and error logs). We keep this to what is needed for operation, security, and debugging.

We do **not** knowingly collect special-category data (health, biometrics, political opinions, etc.), and we ask you not to submit it.

## 4. Why we use your data and our legal bases (GDPR)

For users in the EU/EEA and UK, we rely on the following legal bases under the GDPR:

| Purpose | Data used | Legal basis |
|---|---|---|
| Create and run your account; deliver the core Service you asked for | Identity, preferences, wallet address, watchlist | Performance of a contract (Art. 6(1)(b)) |
| Send the alerts/notifications you turn on | Push tokens, alert preferences | Contract / your consent where required (Art. 6(1)(a)/(b)) |
| Process payments and manage subscriptions | Payment/subscription records | Performance of a contract (Art. 6(1)(b)) |
| Keep the Service secure, prevent abuse, debug | Technical data, delivery stats | Legitimate interests (Art. 6(1)(f)) |
| Improve delivery and the product during the testing phase | Delivery/usage stats, preferences | Legitimate interests (Art. 6(1)(f)) |
| Referral features | Referral attribution | Legitimate interests / contract |

Where we rely on consent (for example, push notifications on some platforms), you can withdraw it at any time. Where we rely on legitimate interests, you can object (see Section 8).

## 5. Who we share data with (third parties and sub-processors)

We share data only as needed to run the Service. Our main recipients are:

- **Telegram** — to authenticate you and deliver messages/Mini Apps. Your use of Telegram is also governed by Telegram's own privacy policy.
- **Polymarket** — for Pulse, we send your **public** wallet address to Polymarket's public data endpoints to read public market and position data. We do not share your identity or other personal data with Polymarket.
- **Google / Apple** — if you use Google or Apple sign-in, to verify your login token.
- **CryptoPay (@CryptoBot)** — to create and check payment invoices when you pay with crypto.
- **Apple App Store / Google Play** — where in-app purchases are offered, to process and validate purchases.
- **Anthropic (AI provider)** — Convicta News uses an AI model to translate and summarise **news content**. Based on our review of the code, we send the model **news article text and public source context only — not your identity, account, email, wallet, or preferences.** The AI provider processes news content, not your personal profile.
- **Infrastructure providers** — we host the Service with a third-party cloud hosting provider and use a content-delivery/tunnelling provider to serve traffic. These providers process data on our behalf under their terms.

*We are finalising the exact list, legal names, and locations of all sub-processors, together with the appropriate data-processing agreements and international-transfer safeguards; this section will be updated accordingly.*

We may also disclose data if required by law or to protect our rights, users, or the security of the Service.

## 6. International transfers

We are based in the United States, and some of the providers above may process data outside your country, including outside the EU/EEA. Where that happens for EU/EEA/UK users, we rely on an appropriate transfer mechanism (such as Standard Contractual Clauses). Provider locations and transfer safeguards are being finalised and this section will be updated accordingly.

## 7. How long we keep your data (retention)

- **Account, identity, preferences, wallet address, watchlist, subscriptions:** kept while your account is active, and deleted or anonymised on account deletion (subject to any records we must keep for legal/accounting reasons).
- **News delivery statistics:** automatically deleted after **about 30 days**.
- **"Already shown" story ledger:** kept only for a short rolling window (a matter of hours) and then deleted.
- **Derived Pulse portfolio/position data:** a cache refreshed from public sources; not a long-term record of your finances.
- **Payment/subscription records:** kept as needed to provide the subscription and to meet legal/accounting obligations.
- **Technical/error logs:** kept for a limited period for security and debugging.

## 8. Your rights

Depending on where you live (and in particular under the GDPR for EU/EEA/UK users), you have the right to:

- **Access** the personal data we hold about you;
- **Rectify** inaccurate data;
- **Erase** your data ("right to be forgotten");
- **Export** your data (portability);
- **Restrict** or **object** to certain processing;
- **Withdraw consent** where we rely on it;
- **Complain** to your local data protection authority.

**How to exercise your rights.** Contact us through the in-app feedback option (`/feedback` in `@Convicta_news_bot` or `@Convicta_pulse_bot`). We will respond within the timeframe required by applicable law (under the GDPR, normally within one month). You can also delete much of your data directly by removing your account/preferences in-app; contact us if you want a full deletion or export.

## 9. Children

The Service is not directed to children. You must be at least **18** years old to use it. We do not knowingly collect data from children below that age. If you believe a child has provided us data, contact us and we will delete it.

## 10. Security

We take reasonable technical and organisational measures to protect your data — for example, sign-in data is cryptographically verified, access to administrative functions is restricted, and payment card data never touches our servers. No system is perfectly secure, and because the Service is in a testing/evaluation phase you should not treat it as a system of record for critical data.

## 11. Changes to this policy

We may update this policy as the Service evolves or as the law requires. We will post the updated version with a new "Last updated" date and, for material changes, provide a more prominent notice in-app.

## 12. Contact

Adoriasoft LLC — in-app feedback (`/feedback` in `@Convicta_news_bot` or `@Convicta_pulse_bot`). A dedicated privacy email will be published when our website launches.
