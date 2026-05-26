# Sharon Singh — Portfolio Site

Custom-coded, deploys to Vercel for free, no monthly cost.

## How to preview locally

1. Download this whole folder to your Mac
2. Double-click `index.html` — it opens in your default browser
3. To see updates: save the file in your text editor, then refresh the browser tab

## File structure

```
portfolio/
├── index.html              ← homepage
├── style.css               ← shared styles for everything
├── case-studies/
│   ├── oracle-health.html        (coming next)
│   ├── customer-attrition.html   (coming next)
│   ├── mental-health.html        (coming next)
│   └── data-governance.html      (coming next)
└── assets/
    └── headshot.jpg        ← drop your photo here, named exactly this
```

## To use your headshot

1. Save your headshot as `headshot.jpg` in the `assets/` folder
2. In `index.html`, find the line that says `<!-- Replace with: <img src="assets/headshot.jpg" ... -->`
3. Replace the entire `<div class="about__photo">...</div>` block with:
   ```html
   <div class="about__photo">
     <img src="assets/headshot.jpg" alt="Sharon Singh" />
   </div>
   ```

## Editing text

Open `index.html` in any text editor (TextEdit works, but VS Code is better and free).
The text is plain English, easy to find and change.

## Deployment

Once the site is finalized, I'll walk you through:
1. Creating a free Vercel account
2. Dragging the folder onto vercel.com (literally drag-and-drop)
3. Buying a custom domain (~$10/year on Cloudflare or Namecheap)
4. Pointing the domain at Vercel

The deploy itself takes 30 seconds.
