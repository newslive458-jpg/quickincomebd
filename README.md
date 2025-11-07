# Smart Earn Bot + EarnQuick MiniApp

## Overview
Telegram bot + MiniApp to earn points by watching ads. Built with Flask + aiogram + SQLite.

## Setup (local)
1. Copy .env.example -> .env and fill values (BOT_TOKEN, ADMIN_ID, WEBAPP_URL, MONETAG_ZONE_ID)
2. pip install -r requirements.txt
3. python main.py
4. Open your bot on Telegram -> /start -> Click "Open EarnQuick"

## Deploy (Render)
- Create a new Web Service on Render, connect GitHub repo
- Start Command: `python main.py`
- Add environment variables in Render: BOT_TOKEN, ADMIN_ID, WEBAPP_URL, MONETAG_ZONE_ID, MIN_WITHDRAW
- Deploy

## Notes
- Keep BOT_TOKEN and other secrets private.
- Consider using a managed DB (Postgres) in production. # quickincomebd
