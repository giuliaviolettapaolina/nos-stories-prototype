# NOS Stories – video page prototype

A responsive prototype of a NOS Stories video page with a clickable, auto-following transcript.

**Live:** `https://<your-username>.github.io/<repository-name>/`

## Files to upload

| File | What it is |
|---|---|
| `index.html` | The page (structure + a small script for the player and transcript) |
| `styles.css` | All styling, incl. desktop / tablet / mobile breakpoints |
| `video-github.mp4` | The video (720×1280, H.264, ~7 MB, optimised for streaming) |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is |
| `README.md` | This file |

`video.mp4` and `video-web.mp4` are not needed on GitHub.

## Publish on GitHub Pages

1. Create a new repository on GitHub (e.g. `nos-stories-prototype`). GitHub Pages on a free account requires it to be **Public**.
2. Click **Add file → Upload files** and drag in the files listed above.
   On a Mac, press `Cmd + Shift + .` in Finder to show the hidden `.nojekyll` file.
3. Click **Commit changes**.
4. Go to **Settings → Pages**. Under *Build and deployment* choose **Deploy from a branch**, branch **main**, folder **/ (root)**, and click **Save**.
5. After a minute or two the page is live at `https://<your-username>.github.io/<repository-name>/`.

To update later, upload the changed file again via **Add file → Upload files**.

## Notes

- Thumbnails and the Inter font load from the internet (images.cdn.nos.nl and Google Fonts).
- Effra is used when installed on the viewer's device; otherwise Inter.
- The video and thumbnails are NOS content. A public repository is visible to anyone, so check internally before sharing the link widely.
