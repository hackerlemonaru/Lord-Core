# Features

Every feature is a module that can be switched on or off in game with `/adminar` (Features), or with `/adminar enable|disable <id>`. A module that is off registers no commands and does no work.

| Feature | Id | What it adds | Default |
|---|---|---|---|
| **Economy** | `economy` | Money and shards ledger, /bal, /pay, /baltop, /eco, Vault support. | on |
| **Sell & Worth** | `sell` | /sell chest, /sellhand, /sellall, /worth, sell history, sell multiplier. | on |
| **Shop** | `shop` | Server shop with categories, and the in-game /shop edit editor. | on |
| **Teleport & Homes** | `teleport` | /spawn, /home, /sethome, /tpa, /tpahere, /rtp with a warm-up. | on |
| **Settings** | `settings` | Per-player /settings menu. Other modules add their choices to it. | on |
| **Scoreboard & Tab** | `scoreboard` | Sidebar, tab header and footer, /sidebar. | on |
| **Auction House** | `auction` | /ah player market: list, search, sort, buy, collect unsold items. | off |
| **Orders** | `orders` | /orders and /order: buy orders paid up front, delivered in parts. | off |
| **Shards & AFK** | `shards` | /afk zone that pays shards over time. Spend them in the shop. | off |
| **Spawners** | `spawners` | Stackable spawners that make loot instead of mobs, with a rules menu. | off |
| **Crates & Keyall** | `crates` | /crates with virtual keys, /key, and a keyall timer. | off |
| **Ranks** | `ranks` | Your own ranks: prefix, chat format, permissions and perk limits. None pre-made. | off |
| **Playtime Rewards** | `playtime` | /playtime and /rewards: milestone and repeating rewards. | off |
| **Worth on Hover** | `worthhover` | Shows what an item sells for in its tooltip. Needs the PacketEvents plugin. | off |
| **Teams** | `teams` | /team: invite, team chat, team home, friendly fire switch. | off |
| **Bounties** | `bounties` | /bounty puts money on a player; the killer collects it. | off |
| **Friends & Messages** | `social` | /msg, /r, /ignore, /friend with a friends screen. | off |
| **Stats & Leaderboards** | `stats` | /stats and /leaderboard: kills, deaths, streaks, playtime, money. | off |
| **Combat Tag** | `combat` | Combat tag: blocked commands and logout counts as death. | off |
| **Punishments and staff tools** | `punishments` | /punish, bans, mutes, history, vanish, freeze, reports. | off |
| **Amethyst tools** | `amethyst` | /amethyst: timed special tools for shards, 3x3 mining. | off |
| **Billford** | `billford` | /billford: a trader whose goods change every few hours. | off |
| **Duels and FFA** | `duels` | /duel with kits, arenas, queue and rating; /ffa. | off |
| **Web panel** | `cloudflare` | A web page with console, players and controls, through a free Cloudflare tunnel. | off |
| **Anti X-ray** | `antixray` | Hides ores from X-ray users with Paper's own engine. Level 1 or 2, per world. Needs one restart to start or stop. | off |
| **Network** | `network` | Links servers through Redis: balances, punishments, staff chat, messages. | off |
