# 🤖 BAKOME Discord Ultimate Assistant v3.0

## The most advanced open‑source Discord bot – 1800+ lines, local AI, Reddit sponsor hunting, live trading data, full moderation, ticket system, 50+ languages, XP levels, and SQLite.

[![MIT license](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Discord](https://img.shields.io/badge/Discord-Bot-5865F2?logo=discord&logoColor=white)](https://discord.com)
[![Reddit](https://img.shields.io/badge/Reddit-Monitor-FF4500?logo=reddit&logoColor=white)](https://reddit.com)
[![Crypto](https://img.shields.io/badge/Crypto-Trading-F7931A?logo=bitcoin&logoColor=white)](https://coingecko.com)

---

## 🚀 Features

| Feature | Description |
|---------|-------------|
| 🧠 **Local AI** | Private, offline AI with Ollama (Llama 3.2) – no cloud, no subscription |
| 🔴 **Reddit Monitor** | Scans r/opensource, r/startups, r/SaaS for sponsors, grants, funding, bounties |
| 💰 **Live Crypto/Forex** | `/crypto BTC`, `/forex EURUSD`, `/news tech` – real‑time market data |
| 🎫 **Ticket System** | `/ticket open` – creates private channel; `/ticket close` – deletes it |
| 🛡️ **Full Moderation** | `!kick`, `!ban`, `!clear`, `!warn`, anti‑spam, SQLite logs |
| 🌍 **50+ Languages** | Auto‑detect & translate – AI answers in the user’s native language |
| ⚡ **XP / Levels** | Every message gives XP; `/profile` shows rank |
| 📊 **SQLite Database** | Persistent memory for chat history, tickets, logs, command stats |
| 🔧 **Modular Cogs** | Easy to extend or disable features |

---

## 📋 Commands

### 🤖 AI
- `/ask <question>` – chat with local AI
- `/clear_memory` – erase your conversation history
- `/languages` – list all 50+ supported languages

### 📈 Trading
- `/crypto <symbol>` – live crypto price (BTC, ETH, etc.)
- `/forex <pair>` – live forex rate (EURUSD=X, etc.)
- `/news <category>` – latest tech or trading headlines

### 🎫 Support
- `/ticket open` – open a private support ticket
- `/ticket close` – close the current ticket

### 🛡️ Moderation (prefix `!`)
- `!kick @user [reason]`
- `!ban @user [reason]`
- `!clear <amount>`
- `!warn @user [reason]`

### 🛠️ Utilities
- `/ping` – bot latency
- `/profile [@user]` – XP and level
- `/stats` – bot statistics
- `/help` – this help message

---

## 🛠️ Installation

### Prerequisites
- Python 3.11+
- A Discord server (with admin rights)
- (Optional) Ollama installed for local AI
- Reddit API credentials (free)

### Steps

```bash
git clone https://github.com/BAKOME-Hub/BAKOME_Discord_Ultimate_Assistant_v3.git
cd BAKOME_Discord_Ultimate_Assistant_v3
pip install -r requirements.txt
