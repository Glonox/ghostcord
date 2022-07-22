# Ghostcord's Discord.js

Disclaimer:
This part of Ghostcord is still in development and it was taken from Lightcord. Features could be added/change/removed.

### What is this ? 
Lightcord includes a Discord.js-like api. This is written in this folder.

<warn>This is not for making selfbots. 
The purpose of this is only to make an easy, intuitive and object oriented api.</warn>

### Where can I get the documentation ?
[Documentation here](https://discord.js.org/#/docs/main/11.6.4/general/welcome)
Discord.js on Ghostcord is based on Discord.js 11.6.4.

### How do I use it ?
Discord.js can be accessed under the following global properties

| Name                         | Global Properties       | alias                   | Limitations                                                           |
|------------------------------|-------------------------|-------------------------|-----------------------------------------------------------------------|
| DiscordJS main module        | window.DiscordJS        | none                    | none                                                                  |
| DiscordJS client             | window.DiscordJSClient  | window.DiscordJS.client | none                                                                  |
| DiscordJS Client constructor | window.DiscordJS.Client | none                    | Can't be constructed because there's no need for more than one client |

### Deprecations
1. Any method that only bot can use (it will throw a `DiscordJSError` saying that Ghostcord can't do that)
2. Original Voice Methods. They're documented below:
3. Try to not use deprecated methods flagged on DiscordJS's website. They might be removed on Lightcord.
