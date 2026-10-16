# Character Auction — v0.1.0

A dark-mode bilingual (English/German) front-end prototype for a character auction game.

## Files
- `index.html` — page structure and dialogs
- `style.css` — responsive dark UI
- `app.js` — navigation, language switcher, demo groups/presets and local lobby preview

## Run locally
Open `index.html` in a modern browser, or use the Live Server extension in Visual Studio Code.

## Current prototype limitations
- Groups and presets are stored in this browser's `localStorage`, not in a cloud database.
- Lobby creation is only a local preview. Lobby codes are not connected to other players.
- There is no real sign-up/login yet. Do not enter real passwords.
- Character image uploads and the auction logic are not implemented yet.

## Planned next step
Create a Supabase project, add authentication and database tables with Row Level Security (RLS), then connect this front end. Keep the Supabase `anon`/publishable key in client config only; never put a service-role key in browser code.
