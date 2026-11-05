# Adil Feroze, portfolio

My personal portfolio site: experience, 16 featured projects with detail dialogs and filters, and a list of every public repository.

It is a single static file with no build step and no dependencies. The only external request is the Archivo typeface from Google Fonts, with system fonts as a fallback.

## Run it

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Deploy it

Any static host works. On GitHub Pages, set **Settings, Pages, Deploy from a branch, main, / (root)**. On Vercel or Netlify, import this repository and leave the build command empty.

## Edit it

All content and styles are in `index.html`. Project cards are the `button.proj` elements, and each opens the `dialog` with the matching id.
