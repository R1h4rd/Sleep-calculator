# Sleep Cycle Calculator

A small offline-capable web app (PWA) that suggests bedtimes and wake-up times based on 90-minute sleep cycles.

- **I'm going to bed at…** – pick a bedtime, get wake-up times
- **I'm going to bed now** – wake-up times from the current time
- **I need to wake up at…** – pick a wake-up time, get bedtimes

Time to fall asleep (default 15 min) and cycle length (default 90 min) can be adjusted under "Adjust settings".

## Host on GitHub Pages

1. Create a new repository and upload all files in this folder (keep the `icons` folder).
2. In the repo, go to **Settings → Pages**, set **Source** to "Deploy from a branch", choose `main` and `/ (root)`, and save.
3. After a minute the app is live at `https://<your-username>.github.io/<repo-name>/`.

## Install on your phone

- **Android (Chrome):** open the link, then menu ⋮ → **Install app** / **Add to Home screen**.
- **iPhone (Safari):** open the link, tap Share → **Add to Home Screen**.

Open it once while online; after that it works with no connection.

## Updating

After changing any file, bump the version in `sw.js` (`sleep-calc-v1` → `sleep-calc-v2`) so installed copies download the new files. The update shows up the second time you open the app.
