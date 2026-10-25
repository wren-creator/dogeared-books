# Roadmap

## Why this exists

Britley's personal/family book line needed its own home, separate from the mainframe-consulting catalog at `books.britleyhoffconsulting.com`. Different tone, different readers, not meant to blend. Domain `dogearedbooks.net` secured 2026-08-10.

## Decisions locked in

- Same mechanics as the mainframe `books` repo: standalone static site, GitHub Pages, GoDaddy CNAME, Gumroad for checkout. Proven pattern, no reason to reinvent it for a second brand.
- Visually distinct from the mainframe catalog on purpose: warm "old library" theme (wood, parchment, brass, a literal dog-eared page corner on each cover) instead of the terminal/CRT look, matched to a family-book audience instead of a technical one.
- Tags are a first-class field on each book (not bolted on later), stored as an array so one book can carry more than one tag. The shelf-filter bar at the top of the page auto-generates from whatever tags exist in `data/books.js`; a tag with no book yet just doesn't show up until one uses it.
- 2026-08-11: split the original "Family & Identity" category into two separate tags (`Family`, `Identity`), both kept on the existing title, and reserved `Adventure` as a tag name for a future title in that vein.
- Two contact addresses: `support@dogearedbooks.net` for reader questions, `admin@dogearedbooks.net` for everything else.

## Next actions

- [x] Get first title's real details, title, price ($5.99), category (Family & Identity), Gumroad link (`https://britley.gumroad.com/l/moms`), and swap into `data/books.js` + `books/my-dad-is-now-my-mom-too.yaml`. Card summary is a trimmed version of Britley's full description (the full text runs four paragraphs including an author's note; the yaml file keeps the complete version, the card shows a condensed synopsis so the grid layout holds up once more titles are added)
- [x] Cover art in place at `assets/books/my-dad-is-now-my-mom-too.png`
- [ ] Enable GitHub Pages on the repo once it's pushed (source: `main`, root)
- [ ] Add a DNS `CNAME`/`A` record at GoDaddy pointing `dogearedbooks.net` to GitHub Pages
- [ ] Push to GitHub (holding per standing rule: no push without explicit go-ahead)

## Later / not yet scoped

- [x] Second title added 2026-10-25: *Still My Mom Too* (Book 2 of Timmy's story, ages 8 to 10, $5.99 placeholder). Gumroad link is live: `https://britley.gumroad.com/l/stillmymom`. The full Gumroad listing text lives in `books/still-my-mom-too.gumroad.md`
- Bundle offer for the two Timmy books, now that there is more than one
