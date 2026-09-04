# Shubham Goyanka — Portfolio

A bold, recruiter-focused one-page portfolio for Shubham Goyanka, a Product Manager building 0-to-1 enterprise SaaS products.

## Sections

- **Hero** — positioning, local PDF resume download, and Notion portfolio link
- **Some of my work** — Chalo Insights, RateGain migration, and BambooBox automation
- **Experience** — resume-backed roles and measurable outcomes
- **About** — product approach and education
- **Toolkit** — product, craft, and tool capabilities
- **Contact** — email, phone, LinkedIn, and Notion portfolio

## Tech Stack

- Semantic HTML
- CSS with responsive layouts and reduced-motion support
- Vanilla JavaScript for mobile navigation and scroll reveals
- Google Fonts: Space Grotesk and DM Mono

## Structure

```text
├── index.html
├── style.css
├── script.js
├── Shubham Goyanka Reporting and Analytics Product Manager.pdf
└── README.md
```

## Run Locally

Open `index.html` directly, or serve the folder so the PDF and external links behave consistently:

```bash
python3 -m http.server 8000
```

Visit `http://localhost:8000` in a browser.

## Customization Checklist

- Replace the visual placeholders in the three work cards with project screenshots when available.
- Replace each `View project` link with the final case-study URL.
- Update the public Google Doc URL in the top navigation when the resume link changes.
- Update the local PDF filename in the hero download link if the PDF is renamed.
- Review the hero copy and contact details before publishing.
- Keep the PDF in the repository so the hero download remains available.

## Deployment

This is a static site and can be deployed to GitHub Pages, Netlify, Vercel, or Cloudflare Pages. Upload the HTML, CSS, JavaScript, and PDF together so the resume download remains available.
