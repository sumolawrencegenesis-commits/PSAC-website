# Progressive Student Advocacy Club (PSAC) Website

This repository contains a single-page static website for the Progressive Student Advocacy Club (PSAC). It is a responsive Tailwind CSS layout with Lucide icons and a client-side membership form.

## Files added
- `index.html` — the full website (single-file static site)
- `README.md` — this file with deployment instructions

## Quick deployment (GitHub Pages)
1. Create a repository on GitHub named `PSAC-website` (or use this existing repository).
2. Commit and push `index.html` to the repository's `main` branch.

From the repository Settings > Pages:
- Select the `main` branch and the `/ (root)` folder for GitHub Pages source.
- Save. GitHub Pages will provide a public URL like `https://yourusername.github.io/PSAC-website/`.

Note: It can take a minute or two for the site to become available. If you see a 404, wait a short while and refresh.

## Local preview
You can preview the site locally with a simple static server. For example (Python 3):

```bash
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

## Optional: Make the membership form actually submit
This site currently handles the membership form client-side and logs submissions to the browser console. To capture and store submissions, consider one of these options:

- Formspree (simple): add Formspree form endpoint and change the form's `action` attribute.
- Netlify Forms: add the `netlify` attribute and deploy to Netlify.
- Google Sheets: use a small Apps Script or a third-party integration.

If you'd like, I can add instructions or integrate one of these services for you.

## Next steps I can take for you
- Add a GitHub Action to build and auto-deploy (not necessary for a single `index.html`, but useful if you add a build step).
- Integrate a serverless form backend (Formspree, Netlify Forms or Google Sheets).
- Improve accessibility and SEO metadata.

---