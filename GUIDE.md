# Make your own prototype gallery with Cursor

This guide sets up a gallery like [this one](https://mzhvcnn.github.io/prototypes/): a single link where people can open and click through your prototypes, grouped by project. You don't need to know git or code. Cursor's agent does the setup, and you approve the steps it asks about.

It takes about 15 minutes the first time.

## What you need

- **Cursor**, installed and signed in.
- **A GitHub account.** Sign up free at [github.com](https://github.com/signup) if you don't have one.
- **Google Chrome**, which Cursor uses to check that pages work.

## 1. Create your gallery

In Cursor, choose **File > Open Folder**, make a new empty folder called `prototypes`, and open it. Then open the agent chat (Cmd+L) and paste this prompt, replacing the name and email with your own:

> Create a prototype gallery in this folder and publish it as a public GitHub Pages site, using a new public GitHub repo called `prototypes` on my account. Copy the gallery design from https://github.com/mzhvcnn/prototypes: the `index.html` page with the project sidebar and guide, the `GUIDE.md`, the `prototypes.json` format, the `README.md`, and an empty `.nojekyll` file. Start with an empty prototype list and don't copy any of the existing prototype folders. My name for the "Designed by" credit is **Your Name** and my email is **you@cnn.com**. When it's live, send me the link.

If Cursor asks you to sign in to GitHub, follow its steps. It usually opens a browser page with a one-time code, which you approve once.

When it's done, you'll get a link like `https://YOUR-GITHUB-NAME.github.io/prototypes/`. The page will say "No prototypes yet" until you add one.

## 2. Build a prototype

Open a separate folder for your prototype project (for example `my-paywall-prototype`) and describe what you want. Figma links work well:

> Build a clickable mobile prototype from this Figma design: FIGMA LINK. Start on the home feed; tapping the first article opens the article screen. Put it inside an iPhone device frame and run it on a localhost so I can try it.

Keep giving feedback in the same chat ("make the transition smoother", "the paywall should appear later") until it feels right.

## 3. Add the prototype to your gallery

In the prototype's chat, paste:

> Export this prototype as a single standalone HTML file that works offline, then publish it to my gallery repo at `~/PATH/TO/prototypes`. Put it in the project **Project name** with the title **Prototype title** and a one-sentence description, and add a thumbnail screenshot. Push it, check that the live link works, and send me the link.

The gallery updates a minute or two after the push. Each prototype gets its own link, and each project gets one too (for example `.../prototypes/#article-paywall`) for sharing a single project.

## Making changes later

Just ask in chat. For example:

- "Update the gallery copy of this prototype with my latest changes."
- "Move the *On landing* prototype into a project called *Onboarding*."
- "Remove the *Old checkout* prototype from my gallery."

## Good to know

- **The link is public.** Anyone who has it can open the gallery. Search engines are asked not to list it, but don't publish anything confidential, such as unreleased pricing.
- **Files are kept small.** Each prototype is one HTML file. If a prototype uses a lot of large images, ask Cursor to downsize them before publishing.
- **Something broke?** Paste the error or a screenshot into the chat and ask Cursor to fix it.
