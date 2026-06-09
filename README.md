# Human Design Basics

A standalone J.Cole Nutrition page/widget for helping visitors get their Human Design chart basics.

This is intentionally separate from the Recovered, Now What? / RRR worksheet engine.

## Current Version

- Branded landing page
- Explains what birth details are needed
- Links to a free external chart calculator
- Gives visitors a checklist of chart basics to save
- Includes a generated hero image
- Can be deployed separately on Vercel, then linked from the main website

## Files

- `index.html`
- `styles.css`
- `assets/human-design-basics-hero.png`

## Local Preview

From this folder, run:

```bash
python3 -m http.server 4188
```

Then open `http://127.0.0.1:4188`.

## Vercel Deployment

This folder can be deployed as a static site. In Vercel, create a new project from this folder/repo and leave the framework preset as "Other" or static HTML.
