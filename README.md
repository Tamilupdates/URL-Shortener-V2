# URL Shortener Bot V2

<p align="center">

![Fork](https://img.shields.io/github/forks/tamilupdates/URL-Shortener-V2?style=for-the-badge)
![Stars](https://img.shields.io/github/stars/tamilupdates/URL-Shortener-V2?color=%23&style=for-the-badge)
![License](https://img.shields.io/github/license/tamilupdates/URL-Shortener-V2?style=for-the-badge)
![Issues](https://img.shields.io/github/issues/tamilupdates/URL-Shortener-V2?style=for-the-badge)

</p>

---

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Tamilupdates/URL-Shortener-V2">
    <img src="https://i.ibb.co/1mwchh9/Screenshot-2022-07-08-at-11-06-34-AM.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">URL Shortener Bot V2</h3>

  <p align="center">
    A Shortener and Convertor Bot
    <br />
    ·
    <a href="https://github.com/Tamilupdates/URL-Shortener-V2#features">Features</a>
    ·
    <a href="https://github.com/Tamilupdates/URL-Shortener-V2#deploy">Deploy</a>
    ·
    <a href="https://github.com/Tamilupdates/URL-Shortener-V2#required-variables">Variables</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#deploy">Deploy</a></li>
    <li><a href="#description">Description</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#commands">Commands</a></li>
    <li>
        <a href="#about">About</a>
        <ul>
        <li><a href="#features">Features</a></li>
        <li><a href="#required-variables">Required Variables</a></li>
        <li><a href="#optional-variables">Optional Variables</a></li>
      </ul>
      </li>
    <li><a href="#tech-stack">Tech Stack</a></li>
    <li><a href="#disclaimer">Disclaimer</a></li>
  </ol>
</details>

---

## Deploy

You can deploy this bot anywhere.

|                                                        | Name                 | Deploy                                                                                                                                                                                                                             |
| ------------------------------------------------------ | -------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Replit](assets/img/replit.jpg)                       | Replit (Recommended) | [See Guide](/guides/replit.md)                                                                                                                                                                                                     |
| [![Heroku](assets/img/heroku.png)](https://heroku.com) | Heroku               | [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Tamilupdates/URL-Shortener-V2)                                                                                      |
| ![Koyeb](assets/img/koyeb.png)                         | Koyeb                | [![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/apps/deploy?type=git&repository=tamilupdates/url-shortener-v2&name=url-shortener-v2&run_command=python3%20-m%20main&branch=main) |
| ![VPS](assets/img/vps.png)                             | VPS                  | [See Guide](/guides/vps.md)                                                                                                                                                                                                        |

## Description

> **Now this bot can be used by users also. Only admin has access to channel support. Bot Owner API will be used in channel post converting. You can restrict users from using this bot by setting env `IS_PRIVATE` to True**

**Just Send Any Link To Short. It Will Short Link or Save it to your MDisk Account**

## Usage

***How To Use Me!?***

- -> Send any link or post of links

- -> Add me to your channel as admin with full previlages to convert channel's post

> For more information about usages, see the [documentation](https://github.com/Tamilupdates/URL-Shortener-V2/wiki/Usage)

## Commands

```
start - start it
help - help Command
about - about Command
method - to set your preferred method
shortener_api - set shortener api
mdisk_api - set mdisk api
header - set header
footer - set footer
username - set username to replace others
banner_image - set banner image
me - know about you
shortener_site - change shortener site
include_domain - set include domain
exclude_domain - set exclude domain
stats - Stats of the server and bot

Admin only use commands

batch -100XX - to convert link for multiple posts
logs - Send the log messages
restart - restart / re-deploy the server
ban - to ban users
unban - to unban users
info - get user info
```

## About

### Features

- [x] Shortener
- [x] Mdisk Convertor
- [x] Channels Support
- [x] Batch Support
- [x] Multiple Methods Available
- [x] Bypass Shortener Links
- [x] Hyperlink Support
- [x] Request Features

### Required Variables

| Variable Name              | Value                                                                                                                                                          |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `API_ID` (required)        | Telegram api_id obtained from <https://my.telegram.org/apps>.                                                                                                  |
| `API_HASH` (required)      | Telegram api_hash obtained from <https://my.telegram.org/apps>.                                                                                                |
| `BOT_TOKEN` (required)     | Create a bot using @BotFather, and get the Telegram API token.                                                                                                 |
| `ADMINS`                   | ID of Admins. Separate multiple Admins by comma                                                                                                                |
| `OWNER_ID` (required)      | ID of Owner.                                                                                                                                                   |
| `DATABASE_URL` (required)  | [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo) |
| `DATABASE_NAME` (required) | Name of the database in [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)                                     |

### Optional Variables

> For more information about optional variables see the [wiki documentation](https://github.com/Tamilupdates/URL-Shortener-V2/wiki/About#optional-variables)


## Tech Stack

**Language:** [Python](https://www.python.org/) 3.10.2

**Library:** [Pyrogram](https://github.com/pyrogram/pyrogram) 2.0.30
