# Prototypes

Clickable prototypes, published at https://mzhvcnn.github.io/prototypes/.

The site is public: anyone with the link can open it.

## Adding or updating a prototype

1. Export the prototype as a single HTML file. For the CNN paywall project, run `npm run export` in that project.
2. Copy it here as `<slug>/index.html`, for example `cnn-article-paywall/index.html`.
3. Optionally add a `<slug>/thumbnail.png` screenshot for the gallery card.
4. Add or update its entry in `prototypes.json` with the slug, title, description, author, email, and updated date. The author and email show as a "Designed by" credit on the card.
5. Commit and push. The site refreshes within a minute or two.

Each prototype gets its own link, for example https://mzhvcnn.github.io/prototypes/cnn-article-paywall/.
