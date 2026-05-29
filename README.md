# 🐙 Fathom — AI Financial Intelligence Platform

An AI-powered financial intelligence platform for retail investors 
and small funds. Built with Claude AI, Finnhub, and the Guardian API.

## Features
- 9 sector portfolios with 100+ tracked companies
- AI Decision Engine (Buy / Hold / Sell verdicts)
- Live stock prices and sector news
- Clickable portfolio charts with company drill-down
- Ask Fathom — AI financial chat
- IPO Predictor and Fallen IPO Recovery tracker

## Setup
1. Open `index.html` in your browser
2. Click ⚙ API Keys and add:
   - Anthropic API key (console.anthropic.com)
   - Finnhub key (finnhub.io) — free
   - Guardian key (open-platform.theguardian.com) — free

## Tech Stack
- Vanilla HTML/CSS/JS (single file, no build step)
- Claude Sonnet 4 via Anthropic API
- Finnhub for live market data
- Guardian API for financial news
- Chart.js for visualisations
- Deployed on Netlify
