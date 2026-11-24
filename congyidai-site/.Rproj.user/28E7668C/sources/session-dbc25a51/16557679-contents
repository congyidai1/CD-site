# congyidai.com

Personal academic website built with Quarto.

## Files

| File | What it is |
|------------------------------------|------------------------------------|
| `_quarto.yml` | Site settings: title, navigation bar, footer, theme |
| `styles.scss` | Fonts and colors |
| `index.qmd` | About page (home) |
| `research.qmd` | Papers |
| `writing.qmd` | Blog listing page (lists everything in `posts/` automatically) |
| `cv.qmd` | CV page, shows `files/Dai_CV.pdf` |
| `posts/` | One folder per blog post, each with an `index.qmd` |
| `files/` | PDFs (CV, working papers) |
| `images/` | Headshot and figures |

Search the project for `TODO` to find everything you still needqua to fill in.

## First-time setup

1.  Install Quarto: https://quarto.org/docs/get-started/ (RStudio already bundles it).
2.  Open this folder in RStudio as a project, or open a terminal in the folder.
3.  Preview the site locally: `quarto preview`. It reloads every time you save a file.

## Add your files

- Headshot: save a square photo as `images/headshot.jpg`, then change `image:` in `index.qmd` to `images/headshot.jpg`.
- CV: save it as `files/Dai_CV.pdf`.
- Working paper: save it as `files/Dai_Quid_Pro_Quo_WP.pdf`, or change the link in `research.qmd` to the public URL.

## Write a new blog post

1.  Copy the folder `posts/quid-pro-quo-explainer` and rename it, for example `posts/my-new-post`.
2.  Edit `index.qmd`: change the title, date, and categories, then write.
3.  To keep a post hidden while drafting, add `draft: true` to its header.
4.  R code chunks work in posts. Figures render into the page automatically.

## Publish to GitHub Pages (free)

1.  Create a GitHub account and a new public repository, for example `congyidai-site`.
2.  Put this folder in that repository (GitHub Desktop is the easiest way).
3.  In a terminal in this folder, run `quarto publish gh-pages`. The first time, it asks you to confirm.
4.  The site goes live at `https://<your-username>.github.io/congyidai-site/`.
5.  To update the site later: edit, then run `quarto publish gh-pages` again.

## Connect congyidai.com

1.  In the GitHub repository: Settings \> Pages \> Custom domain, enter `congyidai.com`, save.
2.  At your registrar, add these DNS records:
    - Four `A` records for `@` pointing to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
    - One `CNAME` record for `www` pointing to `<your-username>.github.io`
3.  Add a file called `CNAME` (no extension) in this folder containing just `congyidai.com`, and add `- CNAME` under `resources:` in `_quarto.yml` so it survives each publish.
4.  Back in GitHub Pages settings, tick "Enforce HTTPS" once it becomes available (can take up to a day).
