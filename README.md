# Usage
Before editing this source code, in order to follow GPL license, make sure to fork it and mention that it is open source please.

**Requirements**
- node.js
- npm

**Setup**
1. clone this repository / download it
2. run `npm i` to install the required dependencies
3. edit `config.js` with your token and prefix
4. run `node index.js` :D

# How does it work?

The bot is creating an array which contains all the `GuildMember` objects. Then it scrapes the user ID of each `GuildMember` object, and sends a private message to it.
Pretty simple :p

Note that the bot needs admin permissions to work the right way. If you face bugs, check your server permssions before opening github issues please <3
