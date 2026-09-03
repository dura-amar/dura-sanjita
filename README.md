# dura-sanjita

Portfolio website for Sanjita Dura.

## Run locally

This is a static site. Serve this directory locally instead of opening
`index.html` with a `file://` URL:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000). YouTube embeds
require an HTTP Referer and will show Error 153 when the page is opened directly
from the filesystem.

The included GitHub Actions workflow deploys pushes to `main` to GitHub Pages,
where the embeds receive the required HTTPS referrer.

## Content updates

Keep the following current in `index.html`:

- featured music and music videos in **Latest Music & Videos**;
- programs, awards, and notable appearances in **Journey & Highlights**;
- official social and booking links in **Bookings & Contact**.

Before publishing a new release, confirm its title, date, credits, cover art,
and official watch/listen URL. Use descriptive image alt text and add
`rel="noopener noreferrer"` to every external link that opens in a new tab.
