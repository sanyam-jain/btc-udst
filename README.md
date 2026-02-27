# 📈 BTC / USDT Live Price Chart

A real-time cryptocurrency price chart displaying **Bitcoin (BTC) against USDT** using live market data from Binance.

This project demonstrates how to build a responsive, real-time trading chart using WebSockets and lightweight charting libraries.

---

## 🚀 Features

- 📊 Live BTC/USDT price updates
- 🕒 Real-time candlestick chart
- ⚡ WebSocket-based streaming data
- 📱 Fully responsive design
- 🔄 Auto-refreshing without page reload
- 🌙 Dark theme trading interface

---

## 🛠 Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Binance WebSocket API
- TradingView Lightweight Charts

---

## 📡 Data Source

Market data is streamed directly from:

Binance Public WebSocket API  
No backend server required.

---

## 📂 Initial Codex Prompt

Create a complete production-ready web project named:

BTC / USDT Live Price Chart

Requirements:

1. Build a real-time Bitcoin (BTC/USDT) price chart.
2. Use Binance Public WebSocket API for live streaming data.
3. Use TradingView Lightweight Charts library for candlestick visualization.
4. No backend — frontend only.
5. Use only:
   - HTML
   - CSS
   - Vanilla JavaScript

Project Structure:

btc-usdt-live-chart/
│
├── index.html
├── style.css
├── script.js
└── README.md

----------------------------------
Functional Requirements:
----------------------------------

• Display real-time candlestick chart (1-minute interval)
• Auto-update chart without page refresh
• Dark theme trading interface
• Responsive design (desktop + mobile)
• Show current BTC price above chart
• Display live price updating in real-time
• Show connection status (Connected / Reconnecting)

----------------------------------
Technical Details:
----------------------------------

Use Binance WebSocket stream:

wss://stream.binance.com:9443/ws/btcusdt@kline_1m

Parse incoming kline data and update candlestick chart in real time.

Use TradingView Lightweight Charts via CDN.

Implement:

- WebSocket reconnect logic if connection drops
- Proper candlestick mapping:
    open
    high
    low
    close
    time (convert to UNIX timestamp seconds)

Use clean, modular, readable JavaScript.

----------------------------------
UI Design Requirements:
----------------------------------

• Dark background (#0d1117 or similar)
• Centered chart container
• Professional trading dashboard style
• Smooth typography
• Subtle glow or accent for price

----------------------------------
README.md Requirements:
----------------------------------

Include:
- Project description
- Features
- Tech stack
- How to run locally
- Disclaimer
- MIT license mention

----------------------------------
Code Quality:
----------------------------------

• No unnecessary libraries
• Clean comments
• Production-ready formatting
• No console errors
• Modern ES6 syntax

Generate complete working code for all files.

Add:

• Ability to switch timeframes (1m, 5m, 15m)
• Toggle between Candlestick and Line chart
• Show volume bars below price chart
• Add smooth loading animation
• Optimize performance for continuous streaming

This chart will later integrate into a crypto trading bot dashboard.
Structure the code to allow future API integration.
