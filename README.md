# Web Linux 2.0

Web Linux is a browser-based desktop environment built with HTML, CSS and JavaScript. It includes a desktop, taskbar, window manager, file manager, browser, media player, settings, games and optional AI assistance.

## Run locally

Open `index.html` in a browser, or serve the repository with a local web server:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Features

- Windows 7-inspired Aero desktop and window styling
- Automatic guest session; no account or password setup
- Draggable and resizable application windows
- Start menu, taskbar, notifications and quick settings
- File manager and text editor
- Browser and local media player with playlists
- Themes, wallpapers and desktop customization
- Built-in tools, games and app store
- Optional AI assistant and OS automation with user approval

## Deploy

You can deploy this repository with [Vercel](https://vercel.com/) or [Netlify](https://www.netlify.com/).

## Project details

Everything runs client-side in the browser. Browser storage is used for local preferences and files. Some online features require an internet connection.

## Credits and license

Web Linux is a modified fork of NautilusOS. This project retains the original upstream attribution and license notices as required by the applicable AGPL-3.0 license. See the repository's license files for the full terms.

