# ⚔️ RLCraft Server

Live status page for RLCraft hardcore survival server.

## Features

- 🟢 Real-time server status (online/offline)
- 🗺️ Live world map with player positions (Dynmap)
- 👥 Online players list with skin avatars
- 📋 How-to-join guide
- 📜 Server rules
- 📱 Mobile-friendly

## Powered by

- [mcsrvstat.us](https://mcsrvstat.us) — Server status API
- [Dynmap](https://github.com/webbukkit/dynmap) — Live world map
- [Crafatar](https://crafatar.com) / [mc-heads.net](https://mc-heads.net) — Player avatars

## Setup

Edit `index.html` and update the CONFIG block:

```javascript
const SERVER_ADDRESS = "your-server.gl.joinmc.link:25565";
const DYNMAP_URL = "http://your-dynmap.gl.joinmc.link:51235";
```

Then deploy via GitHub Pages, Netlify, Vercel, or Cloudflare Pages.
