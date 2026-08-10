# Dogeared Books

A small, family-friendly sales page for Britley's personal book line, separate brand and separate audience from the mainframe/AI consulting catalog at [books.britleyhoffconsulting.com](https://books.britleyhoffconsulting.com). Links out to Gumroad for checkout.

Live at [dogearedbooks.net](https://dogearedbooks.net). `index.html` renders a card grid from `data/books.js`, with a category filter bar generated automatically from whatever categories exist in the data, no separate config needed.

**To add a new title:**
1. Copy `books/_template.yaml` to `books/<slug>.yaml` and fill it in (title, summary, price, category, buy_url, cover filename).
2. Drop the cover image into `assets/books/`.
3. Add a matching entry to `data/books.js` by hand (same as the mainframe `books` repo, the yaml file is the intake record, not an automatic build source, there's no build script).

Contact: `support@dogearedbooks.net` for reader questions, `admin@dogearedbooks.net` for everything else.
