# HALO: Flashpoint Scorekeeper

**An unofficial fan-made scorekeeping tool for HALO: Flashpoint.**

A lightweight, responsive browser app for tracking Red Team and Blue Team victory points, rounds, and in-game achievements.

## Use the scorekeeper

Open the live GitHub Pages site once Pages has been enabled, or open `index.html` locally in a modern browser.

- Adjust each team's manual VP with the `+` and `−` controls.
- Increase or decrease the round with the round controls.
- Check an achievement for Red or Blue when that team earns it. Achievement VP is added automatically.
- Use **RESET MATCH** at the bottom to clear the current match. The app asks for confirmation first.

Match state is saved in the browser's local storage. It stays in that browser on that device; it is not synced between devices or users. Clearing browser site data may erase the saved match.

## Publish with GitHub Pages

1. Create a **public** GitHub repository (for example, `halo-flashpoint-scorekeeper`).
2. Extract this package and upload the contents of this folder to the repository's **root**. Make sure `index.html` is at the top level, not inside an extra nested folder.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then click **Save**.
6. Wait for the Pages deployment to finish. GitHub will show the published URL in the Pages settings.

For a project repository, the URL is usually:
`https://YOUR-USERNAME.github.io/halo-flashpoint-scorekeeper/`

## Project contents

- `index.html` — complete self-contained app. Styling, app logic, and the supplied logo image are embedded in this file.
- `.nojekyll` — tells GitHub Pages not to run Jekyll processing.
- `README.md` — project overview and publishing instructions.
- `NOTICE.md` — unofficial-project and intellectual-property notice.

## Version

Version **1.0** — initial public release.

## Feedback and contributions

You can use GitHub Issues to report bugs or suggest improvements. Please include your browser and device when reporting a problem.
