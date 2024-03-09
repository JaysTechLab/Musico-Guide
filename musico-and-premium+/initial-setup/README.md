---
description: >-
  This page description provides a comprehensive overview of the setup process
  for Musico, guiding users through each step to ensure a smooth and customized
  experience.
cover: >-
  ../../.gitbook/assets/untug_httpss.mj.runfsdSeUbR5oY_httpss.mj.run_y6_rFYy_ro_httpss._683a7f8b-d28c-4828-8a39-78d1a5d9df5a.png
coverY: -36
layout:
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 🔧 Initial Setup

<details>

<summary>Step 1: <strong>Adding Musico to Your Server</strong></summary>

Begin by inviting Musico to your Discord server. Simply use the provided [invite link](https://discord.com/oauth2/authorize?client\_id=810540985032900648\&permissions=2150754416\&scope=bot), authorize Musico to access your server, and select the appropriate permissions.

[https://discord.com/oauth2/authorize?client\_id=810540985032900648\&permissions=2150754416\&scope=bot](https://discord.com/oauth2/authorize?client\_id=810540985032900648\&permissions=2150754416\&scope=bot)

</details>

<details>

<summary>Step 2: Adding a custom music channel</summary>

After inviting Musico to your server, run the `.setup` command to initiate the setup process & add the custom #musico-request channel. In here you can complete the rest of the setup and start listening to music with Musico!

</details>

<details>

<summary>Step 3: <strong>Setting Custom Prefix (optional)</strong></summary>

The prefix in the context of Discord bots refers to the character or characters that users need to type before a command to invoke the bot's functionality. It helps distinguish bot commands from regular messages in a server. For example, if a bot's prefix is set to `.` and there's a command to play music called "play", users would type `.play` to execute that command.

_In essence, the prefix serves as a signal to the Discord server that the following text is a command intended for the bot to interpret and act upon. It's customizable, allowing server administrators to set it to their preferred character or string to avoid conflicts with other bots or server commands._

Use the `.set-prefix` command and choose your desired prefix. For example

```
.set-prefix !
```

</details>

<details>

<summary>Step 4: <strong>Configuring Text and Voice Channels</strong></summary>

Determine which text channels Musico can interact with and specify the voice channels where it's allowed to play music. This ensures seamless integration without cluttering unrelated channels.

For channel selection use `.text-channels <channel name>`

For voice channels use `.set-voice <channel name>`

</details>
