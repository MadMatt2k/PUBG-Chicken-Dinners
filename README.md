# 🐔 PUBG Chicken Dinner Bot

> The most feature-complete PUBG tracking bot for Discord. Built for serious squads, streamers, and competitive communities.

[![Discord Bots](https://top.gg/api/widget/servers/1403723550141186118.svg)](https://top.gg/bot/1403723550141186118)
[![Discord Bots](https://top.gg/api/widget/upvotes/1403723550141186118.svg)](https://top.gg/bot/1403723550141186118)

---

## 🔗 Links

- **Add to your server**: [top.gg/bot/1403723550141186118](https://top.gg/bot/1403723550141186118)
- **Privacy Policy**: [View Privacy Policy](https://madmatt2k.github.io/PUBG-Chicken-Dinners/privacy.html)
- **Terms of Service**: [View Terms of Service](https://madmatt2k.github.io/PUBG-Chicken-Dinners/terms.html)

---

## ✨ Features

### 📊 Stats & Comparisons
Pull current-season stats for any PUBG Steam player as a polished image — perspective follows your server's mode (FPP or TPP). Squad stats include **True KD and True ADR** — calculated from raw match telemetry, excluding bots and friendly fire, with all deaths counted. Compare 2–3 players side by side.

### 🏆 Win Posters
Automatically detects when a tracked team wins and posts a custom win poster image — complete with player stats, kills, and match details.

### 🎬 PUBG.report Clip Tracking
Monitors pubg.report and auto-posts clips when tracked players eliminate streamers. Filters out TDM and non-competitive modes automatically.

### 📋 Last Match Reports
Detailed last match reports posted automatically after every game — placement, kills, damage, survival time and more.

### 🗺️ Drop Survival & Endzone Heatmaps
Visualize where players land and survive to Phase 1, broken down by POI. Also tracks Phase 5 safe zone tendencies per map.

### 📈 Clan Rankings
Nightly auto-ranking images posted at 03:00 server time, scoring players across ADR, KD, Avg Placement, Assists, Revives and more. Each server independently chooses **Squad FPP or Squad TPP** as its ranking mode via a single `setmode` command. Rankings, stat cards, and comparisons all reflect the server's chosen perspective. Supports on-demand posting and per-player visibility controls.

### 🔀 FPP & TPP Support
The bot tracks both perspectives simultaneously for every player — no re-tracking needed. Switch your server's mode anytime with `/auto-clan-ranking` → `setmode`.

### 🌍 Global Player Ranking
Cross-server leaderboard showing all tracked players across every connected Discord — with Guild labels per player.

### ⚙️ Fully Configurable
- Per-feature channel selection
- Per-player ignore/enable controls for every auto-feature
- Server timezone support for accurate timestamps
- Discord member linking for @ mention pings on new clips
- Manage Server permission gating for all admin commands

---

## 🚀 Getting Started

1. [Add the bot to your server](https://top.gg/bot/1403723550141186118)
2. Use `/add-user` to add your first PUBG player
3. Use each auto-feature's `setchannel` action to configure your posting channel
4. Enable features with `/auto-win enable`, `/auto-lastmatch enable`, etc.
5. Run `/help` anytime to see all available commands

---

## 📋 Commands Overview

| Category        | Commands                                                                                                          |
| --------------- | ----------------------------------------------------------------------------------------------------------------- |
| Stats           | `/stats` `/compare` `/lastmatch` `/accountinfo`                                                                   |
| Heatmaps        | `/dropsurvival` `/endzone`                                                                                        |
| Tracking        | `/add-user` `/remove-user` `/list-tracked-users` `/link-player`                                                   |
| Rankings        | `/global-player-ranking` `/global-guild-ranking` `/auto-clan-ranking`                                             |
| Auto Win        | `/auto-win` `/auto-win-ignore-player` `/auto-win-enable-player`                                                   |
| Auto Report     | `/auto-pubg-report` `/auto-pubg-report-ignore-player` `/auto-pubg-report-enable-player`                           |
| Auto Last Match | `/auto-lastmatch` `/auto-lastmatch-ignore-player` `/auto-lastmatch-enable-player`                                 |
| Auto Ranking    | `/auto-clan-ranking-ignore-player` `/auto-clan-ranking-enable-player`                                             |
| Testing         | `/testwin` `/testreport`                                                                                          |
| Admin           | `/set_server_timezone` `/change-update-channel` `/help`                                                           |

---

## 🔒 Privacy & Data

This bot collects PUBG player IDs, display names, and match statistics sourced from the official PUBG API. Data is stored locally per guild and per season, and is automatically cleaned up on season reset. No data is sold or shared with third parties.

For full details see our [Privacy Policy](https://madmatt2k.github.io/PUBG-Chicken-Dinners/privacy.html) and [Terms of Service](https://madmatt2k.github.io/PUBG-Chicken-Dinners/terms.html).

---

## ⚠️ Disclaimer

PUBG Chicken Dinner Bot is not affiliated with or endorsed by KRAFTON, Inc. PUBG and all related marks are trademarks of KRAFTON, Inc.

---

*Supports Steam (PC) only. Requires the PUBG API.*
