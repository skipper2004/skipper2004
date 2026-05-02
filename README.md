<h1 align="center">Mukhammad Albikov</h1>
<p align="center"><b>Senior Backend Engineer · Go / Python</b></p>
<p align="center"><i>Highload backend · Distributed systems · Web3 / multi-chain · Automation platforms</i></p>

<p align="center">
  <a href="https://moonsearch.world">moonsearch.world</a> ·
  <a href="https://linkedin.com/in/mukhammad-albikov-dev">LinkedIn</a> ·
  <a href="https://t.me/skipper_a">Telegram</a> ·
  <a href="mailto:muhammadalbikov@gmail.com">Email</a>
</p>

---

Senior backend engineer with 4+ years of production experience in Go and Python.
Highload systems, distributed architecture, Web3 / multi-chain, LLM at production scale.
Microservices, blue-green deployment, end-to-end ownership — from architecture to launch and scaling.
Building and operating commercial products since age 17.
AI-assisted development: planning, architecture, code review.

Currently shipping [moonsearch.world](https://moonsearch.world) — solo-built
multi-marketplace meta-search, ~130k LOC, ~4 months from idea to launch.

## Tech

| | |
|---|---|
| **Languages** | Go · Python · TypeScript |
| **Backend** | FastAPI · Django + DRF · PostgreSQL · MySQL · Redis |
| **Architecture** | Clean Architecture · Microservices · Blue-green CI/CD · Circuit Breaker · Pool Architecture |
| **DevOps** | Docker · Nginx · GitHub Actions · Linux |
| **Network** | TLS fingerprinting · self-hosted MITM HTTPS proxy · browser-equivalent HTTP/2 |
| **Crypto / Web3** | Bitcoin signing in pure Go (secp256k1 · Schnorr BIP-340 · Taproot BIP-341 · PSBT · Bech32m) · Solana (Jito MEV) · EVM 10+ networks · TON liteservers |
| **AI / LLM** | OpenAI in production · Vision LLM · multi-key LLM pooling with rate limiting |

## What I've built

### 🔎 Moon Search — multi-marketplace meta-search
[moonsearch.world](https://moonsearch.world) · Python/FastAPI + React · ~130k LOC · solo · ~4 months

13 marketplaces, 14+ microservices on clean architecture, blue-green deployment
with auto-rollback, parallel LLM-driven search pipeline returning 100+ products in 1–2 minutes.
3 SPAs on a shared backend, 24 security layers, 5 auth methods.

### 🛒 Marketplace operations platform
Python · 08.2024 – present · ~30k LOC

Automation across 5 large e-commerce marketplaces — account lifecycle and order operations workflows across 91,000+ accounts and 27,000+ orders.
Custom TLS Proxy Bridge (self-hosted MITM HTTPS with browser-equivalent fingerprinting),
3-tier LLM product filtering pipeline.

### ⛓️ Cross-chain Transaction Tool
Go · 01.2025 – 10.2025 · ~30k LOC · team of 2

4 blockchains (Bitcoin, Solana, EVM 10+ networks, TON), 45 modules.
Handcrafted Bitcoin signing protocol in pure Go (secp256k1, Schnorr, PSBT, Bech32m — no C bindings).
Reverse-engineered LaunchMyNFT's closed-source Solana Anchor program (no public IDL, no SDK in any language) — extracted method discriminators, account orderings, and 3 distinct on-chain account layouts (one per mint type) from their Next.js JS bundle.

### 🏪 White-label e-commerce
Python/Django + React · 03.2025 – 07.2025 · team lead (2 engineers)

Full-stack platform (auth, catalog, cart, orders, payments, analytics).
Dynamic theming through 371 env variables — full repaint for new tenants without code changes.
Separate mail microservice with exponential retry and per-tenant SMTP credentials.

### ☁️ Cloud exchange arbitrage
Go · 04.2023 – 02.2024

P2P arbitrage system across 3 exchanges, peak ~1,700 RPS.
Reduced latency ~50x (3,000 ms → 60 ms) by co-locating servers in Japan next to exchange nodes.
2,200+ executed orders. Product retired after exchange market exit (force majeure).

### 🏥 Dental clinic website
Python/Django · 08.2023 – 09.2023

Built backend from scratch in 5 days on Django: 3 models, 11 view functions, 11 HTML templates with file caching, auth, CMS via Django Admin. Hybrid Tilda + Django frontend.

### 🤖 Multilingual chat bot — first commercial product
Python · 01.2022 – 12.2022

Desktop product (EN/RU/TR) with conversational bot (1,500,000+ Q&A database, pre-LLM era),
1,000+ automated flows in a commercial community. Client-side architecture offloading
the server with 100+ concurrent users. First $20k earned at 17.

## Open source

[**btc-sign**](https://github.com/skipper2004/btc-sign) — scure-btc-signer for Go. Ergonomic Taproot PSBT signing with raw private keys in one line. Pure Go, single dependency, BIP-340/350 vectors passing, 4.3x faster than btcsuite.

## Education

**HSE University** (Higher School of Economics), Moscow — BSc in Information Security · 09.2022 – present (3rd year).

## Languages

**Russian** — native · **English** — B2

---

<p align="center">
  <sub>Open to remote backend / LLM / Web3 roles — drop a line on Telegram or email.</sub>
</p>
