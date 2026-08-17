# Venkatesh Gollaprolu — Portfolio Site

One file: `index.html`. Your photo and résumé PDF are embedded inside it, so this
single file *is* the entire website — no folders, no build step, nothing to break.

## Option A — GitHub Pages (recommended, free forever)

1. Go to [github.com](https://github.com) and create a new **public** repository —
   name it `yourusername.github.io` (replace `yourusername` with your actual
   GitHub username — this exact name matters).
2. On the repo page, click **Add file → Upload files**, drag in `index.html`,
   and click **Commit changes**.
3. Go to **Settings → Pages**. Under "Build and deployment", set **Source** to
   **Deploy from a branch**, branch **main**, folder **/ (root)**. Click **Save**.
4. Wait 1–2 minutes, then visit `https://yourusername.github.io` — your site is live.

Every time you upload a new `index.html` to that repo, the live site updates
automatically within a minute or two.

## Option B — Netlify Drop (fastest, no account strictly required)

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag `index.html` straight onto the page.
3. Netlify gives you a live URL immediately (something like
   `random-name-123.netlify.app`). Create a free account if you want to keep
   the site permanently and pick a custom subdomain.

## Option C — Vercel or Cloudflare Pages

Both have free tiers and a similar "import/drag a folder" flow:
- [vercel.com/new](https://vercel.com/new) → drag and drop the file.
- [pages.cloudflare.com](https://pages.cloudflare.com) → "Direct Upload".

## Using your own domain later

All three options above let you attach a custom domain (e.g. `venkatesh.dev`)
for free on their end — you'd only pay a domain registrar (~$10–15/year) if
you want one. Not required to get started.

## Editing the content later

Open `index.html` in any text editor — the text for each section (About,
Trail, Badges, Gear, Education, Contact) is plain, readable HTML. Search for
the section you want to change (e.g. `id="about"`) and edit the text directly.
If you want help updating it, just share the file back and describe the change.
