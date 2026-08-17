# Dipesh Kumar Panda — Portfolio

A single-page developer portfolio. Everything — your photo, resume, and all
certificate images — is embedded directly inside `index.html`, so this whole
site is just one file plus a couple of small SEO extras. No build step,
no dependencies, nothing to install.

## What's in this folder

| File           | What it's for                                             |
|----------------|-------------------------------------------------------------|
| `index.html`   | The entire site — this is the only file you actually need   |
| `favicon.ico`  | Browser tab icon                                             |
| `favicon.png`  | Browser tab icon (modern browsers)                           |
| `robots.txt`   | Tells search engines they can crawl the site                 |
| `sitemap.xml`  | Helps search engines index the site                          |

## Deploy it — pick one (all free)

### Option A: GitHub Pages (recommended, free, easy custom domain later)
1. Create a new repository on GitHub, e.g. `portfolio`.
2. Upload every file in this folder to the repo (drag-and-drop works on
   github.com, or `git add . && git commit -m "deploy" && git push`).
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`,
   branch `main`, folder `/ (root)`. Save.
5. GitHub gives you a live URL in a minute or two:
   `https://YOUR-USERNAME.github.io/portfolio/`

### Option B: Netlify (fastest, drag-and-drop)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag this whole folder onto the page.
3. Netlify deploys it instantly and gives you a live URL
   (you can rename it in Site settings → Domain management).

### Option C: Vercel
1. Go to [vercel.com/new](https://vercel.com/new) and sign in.
2. Choose "Deploy" → upload this folder (or connect the GitHub repo from
   Option A).
3. Leave the framework preset as "Other" — no build command needed.
4. Deploy. Vercel gives you a live URL immediately.

## Before you deploy — two quick edits

1. **`sitemap.xml`** and **`robots.txt`** both contain the placeholder
   `YOUR-DOMAIN-HERE`. Once you know your live URL (from whichever option
   above), replace that placeholder with it. This step is optional — the
   site works fine without it — but it helps search engines index you
   correctly.
2. If you ever update your resume or photo, ping me with the new file and
   I'll re-embed it into `index.html` for you — since everything's baked
   into the one file, there's no separate asset to swap out manually.

## Custom domain (optional)

All three hosts above support pointing a custom domain (e.g.
`dipeshpanda.dev`) at your site for free — look for "Custom domain" in
Netlify/Vercel site settings, or "Custom domain" under GitHub Pages
settings. You'd need to buy the domain separately (Namecheap, Google
Domains, etc.), typically $10–15/year.
