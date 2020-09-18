# Discord.js Bot Template
Make a free Discord bot using discord.js! This template has cooldowns, owner-only commands and more! (With help from the Discord.js guide https://discordjs.guide)

# How to use:

Run: `git clone https://github.com/haroongames-git/discord.js-bot-template.git` in your terminal. 

Again, in the terminal, run `npm install`. This will install any needed dependencies, and the database.

Then run the setup program using: `npm run setup`. 
It will ask you for your bot token and some other settings, such as a status (Online, Idle, Do Not Disturb, Invisible) and a presence (PLAYING, LISTENING, STREAMING, WATCHING) as well as the text you want. By default it's [Online, PLAYING on {Server Count} servers]. About the token, don't worry, I don't get this. Then, run `node index.js`, and your bot is up and running!

You can check the commands folder for some commands, and a template to make your own commands! You can access the database using `client.db` (it uses [quick.db](https://npmjs.com/package/quick.db)).
