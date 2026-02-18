# Elemprin Website (Static Prototype)

Location: `projects/elemprin/site`

## Contents
- `index.html` — static site with modern layout, agentic status bar, CTA, value props, SD-WAN section, tech stack, case studies, insights, CTA footer.
- `style.css` — styles (no build step). Uses Google Fonts (Inter) and light JS for status rotation.
- Links to PDFs in sibling folder (case studies) assume deployment keeps files accessible.

## How to preview
```bash
cd projects/elemprin/site
python3 -m http.server 8000
# open http://localhost:8000
```
(Use any static server of your choice.)

## Sections
- Hero + CTAs + Agentic Status bar
- Core Value (3 cards)
- Managed SD-WAN (how it works + proof points placeholders)
- Technology Stack (trusted tech)
- Case Studies (links to PDFs)
- Insights (from Daily AI Industry Trends)
- CTA footer (Schedule Review / Download Case Study)

## Next steps
- Swap placeholder metrics with real numbers.
- Add schedule link/form endpoint for "Schedule Review".
- Deploy to your preferred host (Netlify, Vercel, S3/CloudFront, etc.).
- If using a different folder structure, adjust case study links.
