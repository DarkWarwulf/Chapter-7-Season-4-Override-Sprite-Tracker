# ⚡ Override Sprite Tracker — Chapter 7 Season 4

A Fortnite-styled web app for tracking the **Chapter 7 Season 4 "Override"** Sprites you've caught and the level you've upgraded each one to. Companion to the [Season 3 tracker](https://darkwarwulf.github.io/Fortnite-Sprite-Tracker/) — this one is a **separate app** for the new season, with its own saved collection.

- **36 sprites** across 12 creatures (Jackrabbit, Shadow, Bush, Tails, Killswitch, Adventure, Klombo, Jonesy, Sonic, Crown, 8-Bit, Storm Scout), each with **base / Gold / Cheat Master** variants.
- **33 released** now; Storm Scout (3) shows under **Show Unreleased** until it drops.
- Set each sprite's level **1–5** — Level 5 is **Mastered** 👑. Click a sprite's picture to quickly toggle owned/not-owned.
- Live **Owned** and **Mastered** completion rings, filters (status + rarity), instant search.
- Card backgrounds, rarity pills, and glows mirror fortnite.gg — including the new green **Cheat Master** theme.
- **Saves automatically** in your browser and reappears every visit. Each visitor gets their own private tracker. **Export / Import** a backup code to move it between devices.

This tracker's saves are **independent** from the Season 3 tracker (separate storage key `fnSpriteOverride:v1`), so collecting here never touches your old collection.

---

## 🚀 Deploy to GitHub Pages
1. Create a new **public** repo (e.g. `Chapter-7-Season-4-Override-Sprite-Tracker`) at https://github.com/new — no README/.gitignore.
2. Push this folder to it (Git, since it has more than 100 files):
   ```powershell
   cd "C:\Claude\Chapter-7-Season-4-Override-Sprite-Tracker"
   git init -b main
   git add -A
   git commit -m "Override Sprite Tracker: initial commit"
   git remote add origin https://github.com/DarkWarwulf/Chapter-7-Season-4-Override-Sprite-Tracker.git
   git push -u origin main
   ```
3. **Settings → Pages → Deploy from a branch → `main` / `/ (root)` → Save.**
4. Live at `https://darkwarwulf.github.io/Chapter-7-Season-4-Override-Sprite-Tracker/`.

## 🗂 Structure
```
index.html   styles.css   app.js   data.js   .nojekyll
assets/
  sprites/   – 36 sprite icons (161.webp … 196.webp, by sprite id)
  img/       – logo, favicons, background
  data/      – sprites.raw.json (source data, for reference)
```

*Fan-made tracker. Sprite names and artwork are the property of Epic Games. Not affiliated with or endorsed by Epic Games. Sprite data referenced from fortnite.gg.*
