
# S4Tech CRM — Website (Final)

This package contains a multi-page static website for S4Tech CRM with the following pages:
Home, About, Features, Screenshots, Pricing, Docs, Blog, Contact, Download.

## Contact Form
The contact form is wired to: **dhl.srij1999@gmail.com** using FormSubmit.co.
To change provider to Formspree, replace the form `action` attribute in `contact.html` with your Formspree form URL (e.g., https://formspree.io/f/<your-id>).

## Deploy (GitHub Pages)
1. Create a new GitHub repo and push the contents of this folder to `main` branch.
2. In the repo Settings → Pages, set Source to `main` and folder `/`.
3. The site will be available at `https://<username>.github.io/<repo>/` in a few minutes.

## Deploy (Netlify)
1. Log into Netlify and create a new site from Git.
2. Connect the repo and deploy with default settings.
3. Optional: change site name to get a friendly URL like `https://s4techcrm.netlify.app`.

## Preview & Live Demo
I cannot host a public live demo from this environment. To preview quickly:
- Run a simple static server locally:
  ```bash
  python -m http.server 8080
  # open http://localhost:8080 in your browser
  ```

## Files Included
- HTML pages for each section
- assets/images (logo, featured, thumbnail, favicon)
- assets/css/style.css
- assets/js/site.js
- netlify.toml (Netlify config)
- deploy/README-GHPAGES.md (GitHub Pages instructions)
- CNAME (placeholder for custom domain)

If you want, I can push this to a GitHub repo for you (I'll provide the exact git commands and a ready-made commit message).

---
Enjoy — S4Tech CRM website ready to publish!
