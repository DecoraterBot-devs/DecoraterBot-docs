### Plugin Commands for DecoraterBot

Commands are usually using the `/` prefix.

List of current Plugin Commands.

|   	| Plugin Commands (credits.py)	|
|:---------------:	|:------------------------------------------------------------------------------------------------:	|
| ``/credits``	| Gives Daily Credits even if the Tatsumaki bot is present in the server this command is sent from.	|
| ``/balance``	| Gives your current Credit Balance.	|
| ``/givecredits <mention user(required)> <amount(required)>``	| Transfers Credits from you to another user.	|

|   	| Plugin Commands (moderation.py)	|
|:---------------:	|:------------------------------------------------------------------------------------------------:	|
| ``/prune <number of messages to remove>``	| Prune a specific number of messages. Max is 100 due to Ratelimits. (Servers only)	|
| ``/kick <mention person here>``	| Kicks the User mentioned.	|
| ``/ban <mention person here>``	| Bans the User mentioned.	|
| ``/softban <mention person here>``	| Bans and then Immediately Unbans the user mentioned. (prune kick)	|
| ``/clear``	| Clears all messages from bot within a 100 message limit.	|

<!-- Some commands are commented out here and in the source code until I think more about them.
I have to decide if I want to officially remove them or keep them and modify them. -->

|   	| Plugin Commands (commands.py)	|
|:------:	|:-:	|
| ``/uptime``	| Makes the bot Reply withh the uptime of the bot's process.	|
| ``/coin``	| Flips an coin that can land on Heads or Tails.	|
| ``/commands``	| Links to the bot's commands (this file).	|
| ``/source``	| Shows GitHub Repositories. (Works in PM and servers)	|
| ``/pyversion``	| Makes the bot Reply with the Version of the Python Interpreter used as well as the bits of it. (32 or 64 bit versions)	|
| ``/userinfo <mention user (optional if you want to see your own info)>``	| Shows your or the person you mentioned user information.	|
| ``/stats``	| Gives the bot's current stats including the number of servers it is currently in.	|

|   	| Plugin Commands (corecommands.py)	|
|:------:	|:-:	|
| ``/load <plugin name>``	| Allows loading of bot plugins. (Bot owner only)	|
| ``/unload <plugin name>``	| Allows unloading of bot plugins. (Bot owner only)	|
| ``/reload <plugin name>``	| Allows reloading of bot plugins. (Bot owner only)	|
| ``/botban <mention user>``	| Bans a specific user from using the bot.	|
| ``/botunban <mention user>``	| Unbans a specific user for them to the bot.	|

