# 🚀 openclaw-skill-uexcorp-sc

[![OpenClaw Compatible](https://img.shields.io/badge/OpenClaw-Compatible-blue.svg)](#)
[![ShibaClaw Compatible](https://img.shields.io/badge/ShibaClaw-Compatible-orange.svg)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

⭐ An **OpenClaw** / **ShibaClaw** skill to fetch live *Star Citizen* trade data directly from the [UEXcorp](https://uexcorp.space) community database.

## 🛠️ What it does

Query live Star Citizen trade data seamlessly using your AI agent:

- 💰 **Commodities:** Buy and sell prices by terminal
- ⛏️ **Mining:** Raw material & mining prices
- 🛸 **Vehicles:** Ship/vehicle data and cargo capacity
- 🪐 **Locations:** Terminals, planets, moons, and star systems
- 🗺️ **Trading:** Best trade route suggestions based on real-time data

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

Try asking your agent:
> *"What's the price of Laranite at Lorville?"*
> *"Find me the best trade route from ArcCorp using a Cutlass Black."*
> *"Where can I sell Titanium for the most credits?"*
> *"Show me all terminals in the Stanton system."*

## 📡 Data source

All data is community-sourced via the [UEXcorp API 2.0](https://uexcorp.space/api/documentation/).  
*Note: Prices and data may slightly differ from live in-game values depending on community updates.*

## 📄 License

[MIT](LICENSE)
