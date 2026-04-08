<div align="center">

<img src="https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/Telegram-Bot-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
<img src="https://img.shields.io/badge/PostgreSQL-Database-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
<img src="https://img.shields.io/badge/FastAPI-Web-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">

# 🎴 Soul Collector Bot

### *Collect · Trade · Dominate*

**The Ultimate Anime Character Collection Experience on Telegram**

[![Add to Telegram](https://img.shields.io/badge/➕_Add_to_Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/+EJLXtbm4Qa4wNzFl)
[![Support Chat](https://img.shields.io/badge/💬_Support_Chat-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/kingchaos7)
[![Support Channel](https://img.shields.io/badge/📢_Support_Channel-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/yourryori)

</div>

---

## ✨ What is Soul Collector?

**Soul Collector** is a feature-rich Telegram bot that brings the thrill of anime character collecting to your groups and DMs. With a sophisticated economy system, weighted rarity drops, weekly leaderboards with real prizes, and a beautiful web store interface — it's the most immersive character collection bot on Telegram.

> 🌸 *"Anime souls drift through the void… Only the worthy may claim them."*

---

## 🚀 Key Features

### 💰 Economy System
| Feature | Description | Cooldown |
|---------|-------------|----------|
| `/daily` | Claim 50-200 coins | 2 hours |
| `/claim` | Claim a random character | 11 hours |
| `/wallet` | View your coin balance & collection count | — |

**Streak Bonuses:**
- 🔥 7-day streak → **+3,000 coins bonus!**
- 🏆 Own all characters → **+10,000 coins reward!**

### 🎴 Collection System
| Feature | Description |
|---------|-------------|
| `/vault` | Browse your collected characters with pagination |
| `/market` | View all available characters |
| `/buy <id>` | Purchase characters (multiple IDs supported) |
| `/sell <id>` | Sell characters for 70% of base price |
| `/search <name>` | Find characters by name or anime |

### 🎭 Drop System (Groups Only)
The heart-pounding drop system where characters appear hourly:

1. **Drop Appears** — A mysterious character image is posted
2. **Guess Fast** — Use `/guess <name>` to identify the character
3. **Win Rewards** — Correct guessers win the character + coins!
4. **Streak Bonus** — 3+ consecutive wins get special recognition

**Rarity Rewards:**
| Rarity | Emoji | Bonus Coins |
|--------|-------|-------------|
| Common | ⚪ | 50 |
| Uncommon | 🟢 | 100 |
| Elite | 🔵 | 200 |
| Epic | 🟣 | 400 |
| Waifu | 💖 | 500 |
| Special Edition | ✨ | 700 |
| Legendary | 🌟 | 1,000 |
| Limited | ⏳ | 1,200 |
| Event | 🎉 | 1,500 |
| Mythic | 🔴 | 2,500 |

### 🏆 Weekly Leaderboard
Every **Sunday at 12:00 UTC**, the bot automatically:
- Posts the global leaderboard to all groups
- Awards prizes to Top 3 collectors:
  - 🥇 1st Place: **3,000 coins**
  - 🥈 2nd Place: **2,000 coins**
  - 🥉 3rd Place: **1,000 coins**
- Sends DM notifications to winners

### 📋 Tasks & Achievements
| Task | Reward |
|------|--------|
| Refer a friend | 1,000 coins |
| Friend joins via referral | 500 coins (for friend) |
| Add bot to group (as admin) | 5,000 coins |
| First purchase | 1,500 coins |
| First guess win | 1,000 coins |
| Collector (10 characters) | 2,500 coins |
| 7-day streak | 3,000 coins |
| Channel subscription tasks | Variable |

### 🌐 Web Store
Beautiful, responsive web interface to browse all characters:
- 🔍 Real-time search by name, anime, or ID
- 🏷️ Filter by anime series
- 📱 Mobile-optimized design
- ✨ Glassmorphism UI with animations

---

## 🛠️ Tech Stack

```
┌─────────────────────────────────────────────────────────┐
│  Python 3.9+  │  python-telegram-bot 20+  │  asyncpg   │
├─────────────────────────────────────────────────────────┤
│  FastAPI      │  Uvicorn                  │  APScheduler│
├─────────────────────────────────────────────────────────┤
│  PostgreSQL   │  Webhook/Polling Support  │  Bilingual │
└─────────────────────────────────────────────────────────┘
```

---

## 📋 Available Commands

### 👤 User Commands
```
/start        - Begin your collection journey
/help         - View all available commands
/lang         - Change language (English/Русский)
/daily        - Claim daily coins
/claim        - Claim a random character
/wallet       - Check your balance
/vault        - View your collection
/market       - Browse the character market
/buy <id>     - Purchase character(s)
/sell <id>    - Sell a character
/search <n>   - Search for characters
```

### 🎮 Drop Commands (Groups)
```
/guess <name>      - Guess the dropped character
/enabledrops       - Enable hourly drops (admin/owner)
/disabledrops      - Disable drops (admin/owner)
```

### 🏆 Social Commands
```
/leaderboard       - View top collectors
/tasks             - View and complete tasks
/refer             - Get your referral link
```

### 👥 Group Admin
```
/listadmins        - List human admins
/calladmins        - Mention all admins (10min cooldown)
```

### 👑 Owner Commands
```
/addcharacter      - Add new character (interactive)
/remove <id>       - Remove character from market
/listchar          - List all characters
/addcoins          - Add coins (reply to user)
/removecoins       - Remove coins (reply to user)
/setstartvid       - Set start video (reply)
/setstartmsg       - Set custom start message
/setwelcomepic     - Set group welcome image
/broadcast         - Broadcast to all users & groups
/stats             - View bot statistics
/groupmembers <id> - View group members
/addtask           - Add channel task
/removetask <id>   - Remove task
/listtasks         - List all tasks
/resetgrpdata      - Reset group data (danger!)
```

---

## 🚀 Deployment Guide

### Prerequisites
- Python 3.9 or higher
- PostgreSQL database
- Telegram Bot Token (from [@BotFather](https://t.me/BotFather))

### Local Development

```bash
# 1. Clone repository
git clone <your-repo-url>
cd soul-collector-bot

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Configure environment
cp .env.example .env
# Edit .env with your values

# 5. Run the bot
python main.py
```

### Environment Variables

```env
# Required
BOT_TOKEN=your_bot_token_here
DATABASE_URL=postgresql://user:pass@host:5432/dbname
OWNER_ID=your_telegram_user_id

# Optional
OWNER_USERNAME=your_username
SUPPORT_LINK=https://t.me/kingchaos7
WEB_STORE_URL=https://your-vercel-app.vercel.app
WEBHOOK_URL=                    # Leave empty for polling
PORT=8000
```

### Render Deployment

1. **Create Web Service** on [Render](https://render.com)
2. **Connect** your GitHub repository
3. **Set Environment Variables** in Render Dashboard
4. **Deploy!**

**Build Command:**
```bash
pip install -r requirements.txt
```

**Start Command:**
```bash
python main.py
```

---

## 📊 Database Schema

```sql
-- Core Tables
groups              -- Group settings & welcome images
users               -- User-group relationships
global_users        -- Coin balances (global)
group_user_data     -- Per-group cooldowns & streaks
characters          -- Character definitions
inventory           -- User collections
started_users       -- Registered users

-- Drop System
drops_active        -- Groups with drops enabled
current_drops       -- Active drop sessions
drop_winners        -- Win streak tracking

-- Tasks & Referrals
tasks               -- Channel join tasks
task_completions    -- Completed tasks
referrals           -- Referral relationships
group_adds          -- Bot add rewards
bonus_tasks         -- Achievement tracking

-- Config
bot_config          -- Start video/message
rarity_ranking      -- Rarity tiers & emojis
user_info           -- User cache for stats
```

---

## 🎨 Web Store Preview

The bot includes a stunning web interface for browsing characters:

```
┌────────────────────────────────────────┐
│     ✨ Anime Character Store           │
│        Collect · Trade · Dominate      │
├────────────────────────────────────────┤
│  🔍 Search by name, anime, or ID...    │
├────────────────────────────────────────┤
│  🌸 All [42]  Naruto [8]  AOT [5]...   │
├────────────────────────────────────────┤
│  ┌────────────────────────────────┐    │
│  │  [Character Image]             │    │
│  │                                │    │
│  │  💖 Mikasa Ackerman            │    │
│  │  🎬 Attack on Titan            │    │
│  │  💎 💖 Waifu  💰 5,000 coins   │    │
│  │  🆔 #0042                      │    │
│  └────────────────────────────────┘    │
├────────────────────────────────────────┤
│     ◀      5 / 42      ▶               │
└────────────────────────────────────────┘
```

---

## 🌍 Localization

Fully bilingual support:
- 🇬🇧 **English**
- 🇷🇺 **Русский**

Users can switch languages anytime with `/lang`

---

## 🔒 Security Features

- ✅ Owner-only commands with ID verification
- ✅ Admin verification for group commands
- ✅ Rate limiting on guesses (10s cooldown)
- ✅ Anti-spam for `/calladmins` (10min cooldown)
- ✅ Safe broadcast with error handling
- ✅ SQL injection protection via parameterized queries

---

## 📈 Performance Optimizations

- ⚡ **Async/await** throughout
- ⚡ **PostgreSQL connection pooling**
- ⚡ **Weighted random selection** via SQL (no full table loads)
- ⚡ **APScheduler** for efficient job scheduling
- ⚡ **Webhook mode** for production (no polling overhead)

---

## 🤝 Support & Community

| Resource | Link |
|----------|------|
| 💬 Support Chat | [@kingchaos7](https://t.me/kingchaos7) |
| 📢 Support Channel | [@yourryori](https://t.me/yourryori) |
| 👤 Contact | [Telegram](https://t.me/+EJLXtbm4Qa4wNzFl) |

---

## 📝 License

This project is licensed under the MIT License.

```
MIT License

Copyright (c) 2024 Soul Collector

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

---

<div align="center">

### ⭐ Star this repo if you find it useful!

**Made with 💜 by the Soul Collector Team**

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/+EJLXtbm4Qa4wNzFl)

</div>
