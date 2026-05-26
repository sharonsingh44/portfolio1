# Sharon Singh — Portfolio Site (v2: Editorial Gravity)

Emerald + beige · Cormorant Garamond · data-science forward positioning.

## How to update your live site with these new files

You already have a GitHub repo at `github.com/sharonsingh44/portfolio1` connected to Vercel. To push these new files live:

### Easiest way — through GitHub.com (browser)

1. Go to **github.com/sharonsingh44/portfolio1**
2. Click on `index.html` in the file list → click the **🗑️ trash icon** (top right of the file view) → commit deletion
3. Repeat for `style.css`
4. For the `case-studies/` folder: click into it, delete each HTML file the same way
5. Back at the repo root, click **"Add file"** → **"Upload files"** → drag in the new `index.html`, `style.css`, and `README.md`
6. Then click **"Add file"** → **"Create new file"** → type `case-studies/customer-attrition.html` (the slash creates the folder), paste in the contents, commit
7. Repeat for the other 3 case study HTML files

This is tedious but straightforward. Vercel auto-deploys ~30 seconds after each commit.

### Faster way — replace files in bulk

1. Go to the repo
2. Click **"Add file"** → **"Upload files"**
3. Drag the entire `portfolio` folder contents in (it asks "replace existing files?" → yes)
4. Commit
5. Vercel auto-deploys

Note: file deletions on GitHub web don't always cascade properly, so the bulk-replace method is cleaner.

## File structure

```
portfolio/
├── index.html              ← homepage (updated)
├── style.css               ← new emerald + beige design
├── README.md               ← this file
├── case-studies/
│   ├── oracle-health.html       (updated)
│   ├── customer-attrition.html  (updated)
│   ├── mental-health.html       (updated)
│   └── data-governance.html     (updated)
└── assets/
    └── headshot.jpg        ← drop your photo here, named exactly this
```

## What changed from v1

- **Colors:** coral → emerald forest green (#0a4733) + beige (#ede4d3)
- **Fonts:** Fraunces → Cormorant Garamond (more classical, academic feel)
- **Headlines:** italics in deep emerald (signature move)
- **Positioning:** data science forward; sales background lives in About section only
- **Roman numerals** for sections (I, II, III, IV) and project list (i, ii, iii, iv)
- **Drop cap** on the first paragraph of About (the italicized large letter)
