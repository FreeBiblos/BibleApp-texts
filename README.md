# BibleApp-texts

Bible texts in many languages for the [FreeBiblos Bible app](https://bluesboy13.github.io/BibleApp/),
served by GitHub Pages and downloaded by the app only when a reader chooses that language.

`texts/index.json` lists them; each `texts/<id>.json.gz` is one Bible (gzip-compressed JSON in the
app's layout). They are built by `.github/workflows/build.yml` from [eBible.org](https://ebible.org)
using the app's converter (`tools/texts/build_ebible_all.py` in the app repo): one freely shareable
complete Bible per language, public domain first, otherwise the most literal freely licensed one.
Each text's copyright and license is recorded in `index.json` and on eBible.org.
