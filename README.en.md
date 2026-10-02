# 📈 BursaBelajar — Investing & Personal Finance Learning Platform

[🇮🇩 Bahasa Indonesia](README.md) · 🇬🇧 English

An interactive, Indonesian-language investment simulator for learning how to read
markets, manage a portfolio, and understand risk — **without risking real money**.

> ⚠️ For **educational purposes only**. All prices, news, and recommendations are
> simulated and are not financial advice.

## 🖼️ Screenshots

| Global Markets | Portfolio |
|---|---|
| ![Global Markets](screenshots/pasar-global.png) | ![Portfolio](screenshots/portofolio.png) |

| Sector Heatmap | AI Advisor & Screener |
|---|---|
| ![Sector Heatmap](screenshots/heatmap.png) | ![AI Advisor](screenshots/advisor.png) |

## ✨ Features

| Feature | Description |
|---|---|
| 📈 **Global Markets** | Stocks, mutual funds, bonds, gold, and crypto from exchanges worldwide, with a scrolling price ticker |
| 🗺️ **Sector Heatmap** | Global sector performance at a glance |
| 🔍 **Analysis & Orders** | 5-level order book (bid/ask), price alerts, trailing stops, and an order form |
| 🤖 **AI Advisor & Screener** | Multi-indicator screener (momentum, mean-reversion, risk/reward) and per-ticker Q&A |
| 💥 **Stress Testing** | Simulate global macro shocks against your portfolio |
| 💰 **Passive Income & Dividends** | Dividend income projections |
| 🎯 **Financial Goals** | Track your financial targets |
| 🔄 **Recurring Buys (DCA)** | Scheduled dollar-cost-averaging purchases |
| 💼 **Portfolio** | Holdings, transaction history, and performance summary |
| 🏦 **Bank Credit** | Loans, credit score, and new credit applications |
| 📰 **Macro News** | Market news and events that move prices |
| 🧮 **Calculators** | Compound interest (DCA) and currency converter |
| 👤 **Evaluation & Backup** | Fund-manager performance review, JSON export/import, simulator reset |

Also: adjustable simulation speed, dark/light theme, achievement badges, and a live **Leaderboard**.

## ☁️ Accounts & Cloud Save

Progress is saved to the cloud via [Supabase](https://supabase.com), so your
investment history is still there when you sign back in from another device.

## 🚀 Getting Started

No installation or build step required.

1. Download or clone this repo.
2. Open `Bursabelajar_SE.html` in a modern browser.

```bash
git clone https://github.com/<username>/<repo-name>.git
cd <repo-name>
# then open Bursabelajar_SE.html in your browser
```

For free hosting, enable **GitHub Pages** (Settings → Pages → select the `main` branch).

## 🛠️ Tech Stack

- Vanilla HTML, CSS, and JavaScript (single file)
- [Supabase JS v2](https://github.com/supabase/supabase-js) for auth, cloud save, and leaderboard
- Fonts: Bricolage Grotesque & IBM Plex Mono

## 📄 License

Released under the [MIT License](LICENSE).

## ⚠️ Disclaimer

This project is a learning tool. Market data is simulated and results here do
not predict real-market outcomes.
