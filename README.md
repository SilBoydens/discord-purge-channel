# discord-purge-channel
purge a discord channel

# usage

1. get your discord token
 - this can be your own token or a bot token
 - if you don't know how to get your own token then don't do it (security reasons)
 - [getting a bot token](https://github.com/reactiflux/discord-irc/wiki/Creating-a-discord-bot-&-getting-a-token)
 
 2. get the channel ID
 - either use dev mode (if you know dev mode then you know how to use it)
 - or use this trick:
 - type the channel name with a `\` in front, so to get the ID of #general, type `\#general` and send that message, only take the numbers out of the responds 
 - ![example](https://cdn.discordapp.com/attachments/235378515866812417/269195258640728075/2017-01-12_22-05-03.gif)
 3. now open any cli in the map with the exe file, and run `./discord-purge-channel.exe <TOKEN> <CHANNEL_ID>` replacing \<TOKEN> and \<channel_ID> with the corresponding values
 4. you will see the last message of this channel and need to press `Y` or `enter` to start clearing the channel
