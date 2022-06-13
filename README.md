# SmartBot Readme
Note:This script is made for personal experimentation only, use it in accordance to terms of use.
 
 
 
 
This chatbot can handle an incredibly large number of tasks and topics, it can help you learn new topics, and translate to other languages (even programming languages!), it can write you a poem or an email and much more. Have a play around with it and send me some feedback.
 
 
##setup 
 
1.Follow this video till about 4:40 minutes through, save the token in line 10 (https://www.youtube.com/watch?v=fU-kWx-OYvE)
 
2.Make an account with openai and enter API key on line 6
 
3.Change the discordchannel on line 23 to the name of the discord channel you want the bot to interact with.
 
### Quickstart for interacting with the bot
The bot is ready to use out of the box, start to talk to it about whatever you want. The bots replies are based off its memory of the conversation so far (aka the 'prompt') if it starts to go off the rails just send it a message saying '!restart' to rset its memory (or !prompt)
 
If you want to give the bot a personality use the !prompt command to set a custom prompt. 
Examples:
Writing tutor bot: !prompt the bot 'Brainy' is a writing tutor, he is here to give you feedback on your writing
Terminal Navigator: !prompt Brainy converts your messages into linux terminal commands
Pirate Bot!!!: !prompt Brainy is a pirate, he talks like a pirate and swears like one too
 
Or if you want to quickly talk to an expert of a particular field use the !expert command. Just type !expert TOPIC.
Example:
!expert Antient Rome 
 
 
### Advanced Options
 
##### !settings
This command will show you the current settings of the bot, you can change these settings to change the bots personality.
 
##### !temp=
This command sets the temperature of the bot, the higher the value the more random the bots responses will be.
 
##### !max=
This command sets the max_tokens of the bot, the higher the value the longer the bots responses will be.
 
##### !top=
This command sets the top_p of the bot, the higher the value the more likely the bot is to repeat itself.
 
##### !freq=
This command sets the frequency_penalty of the bot, the higher the value the less likely the bot is to repeat itself.
 
##### !pres=
This command sets the presence_penalty of the bot, the higher the value the more likely the bot is to come up with new topics.
 
##### !show-prompt
This command shows you the bots current prompt, this is the bots memory of the conversation so far.
 
##### !startover
This command resets the bots prompt to the last !prompt or !expert command.
 
##### !restart
This command resets the bots prompt to the default prompt and resets all settings.
 
##### !help
This command shows you all the commands the bot can handle.
 
 
