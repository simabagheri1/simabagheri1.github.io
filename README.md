# A Little Place to Remember — S.B.

A redesigned version of the original GitHub Pages website. The original academic CV text, PDF documents, and the full **Less Psychology, More Philosophy** essay have been retained. The unfinished “Sense of reality” entry is kept as `post2-draft.txt` and not shown publicly.

## Publish on GitHub Pages
1. Unzip this package.
2. Upload **the contents of this folder** to the root of your existing `simabagheri1.github.io` repository (replace the old README, config, and blog/post files; preserve the new `_layouts`, `_includes`, and CSS folder).
3. In repository **Settings → Pages**, select **Deploy from a branch**, `main`, `/ (root)` if not already configured.
4. Visit `https://simabagheri1.github.io/` after deployment.

This is a Jekyll site: preview with `bundle exec jekyll serve` if Jekyll is installed, or publish via GitHub Pages. Opening `index.html` directly will not process the Liquid/Jekyll tags.

## Customize
- **Blog title, pen name, description:** `_config.yml`.
- **Colors and fonts:** variables at the top of `assets/css/style.css`.
- **Homepage wording and botanical artwork:** `index.html`.
- **About page:** `about.md`.
- **Academic archive:** `academic.md`.
- **Existing essay:** `post1.md` (full original text retained).
- **Journal listing:** `_includes/journal-list.html`.

## Add a new entry
1. Create `my-new-entry.md` at repository root with:

```markdown
---
layout: post
title: My New Entry
permalink: /journal/my-new-entry/
summary: A few words about this entry.
---

Write your diary entry here.
```

2. Add a new entry link to `_includes/journal-list.html` using the existing entry as a model.
3. Commit changes to GitHub. The post becomes public after the site rebuilds.

## Privacy
The public pen name is S.B., but the **academic archive still includes your real name and identifying academic history**, as requested. Remove or anonymize `academic.md` and the academic PDFs if you want stronger separation from your identity. GitHub repository history and username may also reveal your identity.
