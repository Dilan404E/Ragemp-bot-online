# Discord bot to show your server online on RageMP
> Requires NodeJS 16.8 and up to run)

# First version
***The bot displays your server's online as a category name change.***

- Download all files and upload them to a separate folder on your Linux/Windows hosting

- First you need to create a bot on https://discord.com/developers/applications/.

- Next change the token in the file **config.json**
- Replace the server name with your own in the file **config.json** - variable **serverName** - specify the exact match of the name
- Set the online update time in the file**config.json** - variable **timerDelayInMinutes** - enter the exact time in minutes

- Invite a bot to the server (you can find information on creating and inviting a bot on the Internet)

- Install the required modules via **npm i**

- Run the bot on your hosting via **node bot.js** by writing this command in terminal or command line

- In your Discord server, create a category called `Online:` (All characters are required; capital or small letters do not matter)

- The bot finds a category with the name `Online:` and changes its name to `Online: 60/1000`, For example

------------


# Second version
In the second version, I added the display of your server name in the bot status and changing the bot's nickname automatically to the name of your server.
![]({{site.baseurl}}/https://i.imgur.com/LDusYRJ.png)
