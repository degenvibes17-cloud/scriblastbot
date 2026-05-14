# ScriblastBot — A Telegram bot that writes articles and repurposes them

Demo: [@ScriblastBot](https://t.me/ScriblastBot)

## What is this?

Send a topic, get a full article. Send /done, get 7 platform-optimized posts.

## Architecture

```
scriblastbot/
├── scriblastbot.py   — Main bot logic (Telegram + LLM)
├── data/             — Persistent user credit storage
├── .env              — API keys (not committed)
├── requirements.txt
├── README.md
└── LICENSE
```

## Setup

```bash
git clone https://github.com/degenvibes17-cloud/scriblastbot.git
cd scriblastbot
pip install -r requirements.txt
cp .env.template .env   # fill in your API keys
python scriblastbot.py
```

## Environment Variables

| Variable | Description |
|----------|-------------|
| `BOT_TOKEN` | Telegram bot token from @BotFather |
| `LLM_API_KEY` | AI language model API key |
