# Discord Widget

This project provides a simple Discord widget that displays the number of online members in the squib_channel Discord server and a link to join the server. It is designed to be embedded in other websites using an iframe.

## Features

- Displays the number of online members in a Discord server.
- Provides a link to join the server.
- Automatically refreshes every 15 minutes.

## How to Embed in an iframe

_Use the following HTML code to embed the widget in your website:_

```html
<iframe
  src="https://squibchannel.github.io/discord-widget/"
  width="320"
  height="255"
  style="border: none; border-radius: 12px;" // throw in whatever styles you want
  title="Squib Discord Widget"
></iframe>
```

## Warning

Some browser extensions, such as ad blockers (e.g., uBlock Origin) or privacy tools (e.g., Privacy Badger), may block the Discord API call required to load the widget. If the widget does not load or displays an error, users may need to whitelist the following domains in their extension settings:

- `discord.com`
- `squibchannel.github.io`

This widget does not track users or collect any personal data. It only fetches publicly available information from the Discord API.
