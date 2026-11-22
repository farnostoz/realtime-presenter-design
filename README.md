# Church Controller — Number & Verse prototype

A static, interactive prototype of the church presentation controller (current prototype: **v1.5**).

## Try it

Once GitHub Pages is enabled, visit:

`https://OWNER.github.io/church-controller-prototype/`

Replace `OWNER` with your GitHub username or organization. The URL remains the same when `index.html` is updated.

## Important: prototype only

- **Does not control real church displays or projectors.** All operations are simulated in the browser.
- Uses a **static camera image**, not a VDO.Ninja stream.
- Uses demonstration song and bookmark data, not a live church catalog.
- LIVE state sharing between independent controllers is simulated; real WebSocket synchronization belongs in the implementation.
- No backend, accounts, or build tooling are required.

## Publishing with GitHub Pages

1. Create a **public** GitHub repository named `church-controller-prototype`.
2. Upload the **contents** of this folder to the repository root (`index.html`, `README.md`, `.nojekyll`).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main**, folder **/(root)**, then **Save**.
6. After GitHub finishes publishing, use the Pages URL displayed in the settings.

Do not upload the ZIP itself as the site: extract it and upload the files.

## Updating the prototype

- Replace `index.html` with the new complete HTML prototype.
- Commit the change to `main`; GitHub Pages republishes the page automatically.
- Keep the file name `index.html` and the repository name the same so that the team URL does not change.
- Optionally tag milestones (`v1.5`, `v1.6`, etc.) for reproducible review.

## Public-content warning

This repository and the deployed site are public. The HTML currently embeds a church-interior camera still as a base64 image, so the photo is public too. Review the image and any future test data before publishing. Never put operational passwords, device access tokens, private stream URLs, or sensitive production details in this repository.

## Feedback

Share the GitHub Pages URL with organists. Capture usability findings as repository issues or in your usual team feedback channel. In particular, test **OFF → +1**, entering a new song, clearing a draft, returning to LIVE, and bookmarks on actual tablets.
