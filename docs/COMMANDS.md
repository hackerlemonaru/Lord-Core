# Admin commands

The same list is shown in game: `/adminar`, then Commands. Player commands are listed per feature in [FEATURES.md](FEATURES.md).

### Money and shards

| Command | What it does |
|---|---|
| `/money give\|take\|set <player> <amount>` | Change a player's money (also /eco ...) |
| `/shards give\|take\|set <player> <amount>` | Change a player's shards |
| `/money <player>  /shards <player>` | Look at a balance |

### Sell and worth

| Command | What it does |
|---|---|
| `/worth set <price>  /worth remove` | Price of the item in your hand |
| `/adminar, Editors, Worth` | Edit all prices on a screen |

### Shop

| Command | What it does |
|---|---|
| `/shop edit` | Edit the shop; click an empty slot for the full item list |

### Teleport

| Command | What it does |
|---|---|
| `/setspawn` | Set the spawn point where you stand |

### Sidebar and tab list

| Command | What it does |
|---|---|
| `/sidebar edit` | Edit the title, lines and tab list on a screen of signs |
| `/sidebar edit <theme>` | Use a ready-made theme: donut, ocean, sunset, classic, smallcaps, minimal, boxed, pvp |

### Web panel

| Command | What it does |
|---|---|
| `/webpanel link` | Show the link of the web panel |
| `/webpanel newlink` | Make a new key and sign every browser out |
| `/webpanel restart` | Reconnect to Cloudflare (gives a new address) |

### Anti X-ray

| Command | What it does |
|---|---|
| `/antixray` | Open the Anti X-ray screen: level, worlds, block lists, what is live |
| `/antixray level <1\|2>` | 1 = buried ores look like stone, 2 = fake ores everywhere as well |
| `/antixray worlds <all\|overworld\|nether\|end\|name>` | Choose where it works |

### Auction house

| Command | What it does |
|---|---|
| `/ah, then shift-right-click a listing` | Remove a listing; the item goes back to the seller |

### Shards and AFK

| Command | What it does |
|---|---|
| `/setafk` | Set the centre of the AFK zone |

### Playtime

| Command | What it does |
|---|---|
| `/playtime set\|add <player> <time>` | Change playtime, for example 12h or 3d (player must be online) |

### Crates

| Command | What it does |
|---|---|
| `/key give <player\|all> <crate> [amount]` | Give crate keys |
| `/key take <player> <crate> [amount]` | Take crate keys |
| `/crateblock set <crate> \| remove \| list` | Make the block you look at a crate |
| `/adminar, Editors, Crates` | Edit crates and their rewards on a screen |

### Ranks

| Command | What it does |
|---|---|
| `/rank set <player> <rank> [days]` | Give a rank, for ever or for some days |
| `/rank remove <player>  /rank info <player>  /rank list` | Take, look up and list ranks |
| `/adminar, Editors, Ranks` | Create and edit ranks on a screen |

### Spawners

| Command | What it does |
|---|---|
| `/spawner give <player> <mob> [amount]` | Give spawners |

### Combat

| Command | What it does |
|---|---|
| `/combat untag <player>` | End a player's combat tag |

### Bounties

| Command | What it does |
|---|---|
| `/bounty remove <player>` | Delete the bounty on a player (the money is not paid back) |

### Stats

| Command | What it does |
|---|---|
| `/stats set <player> <kills\|deaths\|streak\|best> <number>` | Change one figure |
| `/stats reset <player>` | Set kills, deaths and streaks to 0 |

### Teams

| Command | What it does |
|---|---|
| `/team forcedisband <team>` | Delete a team |

### Punishments and staff

| Command | What it does |
|---|---|
| `/punish <player>` | Punish step by step on a screen |
| `/warn /mute /kick /ban /ipban <player> [length] [reason]` | Punish directly |
| `/unmute /unban <player> <reason>` | Lift a punishment |
| `/history /alts /notes <player>  /note <player> <text>` | Look up a player |
| `/staff  /vanish  /cmdspy` | Staff mode, invisible, see commands |
| `/freeze /invsee /echest /stp /tphere <player>` | Hold, inspect and teleport |
| `/sc <text>  /reports  /ecorollback <player> <time>` | Staff chat, reports, undo money changes |

### Duels

| Command | What it does |
|---|---|
| `/duel arena create\|pos1\|pos2\|delete <name>  /duel arena list` | Set up arenas |

### Amethyst tools

| Command | What it does |
|---|---|
| `/amethyst give <player> <tool>` | Give an amethyst tool |

### Billford

| Command | What it does |
|---|---|
| `/billford spawn  /billford remove` | Place or remove the trader |

### Network

| Command | What it does |
|---|---|
| `/network` | Link status with the other servers |
