# GRE Flashcards

A free, no-install flashcard app with spaced repetition. It runs in the browser from a single file (`index.html`).

## Put it on GitHub Pages (about 5 minutes)

1. Create a free account at github.com and click **New repository**. Name it `gre-flashcards`, set it to **Public**, and create it.
2. Click **Add file > Upload files**, drag in `index.html` (and this README), then click **Commit changes**.
3. Open the repository's **Settings > Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, choose branch `main` and folder `/ (root)`, then Save.
4. After a minute your app is live at `https://YOUR-USERNAME.github.io/gre-flashcards/`. Open it on your phone and use "Add to Home Screen" for one-tap access.

## Using it

- **Study:** tap a card (or press Space) to reveal the meaning, then rate it Again / Hard / Good / Easy (keys 1-4). Harder cards come back sooner.
- **Add:** type your own words, or use **Data > Import** to paste or upload a CSV with columns `word, meaning, example, group`.
- **Data:** change the daily new-card limit, export cards, or back up and restore your progress.

## Important

Your progress is saved in each browser separately. It does not sync between your phone and laptop automatically. Use **Data > Export progress (JSON)** and import it on the other device when you want them to match.

To change the starter deck for everyone who opens your page, edit the `SEED` list at the top of the script in `index.html` directly on GitHub (pencil icon). Each line is `word|meaning|example|group`.
