<h2 align="center">
    ─「 TG-WhatsApp 」─
</h2>

> Get WhatsApp Messages On Telegram And Reply From Telegram!

<h3 align="center">
    ─「 Features 」─
</h3>

[X] Realtime delivery of messages from whatsapp to telegram and vice-versa.

[X] Supports both personal messages and group messages.

<h3 align="center">
    ─「 Why This Exists? 」─
</h3>

Being an active telegram user and a person who don't like to use Whatsapp, but still wants to keep connected with friends.
A solution for the same would be using a bridge between both the apps. Yes, I know this already [exists](https://github.com/WhatsGram/WhatsGram), but unfortunately its not handling the group messages like what i was expecting. So I decided to create a similar one with multidevice support from [Tuhin's WhatApp userbot](https://github.com/tuhinpal/WhatsBot). In short you can call it as a fork of both [WhatsGram](https://github.com/WhatsGram/WhatsGram) and [WhatsBot](https://github.com/tuhinpal/WhatsBot). ~~I know , you know a better name , but still i love to call it as a fork. :/~~

<h3 align="center">
    ─「 Deployment 」─
</h3>

<p align="center"><a href="https://dashboard.heroku.com/new?template=https://github.com/AL3X-Github/TG-WhatsApp"> <img src="https://img.shields.io/badge/Deploy%20On%20Heroku-black?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>

<h3 align="center">
    ─「 Config Variables 」─
</h3>

- `BOT_TOKEN` Bot token from [@BotFather](https://telegram.dog/BotFather)
- `MONGODB_URL` MongoDB connection string.
- `OWNER_ID` Your telegram ID.
- `SESSION_KEY` Password for your session file.
- `SESSION_URL` Direct link to your WhatsApp session file.
- `PM_REPLY` Make it `false` if you don't want bot to send an automated message when someone DM for first time.

For detailed instructions on how to deploy and run your own bot, refer [this wiki page of WhatsBot](https://github.com/tuhinpal/WhatsBot/wiki)

- After succesfull deployment,add the telegram bot to telegram group and whatsapp user to whatsapp group and send `/connect` in your telegram group or `!connect <telegram chat id>` in your whatsapp group to connect both the group.
- To disconnect a chat, use `/disconnect` in your telegram chat.


<h3 align="center">
    ─「 How It Works 」─
</h3>

- Open whatsapp web in server using puppeteer
- Listen messages and take action.
- Using telegraph-js to connect with telegram and sends messages to connected chats.

<h3 align="center">
    ─「 Credits 」─
</h3>

- [Whatsapp Web JS](https://github.com/pedroslopez/whatsapp-web.js/) - Whatsapp Web API Client
- [telegraf](https://github.com/telegraf/telegraf) - Telegram Bot Framework for Node.js
- [WhatGram](https://github.com/WhatsGram/WhatsGram) - Many of the functions related to telegram are taken from here.
- [WhatsBot](https://github.com/tuhinpal/WhatsBot) - Modular Userbot for Whatsapp

<h3 align="center">
    ─「 License 」─
</h3>

- This Project Is [Apache-2.0](https://github.com/AL3X-Github/TG-WhatsApp/blob/main/LICENSE) Licensed

<h3 align="center">
    ─「 Support & Updates  」─
</h3>

<div align="center">

<p align="center"><a href="https://github.com/AL3X-Github"><img alt="Website" src="https://img.shields.io/badge/ㅤPowered By I𝗓υɱi 和泉ㅤ-blue"></a></p>


![Support Cover](https://github.com/AL3X-Github/Resources/blob/main/Photos/Support.png)

</div>

<div align="center">


[![Telegram](https://img.shields.io/badge/Group-%232C3454?style=for-the-badge&logo=telegram&logoColor=white)](https://telegram.dog/MaximXGroup) [![Telegram](https://img.shields.io/badge/Channel-%232C3454?style=for-the-badge&logo=telegram&logoColor=white)](https://telegram.dog/MaximXChannels)

[![ForTheBadge built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg)](https://github.com/AL3X-Github)

<h6>

**Copyright 2022 :** [**Iᴢυɱi 和泉**](https://telegram.dog/MaximXRobot) 

</h6>
</div>

