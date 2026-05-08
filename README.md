# DonutStats Player Search

A lightweight Chrome/Edge extension for looking up public DonutSMP player stats from the browser toolbar.

## Features

- Searches DonutStats by Minecraft username.
- Shows a compact player summary in the popup.
- Keeps recent searches for quick repeat lookups.
- Supports favorites for players you check often.
- Caches recently fetched pages while the popup is open.
- Times out slow DonutStats requests instead of leaving the popup stuck.

## Install Locally

1. Open `chrome://extensions` or `edge://extensions`.
2. Turn on `Developer mode`.
3. Choose `Load unpacked`.
4. Select this folder:

```text
C:\Users\aaron\Documents\projects\Extensions\DonutStatsExtension
```

## Usage

1. Click the extension icon.
2. Enter a valid Minecraft username.
3. Press the search button or hit `Enter`.
4. Use favorites or recent chips to reopen previous searches.

## Permissions

- `storage`: saves recent searches and favorites locally in your browser.
- `https://donutstats.org/*`: reads public DonutStats player pages.

## Development

- `manifest.json` defines the extension metadata and permissions.
- `popup.html` contains the popup structure.
- `popup.css` handles the popup styling.
- `popup.js` fetches DonutStats pages, parses stats, and manages local storage.

This is an unofficial extension and is not affiliated with DonutStats, DonutSMP, Mojang, or Microsoft.
