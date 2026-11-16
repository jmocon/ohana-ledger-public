# OhanaLedger website

The public website for **OhanaLedger**, an Android app that keeps a
household's money and the family's health records together on one phone.
There is no account and no server, and backups are encrypted.

This repository holds only the website. The app's source code is not here.

## Pages

| Page | Address |
|---|---|
| Home | https://jmocon.github.io/ohana-ledger-public/ |
| Privacy policy | https://jmocon.github.io/ohana-ledger-public/privacy/ |
| User guide | https://jmocon.github.io/ohana-ledger-public/guide/ |

## Contact

Questions about the app or its privacy policy:
[jumariegabotmocon@gmail.com](mailto:jumariegabotmocon@gmail.com)

## How the site is built

Plain HTML and CSS with no build step, served by GitHub Pages from the root
of `main`. Fonts come from Google Fonts. `.nojekyll` tells Pages to serve the
files exactly as they are.

```
index.html          home page
privacy/index.html  privacy policy
guide/index.html    user guide
images/             app icon, share image and store screenshots
```

To change a page, edit its HTML and push to `main`. Pages republishes it
within a minute or two. When the privacy policy changes, update the
effective date at the top and in its footer as well.
