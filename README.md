📌 Discord Bot Command Guide
This guide explains how to use the bot’s message relay system, sync commands, and change the fixed channel if needed.

🔹 Changing the Fixed Channel
By default, the bot listens for relay commands in a specific fixed channel. If you want to change it, follow these steps:

1️⃣ Update the Bot’s Settings
Open the bot’s settings or ask the server admin to update the fixed channel.
Choose the new fixed channel where the bot should listen for commands.
2️⃣ Adjust Bot Permissions
Make sure the bot has the following permissions in the new fixed channel:
✅ View Channel
✅ Send Messages
✅ Read Message History

Remove these permissions from the old fixed channel if necessary.

3️⃣ Restart the Bot (If Needed)
Some changes might require the bot to be restarted.
If the bot stops working, check its settings or ask the server admin for help.
🔹 Message Relay System
The bot can connect two channels, allowing messages from one to be forwarded to another.

How to Link a Channel
Go to the fixed channel and type the command to set a target channel.
Enter the channel ID of the channel where messages should be forwarded.
The bot will confirm when the connection is successful.
Sending Messages After Connecting
Once linked, any message sent in the fixed channel will be automatically forwarded to the target channel.

🔹 Troubleshooting Errors
1️⃣ "Invalid channel ID or bot lacks access."
✔ Make sure the channel ID is correct.
✔ Ensure the bot has permission to send messages in the target channel.

2️⃣ "The connected channel is no longer accessible."
✔ Check if the target channel was deleted or renamed.
✔ Try reconnecting by setting a new channel ID.

🔹 Syncing Slash Commands
If slash commands (/commands) are not appearing, you may need to refresh them.

How to Sync Commands
Use the sync command provided by the bot.
This will update all available slash commands in Discord.
🔹 Final Tips
✅ Always update the fixed channel when moving the relay system.
✅ Check bot permissions in both the fixed and target channels.
✅ Restart the bot if changes are not applied.

