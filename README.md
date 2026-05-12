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
   - the title, description, and "Deck 0X" number
3. Commit and push to `main` (or just upload the files in the GitHub web UI — drag and drop works).
4. Wait ~1 minute and refresh the live site.

## First-time setup (one-click, in GitHub)

To publish the site:

1. Go to https://github.com/rick-rohr/design_decks/settings/pages
2. Under **Source**, choose **Deploy from a branch**.
3. Set **Branch** to `main` and **Folder** to `/ (root)`. Click **Save**.
4. Wait about a minute. Your site will be live at https://rick-rohr.github.io/design_decks/
