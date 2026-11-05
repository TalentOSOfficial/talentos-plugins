# TalentOS plugins

Plugins that bring your AI agents into your [TalentOS](https://talentos.so) workspace as teammates.

| Plugin | Works in | What it does |
| --- | --- | --- |
| [`talentos`](talentos/) | Grok Bot | Grok Bot joins your TalentOS rooms as your teammate. It reads and posts in rooms, makes files there, searches team memory and uses your team's Skills. |

TalentOS also connects to ChatGPT and Claude.ai. Those connections need no files from this repository; the steps are below.

## Connect Grok Bot

TalentOS is not listed in **Connect apps** yet. This repository holds the plugin submitted for review.

1. In Grok Bot, open **Connect apps**, search **TalentOS** and click **Connect**.
2. On the TalentOS page, under **Where are you connecting from?**, pick **Grok Bot**. If the page lists rooms, tick the ones it may join. Then click **Allow**.

No key or address is typed. To disconnect, remove the Grok Bot in TalentOS under **Your agents**, or remove TalentOS from Grok Bot's **Connect apps**.

## Connect ChatGPT

TalentOS is not listed in ChatGPT's plugin directory yet. Once it is:

1. In ChatGPT, open the plugin directory, search **TalentOS** and click **Connect**.
2. Sign in to TalentOS. Tick the rooms ChatGPT may join, then click **Allow**.

ChatGPT joins your workspace as your teammate, for example "Olivia's ChatGPT". Ask it to catch up on a room, post an update, or write a document, deck or spreadsheet in a room.

## Connect Claude.ai

TalentOS is not listed in Claude's connector directory yet. Once it is:

1. In Claude, open **Settings → Connectors**, find **TalentOS** and click **Connect**.
2. Sign in to TalentOS. Tick the rooms Claude may join, then click **Allow**.

Claude joins your workspace as your teammate, for example "Olivia's Claude.ai". Ask it the same things as ChatGPT.

## What a connected ChatGPT or Claude.ai can do

- Read the rooms you ticked: messages, threads, files and comments.
- Post in those rooms and make documents, decks, spreadsheets and web apps there, when you ask. Everything it makes is marked as made by your ChatGPT or Claude.ai.
- Read your Skills, your memory, the names of your connected apps and your Routines' names and schedules.

It never sees more than you can. It can't run your Routines, ask your Talent or use your connected apps.

To disconnect, open TalentOS, go to **Settings → Agents**, choose the teammate and click **Disconnect**. Your workspace admin can turn ChatGPT, Claude.ai or Grok Bot off for everyone under **Admin settings → General → Outside agents**.

## Support

- Help: [support@talentos.so](mailto:support@talentos.so)
- Privacy policy: https://talentos.so/legal/privacy

## License

The files in this repository are under the [MIT License](LICENSE). The TalentOS name and logo are trademarks of Talent Operating Systems Corp. and are not licensed for other use.
