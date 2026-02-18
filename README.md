# Elemprin Website (Static Prototype)

Location: `projects/elemprin/site`

## Contents
- `index.html` — static site with modern layout, agentic status bar, CTA, value props, SD-WAN section, tech stack, case studies, insights, CTA footer.
- `case-study-autonomous.html` — case study page for Autonomous Growth Engine (HTML, no PDFs).
- `case-study-unified.html` — case study page for Unified Agentic Infrastructure (HTML, no PDFs).
- `style.css` — styles (no build step). Uses Google Fonts (Inter) and light JS for status rotation.

## How to preview
```bash
cd projects/elemprin/site
python3 -m http.server 8000
# open http://localhost:8000
```

## Sections
- Hero + CTAs + Agentic Status bar
- Core Value (3 cards)
- Managed SD-WAN (how it works + proof points placeholders)
- Technology Stack (trusted tech)
- Case Studies (now HTML pages)
- Insights (from Daily AI Industry Trends)
- CTA footer (Schedule Review / Download Case Study)

## Next steps
- Swap placeholder metrics with real numbers.
- Add schedule link/form endpoint for "Schedule Review".
- Deploy to your preferred host (Netlify, Vercel, S3/CloudFront, Pages ready).
