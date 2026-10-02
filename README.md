# Letterboxd Services

Quickly search for a film from its Letterboxd page. This userscript adds links to external search services using the film’s title and release year.

## Search services

- BT4G
- 1337x
- LimeTorrents
- Nyaa
- YouTube

Each link opens in a new tab.

## Install

1. Install a userscript manager, such as Tampermonkey or Violentmonkey.
2. Open the [raw userscript](https://raw.githubusercontent.com/wishofkazdel/letterboxd-services/refs/heads/main/letterboxd-services.user.js).
3. Follow your userscript manager’s prompt to install it.

## Display modes

Use the userscript manager’s menu to choose a display mode:

- **Combine Services:** show the added links alongside Letterboxd’s existing services.
- **External Services Only:** show the added external links without Letterboxd’s existing service entries.
- **Disabled":** don’t add the external links.

Your selected mode is saved by the userscript manager and takes effect after the page reloads.

## Permissions

The script runs on Letterboxd film pages. It uses userscript-manager storage to remember your selected display mode, and its links take you to the corresponding external search sites.
