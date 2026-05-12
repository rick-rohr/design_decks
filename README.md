# Design Decks

Presentations and design reviews for the Gymondo team.

**Live site:** https://rick-rohr.github.io/design_decks/

## How it works

- `index.html` is the landing page that lists every deck.
- Each deck is a single `.html` file in this folder.
- Anything you push to the `main` branch goes live on the web automatically.

## Adding a new deck

1. Drop the new `.html` file into this folder (next to `index.html`).
2. Open `index.html` and copy one of the existing `<a class="deck">…</a>` blocks. Paste it just below, then change:
   - the `href="..."` to your new file's name
   - the `<img src="thumbs/...">` to point at your thumbnail (or leave it pointing at a non-existent file — the card auto-falls-back to text-only)
   - the title, description, and "Deck 0X" number
3. Commit and push to `main` (or just upload the files in the GitHub web UI — drag and drop works).
4. Wait ~1 minute and refresh the live site.

## Thumbnails

Card thumbnails live in `/thumbs/`. To add one:

1. Take a screenshot of the deck — the hero usually works best. Aim for 16:10 ratio, ~1600×1000px, PNG or JPG.
2. Save it as `thumbs/<short-name>.png` (e.g. `thumbs/program-detail.png`).
3. Upload via the GitHub web UI (drag and drop into the `thumbs/` folder works).

If a thumbnail is missing or fails to load, the card falls back to its text-only layout automatically — no broken images.

## First-time setup (one-click, in GitHub)

To publish the site:

1. Go to https://github.com/rick-rohr/design_decks/settings/pages
2. Under **Source**, choose **Deploy from a branch**.
3. Set **Branch** to `main` and **Folder** to `/ (root)`. Click **Save**.
4. Wait about a minute. Your site will be live at https://rick-rohr.github.io/design_decks/
