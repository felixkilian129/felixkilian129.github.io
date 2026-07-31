# ArgentWatch Portfolio

Personal portfolio for **Felix Kilian / ArgentWatch** with a focus on software engineering, backend and API integration, automation, application operations, and IT security.

## Current structure

- `index.html` — landing page, positioning, featured work, about, and contact
- `projects.html` — public projects, anonymized professional case studies, and CTF results
- `style.css` — responsive ArgentWatch design system without external fonts or JavaScript dependencies

## Local preview

Open `index.html` directly in a browser or start a local server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deployment plan

The site is intended for GitHub Pages and the custom domain `argentwatch.de`.

Before publishing:

1. Review all professional case studies for confidentiality.
2. Decide whether to rename the repository to `argentwatch.github.io` or deploy through the custom domain.
3. Configure GitHub Pages.
4. Configure and verify the custom domain before changing DNS records.
5. Add legal pages required for the final public use case.

## Privacy

The MVP intentionally avoids analytics, tracking, external fonts, embedded third-party widgets, and a contact form.
