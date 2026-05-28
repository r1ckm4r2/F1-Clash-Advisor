# 🏎️ F1 Clash Advisor — Claude Skill

A strategy advisor skill for **F1 Clash (2026)** that recommends optimal car setups, driver pairings, and upgrade paths based on your actual garage.

---

## What it does

- **Track-specific setup** — recommends the best 7-component car build and driver pair for any track based on its stat priorities (Speed, Cornering, Power Unit, Race Start, etc.)
- **Balanced series setup** — when racing a full series, analyzes all tracks in that series and recommends a balanced setup that doesn't sacrifice performance on any single track
- **Upgrade advice** — tells you what to upgrade next based on where you're headed, not where you've been
- **GP boost support** — accounts for 10% and 20% GP race boosts when calculating the best setup
- **Battery scoring** — correctly factors in Overtake Modifier and Impact stats unique to the Battery slot
- **Boost recommendations** — filters the 65 available race boosts down to the 14–18 most relevant for your track or series

---

## What's included

- All driver stats across every rarity (Common, Rare, Epic, Legendary) and every level up to max
- All component stats across all 7 slots, every rarity, every level up to max
- All 48 tracks across 12 series with stat priorities
- All 65 boosts with full stat breakdowns
- An interactive garage input form that pre-populates based on your series

---

## How to use it

Type any of the following to launch the interactive garage form:

> *"build my setup"* · *"bring up the UI"* · *"F1 Clash setup"* · *"let's build my setup"*

Select your series, adjust what you have, set component levels, and submit. The skill handles the rest.

---

## Installation

1. Download the `.skill` file from this repository
2. Rename it from `.skill` to `.zip`
3. Go to **[claude.ai](https://claude.ai)** in your browser
4. Navigate to **Customize → Skills**
5. Click **"+"** → **"+ Create skill"** → **"Upload a skill"**
6. Upload the `.zip` file and toggle it on

> **Prerequisites:** Code execution must be enabled under **Settings → Capabilities** before the Skills section appears.

Works on **claude.ai** (web and mobile browser) and the **Claude desktop app**. Skills must be installed via the web — once installed they are active in the Android and iOS apps automatically.

---

## Strategy principles baked in

- **Car-first** — components always matter more than drivers. A well-built car beats a stronger driver in a weak setup every time.
- **No exploitable gaps** — winning the primary stat is the goal, but large weaknesses in secondary stats can still cost you the race.
- **Balanced series logic** — never goes all-in on the majority track stat at the expense of minority tracks.
- **Battery is different** — the Battery slot is always scored on Overtake Modifier + Impact, not just Speed and Cornering.

---

## Compatibility

| Platform | Install | Use |
|----------|---------|-----|
| claude.ai (web) | ✅ | ✅ |
| Claude desktop app | ✅ | ✅ |
| Claude iOS app | via web | ✅ |
| Claude Android app | via web | ✅ |

---

*Built with game data compiled by the F1 Clash community. Covers Series 1–12, all 2026 drivers and components.*

