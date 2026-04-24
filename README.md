# 🚀 openclaw-skill-uexcorp-sc

⭐ OpenClaw/ShibaClaw skill for Star Citizen trade data via UEXcorp API

## What it does

Query live Star Citizen trade data powered by the [UEXcorp](https://uexcorp.space) community database:

- 💰 Commodity buy/sell prices by terminal
- ⛏️ Raw material & mining prices
- 🛸 Ship/vehicle data and cargo capacity
- 🪐 Terminals, planets, moons, star systems
- 🗺️ Best trade route suggestions

## 📦 Installation

1. Copy the `SKILL.md` file into your agent's skills folder:
   - **OpenClaw:** `~/.openclaw/skills/uexcorp-sc/SKILL.md`
   - **ShibaClaw:** `<workspace>/skills/uexcorp-sc/SKILL.md`

2. Get your free API token at [uexcorp.space/api/apps](https://uexcorp.space/api/apps)

3. Add your token to your configuration file:
```json
{
  "skills": {
    "entries": {
      "uexcorp-sc": {
        "apiToken": "YOUR_TOKEN_HERE"
      }
    }
  }
}
```

4. Restart your agent session and you're good to go! 🚀

## 💬 Example prompts

- *"What's the price of Laranite at Lorville?"*
- *"Best trade route from ArcCorp with a Cutlass Black?"*
- *"Where can I sell Titanium for the most credits?"*
- *"Show me all terminals in the Stanton system"*

## 📡 Data source

All data is community-sourced via [UEXcorp API 2.0](https://uexcorp.space/api/documentation/).
Prices may slightly differ from live in-game values.

## 📄 License

MIT
