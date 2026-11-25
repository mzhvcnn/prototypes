# Prototypes

Clickable prototypes, published at https://mzhvcnn.github.io/prototypes/.

The site is public: anyone with the link can open it.

Want your own gallery like this? Follow the [guide](GUIDE.md).

## Adding or updating a prototype

1. Export the prototype as a single HTML file. For the CNN paywall project, run `npm run export` in that project.
2. Copy it here as `<slug>/index.html`, for example `cnn-article-paywall/index.html`.
3. Optionally add a `<slug>/thumbnail.png` screenshot for the gallery card.
4. Add or update its entry in `prototypes.json` with the slug, project, title, description, author, email, and updated date. Prototypes are grouped by `project` in the side navigation, and a new project name creates a new group. The author and email show as a "Designed by" credit on the card.
5. Commit and push. The site refreshes within a minute or two.

Each prototype gets its own link, for example https://mzhvcnn.github.io/prototypes/cnn-article-paywall/.
