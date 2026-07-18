# Minecraft AFK Bot (Aternos 24/7)

A Node.js bot that connects to an Aternos Minecraft server via [Mineflayer](https://github.com/PrismarineJS/mineflayer) to keep it online 24/7. Includes an Express web dashboard for status monitoring.

## Stack
- **Runtime**: Node.js
- **Bot**: mineflayer + mineflayer-pathfinder
- **Web server**: Express (status dashboard on port 5000)
- **Config**: `settings.json`

## Configuration
All bot settings are in `settings.json`:
- `server.ip` / `server.port` — your Aternos server address
- `bot-account.username` — bot's Minecraft username (offline mode by default)
- `utils.auto-auth` — auto-login password for auth plugins (e.g. AuthMe)
- `discord.webhookUrl` — optional Discord webhook for connect/disconnect events

## How to run
```bash
npm install
npm start
```

The bot connects to the configured server and the dashboard is available at the Replit preview URL.

## User preferences
- Project language: Portuguese (BR)
