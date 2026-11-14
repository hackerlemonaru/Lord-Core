# Supported Minecraft versions

Lord-Core 0.22.0 is published as one jar per Minecraft version. All jars come from the same source code; each is compiled against the Paper API of its own version and then tested on a Paper server of that version.

| Minecraft | Paper build tested | Java | Console test | In-game bot test |
|---|---|---|---|---|
| 1.21.11 | 132 | 21 | passed | passed |
| 26.2 | 135 | 25 | passed | not possible yet |
| 26.3 | 249 | 25 | passed | not possible yet |
| 26.1.2 | 74 | 25 | passed | passed |
| 1.21.10 | 130 | 21 | passed | passed |
| 1.21.8 | 60 | 21 | passed | passed |
| 1.21.4 | 232 | 21 | passed | passed |
| 1.21.1 | 133 | 21 | passed | passed |
| 1.20.6 | 151 | 21 | passed | passed |

## What the tests are

**Console test.** The server is started three times with the jar. About 160 console commands are run across the features (economy, punishments, admin tools, switching features on and off), and the server log is checked for errors.

**In-game bot test.** Scripted players join the server and use the plugin the way real players do: paying, selling, the auction house, crates and ranks, bounties and combat tag, duels, admin commands, and the web panel (including ranks, crate keys, teams and anti X-ray from the page). Eight scripts are run per version and the server log is checked for errors after each one.

The bot library cannot join 26.2 and 26.3 servers yet, so those two versions have the console test only. Menus and player actions are therefore not exercised on 26.2 and 26.3.

Not every feature has a bot script in this per-version run (for example spawners, orders and the network feature do not), and the tests do not replace playing on a real server. If something misbehaves on your version, please open an issue with the Paper version and the console error.

## Differences between versions

- **1.20.6:** items and blocks added in later versions do not exist, so they are missing from the shop item list. Saved shop backups and duel inventories use a storage format of their own on this version.
- **26.x:** needs Java 25, as Paper itself does.
- **1.20.4 and older:** not supported. Paper changed how items work in 1.20.5 and needs Java 17 before it.
