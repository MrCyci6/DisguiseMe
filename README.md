# DisguiseMe : Disguise as the mob of your choice with a simple command by using packets ! (In Skript, without LibsDisguise)
![Features](https://i.ibb.co/K5yHB5w/Features.png)
### This script works from minecraft 1.8 up to minecraft 1.16 with packets therefore it doesn't require iDisguise or LibsDisguise ! 
### You can disguise as the mob you want and remove your disguise without having to disconnect !
### Your disguise stay even if you disconnect!
### Screenshots [1](https://ibb.co/K7NqxMj) [2](https://ibb.co/64wPh7p) [3](https://i.ibb.co/FJsw4Sb/2020-04-23-14-32-09.png) | [Old video to show that it works](https://www.youtube.com/watch?v=cP3a86qPIWE) |
### [French Version](https://skript-mc.fr/forum/files/file/322-disguiseme/) | [French video about it](https://www.youtube.com/watch?v=9tYIYT4FVgo)
![Commands](https://i.ibb.co/fYBf22L/Commands.png)
```
/disguise help : list all the commands(permission: self.disguise)
/disguise list : List all the mobds that can be used with your version (permission: self.disguise)
/disguise <Mob> : Disguise in a mob (permission: self.disguise) (example: /disguise Enderman)
/disguise <Mob> <Player> : Disguise a player in a mob (permission: other.disguise)
/undisguise : Remove your disguise (permission: self.undisguise)
/undisguise <Player> : Remove a player's disguise (permssion: other.undisguise)
```
![Options](https://i.ibb.co/SJ9Mwcg/Options.png)
 * You can remove the player's name above his disguise
 * You can customize the name of every mob
 * There are other options, but you shouldn't modify them unless you know what you're doing

![Addons](https://i.ibb.co/QdcGkjv/Addons.png)
* You need a [recent version of Skript](https://github.com/SkriptLang/Skript/releases) if possible (or [here](https://github.com/Matocolotoe/Skript-1.8/releases) for MC 1.8)
* [ThatPacketAddon](https://forums.skunity.com/resources/thatpacketaddon.847/) (for packets)
* [Skript-Mirror](https://skripttools.net/dl/skript-mirror+2.0.0-SNAPSHOT.jar) (EntityId, pitch, yaw & packets) (or skript-reflect but I didn't test with it)
* [ProtocolLib](https://www.spigotmc.org/resources/protocollib.1997/) (for packets)

![Bugs](https://i.ibb.co/Jj9pkD7/bugs.png)
Known bugs that cant be fixed or that I don't have the time to fix right now
* The player will have the hitbox of the mob he is disguised as (with physical hit) (unfixable)
* Some mobs use pitch & yaw in a weird way such as Guardians
* Enderdragons face the wrong direction
* Shulkers don't move (They don't move in vanilla)
* In 1.9 & 1.10, rightclicking on a villager can make the clicker crash, and in 1.8 it makes him invisible for the clicker
* Bats look afk, but doing a metadata customization for each mob would be too long
* NPCs are hidden with Citizens2. I can't fix it, just listening to a packet make this (even if I don't modify it)

![Functions](https://i.ibb.co/GdzPPfj/Functions.png)
You can use functions in order to avoid "make console execute command /disguise.." and to disguise some players for others players. See more [here](https://phe0x.fr/DisguiseMe/Functions.html) (ugly but still readable) or read the code

![Thanks](https://i.ibb.co/MkrDvfz/Thanks.png)
* Rush²Fer for helping me giving a name to the entities in 1.13 and above, ThatPacketAddon not working with optionnal chat
* CarloDrift for giving me ideas and helping me test this
* Anarchick for the help on the functions to show the stuff of the player in 1.16
* And you for downloading or contributing to this script :D

![Bugs](https://i.ibb.co/ZXfW03c/Q-B.png)
If you find any bugs, any typos or need help, make an issue or contact me on Discord (Phe0X#5907), I'll reply in the next weekend following your message!
I won't be really active anymore, [read this for more information](https://www.spigotmc.org/threads/disguiseme-1-8-1-16.434216/page-2#post-3927112)
