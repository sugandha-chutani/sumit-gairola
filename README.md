# Sumit &amp; Sugandha · Save the Date

A single-page save-the-date for our wedding on **24 February 2027**.

## Files


| File          | What it is                                                        |
| ------------- | ----------------------------------------------------------------- |
| `index.html`  | The whole page (all styles, scripts and photos are built in)      |
| `preview.jpg` | The illustrated card shown when the link is shared on WhatsApp/iMessage |
| `music.mp3`   | **Add this yourself**: the song that plays after the petal reveal |
| `.nojekyll`   | Tells GitHub Pages to serve the files as-is                       |


## Publish on GitHub Pages

1. Create a new repository on GitHub (e.g. `sugandha-sumit-wedding`). On a free plan it must be **Public** for Pages.
2. **Add file → Upload files**, drag in everything from this folder (plus your `music.mp3`), and commit to `main`.
3. Go to **Settings → Pages**. Under *Build and deployment*, pick **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After about a minute the site is live at `https://<your-username>.github.io/sugandha-sumit-wedding/`.

## After it's live

- **Link preview:** in `index.html`, change `content="preview.jpg"` in the `og:image` tag to the full URL, e.g. `https://<your-username>.github.io/sugandha-sumit-wedding/preview.jpg`. WhatsApp only shows images from full URLs.
- **Music:** the file must be named exactly `music.mp3` (lowercase) and sit next to `index.html`. If it is missing, the music button simply stays hidden.
- **Privacy:** the page asks search engines not to index it (`noindex`), but anyone with the link can open it.
- **Updating:** upload a new `index.html` over the old one; the site refreshes in a minute or two.

