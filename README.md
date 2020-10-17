# Discord Application Tutorial
A quick and short tutorial on how to create a discord bot application, and how to navigate through the discord developer panel to gain information about your bot.

## 🏃 Creating An Application
Create the application in order to have your bot profile and information.

1. Go to the discord [developer application page](https://discord.com/login?redirect_to=%2Fdevelopers%2Fapplications).
2. Login to your discord account.
3. Click the **New Application** button at the top right.
4. Enter the name you would like to give your bot.
5. Lastly, click the create button. And now you should have an application!

## 🤖 Creating The Bot
Now that you have your application, you can create the actual robot!

1. Click your new application pad.
2. Open the **Bot** tab to the left.
3. Lastly, click the **Add Bot** button to the right.

## ❓ Frequently Asked Questions
These questions may come up at a certain point, so might as well take a look right?

### Where is my bot token?
By the end of this, the bot token will be copied to your clipboard.

1. Go to the discord [developer application page](https://discord.com/login?redirect_to=%2Fdevelopers%2Fapplications).
2. Click the application pad you want.
3. Open the **Bot** tab to the left.
4. Click the **Copy** button under *Click to Reveal Token*.

### How do I change my bot token?
This will make all past tokens created for your bot dysfunctional.

1. Go to the discord [developer application page](https://discord.com/login?redirect_to=%2Fdevelopers%2Fapplications).
2. Click the application pad you want.
3. Open the **Bot** tab to the left.
4. Click the **Regenerate** button under *Click to Reveal Token*.

### Where is my application/client ID?
By the end of this, the application ID will be copied to your clipboard.

1. Go to the discord [developer application page](https://discord.com/login?redirect_to=%2Fdevelopers%2Fapplications).
2. Click the application pad you want.
3. Click the **Copy** button under *CLIENT ID*.

### Where is my bot invite link?
By the end of this, the bot invite link will be copied to your clipboard.

1. Go to the discord [developer application page](https://discord.com/login?redirect_to=%2Fdevelopers%2Fapplications).
2. Click the application pad you want.
3. Open the **OAuth2** tab to the left.
4. Click the **bot** button under *Scopes*.
5. Scroll down, select all the bot permissions you need.
6. Click the **Copy** button to the right of the newly generated bot token.

## 💻 Hosting
This is a complete guide that will teach you the basics of hosting a discord javascript application.

### Prerequisites
* [**Linux Node.js**](https://github.com/nodesource/distributions#table-of-contents)
* [**Windows Node.js**](https://nodejs.org/en/download/)

### Windows Hosting
By the end of this tutorial, the bot should be online.

1. Create a file on your *desktop* with all the *bot files* in it.
2. Open the file, and copy the [navigation link](https://www.wikihow.com/Find-a-File%27s-Path-on-Windows).
3. Open a [command prompt](https://www.wikihow.com/Open-the-Command-Prompt-in-Windows).
4. Run the `cd <navigation link>` command to get into the directory.
5. Run the `npm install` command to install all the dependencies.
6. Run the `node .` command to turn the bot online.

### Linux Hosting
This tutorial is meant for people with a slight knowledge of how to use Ubuntu.

1. Create a file in any directory and import the bot files into it.
2. Change directory to the file you just created.
3. Run the `npm install` command to install the dependencies.
4. Run the `npm install --global pm2` command to install pm2 on the system.
5. Run the `pm2 start .` command to start the bot on the system.