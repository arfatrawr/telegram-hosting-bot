# Render Telegram Bot

## Render settings
- Runtime: Python 3
- Build Command: `pip install -r requirements.txt`
- Start Command: `python bot.py`

## Environment variables
Add these in Render:
- BOT_TOKEN = your NEW Telegram bot token
- OWNER_ID = your Telegram numeric user ID
- ADMIN_ID = your admin numeric user ID

## Important
The current bot.py still contains its existing hard-coded configuration values.
Before deploying, replace the TOKEN/OWNER_ID/ADMIN_ID configuration with environment-variable based values as described above, and NEVER commit a real bot token to GitHub.

The bot creates `inf/` and `upload_bots/` automatically at runtime.
