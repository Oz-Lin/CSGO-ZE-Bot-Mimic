# CS:GO Zombie Escape: Bot Mimic Files
Make bots great again in CS:GO Zombie Escape! 

Using this plugin https://forums.alliedmods.net/showthread.php?t=164148

Not enough people playing on your server? No worries! Bots will replay your gameplay footage on the human side. This would "kinda" make bots playable in zombie escape mode.

## Showcase Video
YouTube: https://www.youtube.com/watch?v=Ba4o3VG9xjU 

[![IMAGE ALT TEXT HERE](https://yt-embed.live/embed?v=Ba4o3VG9xjU)](https://www.youtube.com/watch?v=Ba4o3VG9xjU)

Bilibili: https://www.bilibili.com/video/BV1uD4y167FQ

## Note to popular CS:GO zombie escape communities
* You can choose not to have this plugin and configs since you already have more than 20 players every day. 
* But if you like, feel free to contribute to this repository (See `Contribution Rules` below) :)

## Installation
1. Install `[CS:S/CS:GO] Bot Mimic - Record your movements (Version 2.1 updated 02.10.2014)` on your server -> Github Link: https://github.com/peace-maker/botmimic
2. In your `csgo\cfg\sourcemod\plugin.botmimic.cfg`:
    * Set your cvar `sm_botmimic_snapshotinterval` to `1000`.
    * Set your cvar `sm_botmimic_respawnondeath` to `0`.
3. Copy the `default` folder into your `csgo\addons\sourcemod\data\botmimic`


## Criteria of Supported Maps
* Maps with only one single stage (It can be as short as icecap, or as long as OBJ series)
* Maps without random paths

## Known Bugs
* If the mimic bots are chosen as mother zombie, they still holding guns.
* Not all maps have slaying zone covered in all areas. Some bots might not be slayed at the end of map.

## Contribution Rules
1. You must have the same cvar as in `Installation`
2. You must start recording as soon as new round begins.
3. If you are chosen as mother zombie after the infection countdown, or being killed or infected in the middle of recording, you must discard the recording.
4. Naming the `.rec` footage files is optional, but good to do so :)
5. If you are forking this repository, remember to keep your repository up-to-date before doing a pull request.

## Any other questions?
* Australian Zombie Escape server: steam://connect/csgo.ozlin.info:27058
* Discord: https://discord.io/ozlin-info
* Steam Group: https://steamcommunity.com/groups/ozlin-gaming
* or just send a GitHub issue

![Gametracker banner(https://cache.gametracker.com/server_info/103.137.14.27:27058/b_560_95_1.png)](https://cache.gametracker.com/server_info/103.137.14.27:27058/b_560_95_1.png)
