# Roadmap

## Why this exists

Britley's personal/family book line needed its own home, separate from the mainframe-consulting catalog at `books.britleyhoffconsulting.com`. Different tone, different readers, not meant to blend. Domain `dogearedbooks.net` secured 2026-08-10.

## Decisions locked in

- Same mechanics as the mainframe `books` repo: standalone static site, GitHub Pages, GoDaddy CNAME, Gumroad for checkout. Proven pattern, no reason to reinvent it for a second brand.
- Visually distinct from the mainframe catalog on purpose: warm "old library" theme (wood, parchment, brass, a literal dog-eared page corner on each cover) instead of the terminal/CRT look, matched to a family-book audience instead of a technical one.
- Categories are a first-class field on each book (not bolted on later), the shelf-filter bar at the top of the page auto-generates from whatever categories exist in `data/books.js`.
- Two contact addresses: `support@dogearedbooks.net` for reader questions, `admin@dogearedbooks.net` for everything else.

## Next actions

- [x] Get first title's real details, title, price ($5.99), category (Family & Identity), Gumroad link (`https://britley.gumroad.com/l/moms`), and swap into `data/books.js` + `books/my-dad-is-now-my-mom-too.yaml`. Card summary is a trimmed version of Britley's full description (the full text runs four paragraphs including an author's note; the yaml file keeps the complete version, the card shows a condensed synopsis so the grid layout holds up once more titles are added)
- [x] Cover art in place at `assets/books/my-dad-is-now-my-mom-too.png`
- [ ] Enable GitHub Pages on the repo once it's pushed (source: `main`, root)
- [ ] Add a DNS `CNAME`/`A` record at GoDaddy pointing `dogearedbooks.net` to GitHub Pages
- [ ] Push to GitHub (holding per standing rule: no push without explicit go-ahead)

## Later / not yet scoped

- Second title in the personal line, no topic decided yet
- Bundle offer once there's more than one book
