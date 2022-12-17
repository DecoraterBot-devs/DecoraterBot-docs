### Plugin Commands for DecoraterBot

Commands are usually using the `/` prefix.

List of current Plugin Commands.

|   	| Plugin Commands (moderation.py) (Loaded by Default)	|
|:---------------:	|:------------------------------------------------------------------------------------------------:	|
| ``/prune <number of messages to remove>``	| Prune a specific number of messages. Max is 100 due to Ratelimits (Servers only).	|
| ``/clear``	| Clears all messages from bot within a 100 message limit.	|

|   	| Plugin Commands (nsfw.py) (Not loaded by Default)	|
|:---------------:	|:------------------------------------------------------------------------------------------------:	|
| ``/rule34``	| Searches rule34 for images (warning: may return explicit images so it can only be used in nsfw channels as it is hidden otherwise).	|

|   	| Plugin Commands (commands.py) (Loaded by Default)	|
|:------:	|:-:	|
| ``/uptime``	| Makes the bot Reply withh the uptime of the bot's process.	|
| ``/coin``	| Flips an coin that can land on Heads or Tails.	|
| ``/commands``	| Links to the bot's commands (this file).	|
| ``/source``	| Shows GitHub Repositories. (Works in PM and servers)	|
| ``/userinfo <mention user (optional if you want to see your own info)>``	| Shows your or the person you mentioned user information.	|
| ``/stats``	| Gives the bot's current stats including the number of servers it is currently in.	|

|   	| Plugin Commands (corecommands.py) (Loaded by Default)		|
|:------:	|:-:	|
| ``<mention> load <plugin name>``	| Allows loading of bot plugins (Bot owner only).	|
| ``<mention> unload <plugin name>``	| Allows unloading of bot plugins (Bot owner only).	|
| ``<mention> reload <plugin name>``	| Allows reloading of bot plugins (Bot owner only).	|
| ``<mention> sync``	| Syncs all of the bot's commands (Bot owner only).	|
