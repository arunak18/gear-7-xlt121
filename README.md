# Gear 7 — Turf Cricket Crew

A one-page, Straw-Hat-themed website for the **Gear 7** turf cricket team: a night-voyage hero, a wanted-poster crew roster, a treasure-map fixture log, and a trophy chest.

Everything lives in a single file — `index.html` — with all fonts (Pirata One, Anton, Arvo) inlined as base64, so it works standalone with no build step and no external requests.

## Preview it locally

Just open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Import/push this folder to a new GitHub repository.
2. In the repo, go to **Settings → Pages**.
3. Under "Build and deployment", set the source to **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Save — the site will be live at `https://<your-username>.github.io/<repo-name>/`.

## Content to personalize

The roster, fixtures, trophies, and contact details in `index.html` are placeholders. Search for and replace:

- Player names/nicknames in the "Wanted" crew section (e.g. `Arjun Menon`, `Kabir Sheikh`)
- Fixture dates/opponents/venues in the "Voyage Log" section
- Trophy history in the "Treasure Chest" section
- Contact info in the "Join the Crew" section (`gear7turfcc@gmail.com`, Instagram/WhatsApp links)

## Credits

Design and original SVG crest built for this project — not affiliated with Toei Animation or Shueisha.
