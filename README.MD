# Cowlection
![Cowlection](https://github.com/cow-mc/Cowlection/blob/master/cowlection.png?raw=true)
> Cow's collection ➔ Cowlection

Cowlection is a client-side-only Forge mod by [Cow](https://namemc.com/profile/Cow) for Minecraft version 1.8.9.  
It is a collection of different features mainly focused on Hypixel SkyBlock. 🐄

## Current features
➜ Use `/moo help` to see all available commands.
➜ Use `/moo config` to adjust the features to your needs.

| Feature                                                                 | Command/Usage                           |
|-------------------------------------------------------------------------|-----------------------------------------|
| Search through your Minecraft log files                                 | `/moo search` (click the `?` for more info) |
| Stalk a player (check online status, current game, ...)                 | `/moo stalk`                            |
| Show all client-side commands added by all installed mods               | `/commandslist`                         |
| Copy chat component                                                     | <kbd>ALT</kbd> + <kbd>right click</kbd><br>Hold <kbd>shift</kbd> to copy full component |
| Copy inventories to clipboard as JSON                                   | <kbd>CTRL</kbd> + <kbd>C</kbd> (single item)<br><kbd>CTRL</kbd> + <kbd>SHIFT</kbd> + <kbd>C</kbd> (whole inventory) |
| Copy info of "the thing" you're looking at (NPC or mob + nearby "text-only" armor stands; armor stand, placed skull, banner, sign, dropped item, item in item frame, map on wall) | `/moo whatAmILookingAt` |
| Tab-completable usernames for several commands (e.g. `/party`, `/invite`, ...) | `/moo config` &rarr; `Commands with Tab-completable usernames` for full list of commands |
| Auto-replace `/r` with `/w <latest username>`                           | `/r `, use `/rr` to avoid auto-replacement |
| Change guiScale to any value                                            | `/moo guiscale [newValue]`              |
| Check for mod updates on server login and via command                   | `/moo update`                           |

### SkyBlock related features
| Feature                                                                 | Command/Usage                           |
|-------------------------------------------------------------------------|-----------------------------------------|
| Stalk SkyBlock stats of a player                                        | `/moo stalkskyblock`                    |
| Analyze chests and their Bazaar, lowest BINs, and NPC value on your private island | `/moo analyzeChests`         |
| Analyze minions, chest and hopper counts on a private island            | `/moo analyzeIsland`                    |
| Improved Dungeon item tooltips (item quality + obtained floor; normalize dungeon item stats) | To normalize stats: Hold <kbd>shift</kbd> (configurable) while viewing a dungeon item tooltip |
| Improved Dungeon Party Finder                                           | configure with `/moo config party`      |
| Dungeon Party inspector (Who is in my party again? What class are we missing?) | `/moo dungeon party` or `/moo dp` |
| Dungeon performance tracker and overlay: Skill score calculation, class milestone tracker, destroyed crypts tracker, and elapsed time indicator | automatically; or with `/moo dungeon` |
| Check how long current world has been loaded (≈ when the server was last restarted) | `/moo worldage` + `/moo config` &rarr; SkyBlock |
| Additional info in various tooltips (e.g. show item age, display pet exp, price per item in an auction, Bestiary overview) | `/moo config` &rarr; SkyBlock &rarr; Tooltip enhancements |
| Quick lookup for item prices and wiki articles                          | Prices: <kbd>P</kbd>, Wiki: <kbd>I</kbd> *(= Info; use <kbd>SHIFT</kbd> to switch between Fandom and official wiki)* |

### Installation

Download the newest Release and use it like every other forge mod.

### How to install a forge mod
- [Download the latest forge version](http://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.8.9.html "Download Forge")
- Run it to install forge  

- Open minecraft launcher and check if forge's profile is there, if not then you can create it ![image](https://user-images.githubusercontent.com/74936369/111808098-b8d7bf00-88e4-11eb-8a2d-60e93b1406a5.png)
- **Windows**: Press windows+r and type %appdata%/.minecraft/
- **Linux**: .minecraft is located in your home folder. ~/.minecraft
- **Mac**: do ⌘ (Command) + Space type "~/Library/Application Support/minecraft/
- Create a folder called "mods" if it isnt there already. then put the mods you download inside that folder and start minecraft.
                   
### Legal Disclaimer

This was made for educational purposes only, nobody which directly involved in this project is responsible for any damages caused.
**You are responsible for your actions.**