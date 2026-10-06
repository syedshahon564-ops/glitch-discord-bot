# 🤖 GMX High-Security Discord Bot (24/7 Cloud Host Ready)

Autonomous, High-Security, Voice-Streaming & Auto-Role Discord Bot designed for 24/7 cloud deployment on **Render.com**, **Discloud**, **Railway**, or **Koyeb**.

## Features
- **Anti-Nuke Protection**: Instant rollback and bans for unauthorized deletions.
- **Voice HD Streaming**: 192kbps / 48kHz audio streaming with `yt-dlp` and `davey` E2EE.
- **Auto-Role System**: Automatically grants configured roles to new members.
- **Render HTTP Health-Check Server**: Built-in 0.0.0.0:$PORT server ensuring 100% Render Web Service uptime.

## Deployment on Render.com (100% Free)
1. Fork or push this repository to GitHub.
2. Go to [Render Dashboard](https://dashboard.render.com).
3. Click **New +** -> **Web Service**.
4. Select this repository and click **Connect**.
5. Set:
   - **Runtime**: Python 3
   - **Build Command**: `pip install -r requirements.txt`
   - **Start Command**: `python main.py`
   - **Plan**: Free
6. Add Environment Variable:
   - `DISCORD_BOT_TOKEN`: `YOUR_DISCORD_BOT_TOKEN`
   - `PYTHONUNBUFFERED`: `1`
7. Click **Create Web Service**. Done!
