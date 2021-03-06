# hello-bot
simple bot that says hello and MP rules.
Built with [nodejs](https://nodejs.org/en/) and the [discordjs](https://discord.js.org/#/) library.

### Setup
 - You need `git` and `nodejs` on your system
 - create a `user bot`
    It will have a `bot ID` and a `bot token`.

    You can find all that on the discord website :

    [https://discordapp.com/developers/applications/me](https://discordapp.com/developers/applications/me)


 - Then authorize your bot to your discord with this link :

    `https://discordapp.com/oauth2/authorize?&client_id=BOT_ID&scope=bot`

    (where `BOT_ID` is replaced by your bot id)

 - Find your id by right-clicking yourself and click `copy ID` in the menu

 - You must then create a config file like so :

    ```js
    // config.json
    { "botToken": "my.bot.token", "adminId": "245646465465" }
    ```
    (where `my.bot.token` is replaced by your bot token, and `adminId` is your personnal discord id).

:warning: _your bot token is private, don't share it_


### Install
```shell
# clone the repo and go into the folder
git clone https://github.com/kigiri/hello-bot && cd hello-bot

# install the required modules (discord.js here)
npm install

# start the bot
node bot

```


### Video explaining the code (in french)
[![youtube video link](http://img.youtube.com/vi/vpDytuYdK4w/maxresdefault.jpg)](https://www.youtube.com/watch?v=vpDytuYdK4w)