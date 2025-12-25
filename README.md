# ProofNest Landing Page

The official landing page for [ProofNest](https://proofnest.io) - quantum-proof verification infrastructure for AI decisions.

## Live Site

**[proofnest.io](https://proofnest.io)**

## Tech Stack

- Pure HTML/CSS/JS (no frameworks)
- Vercel deployment
- Google Analytics 4 (GDPR-compliant, consent-based)

## Features

- Responsive design (mobile-first)
- Accessibility (WCAG 2.1 AA compliant)
- GDPR-compliant cookie consent
- Animated particle network background
- Dark theme with gold/cyan accents

## Local Development

```bash
# Clone the repository
git clone https://github.com/Proofnest/proofnest.io.git
cd proofnest.io

# Serve locally (any static server works)
python3 -m http.server 8000
# or
npx serve .

# Open http://localhost:8000
```

## Deployment

Deployed automatically via Vercel on push to `main` branch.

Manual deployment:
```bash
npx vercel --prod
```

## Project Structure

```
proofnest.io/
├── index.html          # Main landing page
├── privacy.html        # Privacy policy
├── 404.html            # Custom 404 page
├── robots.txt          # Search engine directives
├── sitemap.xml         # XML sitemap
├── vercel.json         # Vercel configuration (headers, redirects)
├── assets/
│   ├── favicon.svg     # Site favicon
│   ├── og-image.png    # Social sharing image (1200x630)
│   └── *.svg           # Various SVG assets
├── LICENSE             # MIT License
└── BRAND_GUIDE.md      # Brand guidelines
```

## Related Repositories

- [proofnest](https://github.com/Proofnest/proofnest) - Main Python library
- [proofnest-anchor](https://github.com/Proofnest/proofnest-anchor) - Bitcoin timestamping CLI

## License

MIT License - see [LICENSE](LICENSE)

## Links

- **Website**: [proofnest.io](https://proofnest.io)
- **PyPI**: [pypi.org/project/proofnest](https://pypi.org/project/proofnest/)
- **Documentation**: [GitHub README](https://github.com/Proofnest/proofnest#readme)
- **Company**: [Stellanium Ltd](https://stellanium.io)
