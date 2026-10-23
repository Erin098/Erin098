# Hi, I'm Erin 👋

Founder-engineer. I design, build, ship, and operate products end-to-end — most recently **LumoRead**, a live App Store app I built solo: product, code, cloud infrastructure, content pipeline, and store operations.

📫 erin@lumoread.app · 🌐 [lumoread.sableus.com](https://lumoread.sableus.com)

---

## 🌙 LumoRead — AI Bilingual Reading

[**► Download on the App Store**](https://apps.apple.com/app/id6789734471) · *live on iOS, 10 languages*

World classics and original titles, rewritten at the reader's own level. Built for readers whose level and book don't match — the kid reading years ahead, the adult meeting a hard classic, anyone learning a new language.

**What's inside (all built solo):**

- 📚 **Adaptive content engine** — every book hand-crafted at 4 reading levels in English and Traditional Chinese, with verified pinyin, keywords, and comprehension quizzes; AI-translated reading in 7 more languages with a shared translation cache
- 🤖 **AI Adapter** — readers paste any text and get it rewritten at their level (LLM-backed, with per-user metering and a global cost circuit-breaker)
- 🔔 **Full engagement stack** — daily reminders, lapse win-back, monthly reading recaps, new-book push to every device, forced-update gating, in-app inbox — plus email campaigns (SES, one-click unsubscribe) and a referral program (both sides earn a free Premium month)
- 🎮 **Gamified retention** — streaks with freeze/make-up/repair mechanics, feathers economy, collectible companions, a Story Passport of stamps
- 💳 **Monetization** — RevenueCat subscriptions (Premium / Family), App Store offer codes, promo entitlements

**How it's built:**

| Layer | Stack |
|---|---|
| App | React Native / Expo (expo-router), TypeScript, i18n ×10 languages |
| Also fluent in | C/C++ (systems & test tooling), Python, Node.js, SQL |
| Backend | AWS CDK — Lambda, Aurora Serverless v2 (Data API), API Gateway, DynamoDB metering, SES, Cognito |
| Content delivery | S3 + CloudFront CDN — new books reach live users with zero app releases |
| Release ops | EAS Build + OTA updates, App Store Connect API automation, Sentry monitoring with failure sentinels |
| Growth tooling | Expo push broadcasting, raw-MIME SES campaigns, screenshot-generation pipeline for 10-locale store listings |

> The source is private — it's a live commercial product with a hand-authored catalog — but I'm glad to do a full code walkthrough in an interview, or grant read access on request.

---

## What I'm good at

- **Shipping the whole thing** — from CDK infrastructure to pixel-level UI to App Store review notes, as one person, fast
- **Root-causing hard bugs** — the kind that hide behind three layers of silent failure (ask me about the notification pipeline that failed silently across an SDK upgrade, an OTA channel misconfiguration, and a persisted-settings migration — and how I instrumented it so it can never hide again)
- **Cost-conscious cloud** — serverless-first, metered AI endpoints, a whole production backend that runs on pocket change until users justify more
- **Multilingual product thinking** — 10 UI languages shipped and maintained as a first-class feature, not an afterthought
- **Systems-level roots** — years of C/C++ before the web stack, including building test tooling in C for large-scale software validation; comfortable all the way from memory layout to React Native

## 🇹🇼 中文簡介

LumoRead 創辦人,一人完成產品、前後端、雲端架構、內容管線與 App Store 營運。
產品已上架 iOS,支援十種介面語言;中英雙語分級閱讀,為「程度與書本不匹配」的讀者而生。
歡迎交流:erin@lumoread.app

---

*This README covers the shipped product. Resume and references available on request.*
