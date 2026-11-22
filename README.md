# Pulse Web

Offline-first web app version of Pulse. Add it to your iPhone home screen and it opens full-screen like a native app.
No Apple account, no server, no build step: 3 static files + icons.

Your data stays on the phone (localStorage). Back up with ⚙︎ → Export now and then.

## Put it online (GitHub Pages, free, ~3 min)
1. github.com → New repository → name `pulse` → Public → Create.
2. "uploading an existing file" → drag in everything from this folder (index.html, manifest.webmanifest, sw.js, icons/) → Commit.
3. Settings → Pages → Source: Deploy from a branch → `main` / root → Save.
4. Wait ~1 min. Your app: https://YOUR-USERNAME.github.io/pulse/

## Install on iPhone
Open that link in Safari → Share → Add to Home Screen → Add.
Always open it from the home-screen icon (Safari and the icon keep separate data).

## Update
Replace index.html in the repo, and bump VERSION in sw.js. Open the app twice to load the new version.
