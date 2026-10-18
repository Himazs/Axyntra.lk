# Axyntra Digital Solutions — Website

Official website source for **Axyntra Digital Solutions**, a Sri Lanka-based web development and digital solutions agency welcoming project enquiries from clients worldwide.

- **Main website:** `index.html`
- **Portfolio:** `projects.html`
- **External demonstration gallery:** `preview.html` (excluded from search indexing)
- **Articles:** `blog-post.html?post=<slug>`
- **Deployment:** GitHub Pages (workflow at `.github/workflows/static.yml`)

## Viewing the site locally

The project is built with HTML, CSS and vanilla JavaScript. No build process is required. Extract the ZIP and run the following command from this folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/` in your browser. A local HTTP server is preferable to double-clicking the HTML files when checking navigation and assets.

## Contact enquiries

The homepage's **Request a Project Quote** form supports both:

1. **Continue on WhatsApp:** Opens WhatsApp with a prefilled draft addressed to the company's published WhatsApp number.
2. **Prepare an email enquiry:** Opens the visitor's mail application with a prepared message to `info@axyntra.lk`.

**Important:** This is a static site. It has **no server-side form submission, database storage or automatic delivery**. The visitor needs to review and click **Send** in WhatsApp or their email client. If you need a traditional form that delivers and stores leads automatically, connect a secure server-side endpoint or an approved form provider and add the appropriate privacy notices and anti-spam safeguards.

## How to publish with GitHub Pages

1. Back up your current `main` branch and any custom domain settings.
2. Copy the updated files **inside** this folder into the root of your Axyntra GitHub repository. Keep `.github/workflows/static.yml`.
3. Review the changes and commit them to `main` (or use a branch/pull request first).
4. In the repository, verify **Settings → Pages** uses **GitHub Actions**. The workflow deploys on pushes to `main`.
5. Verify `axyntra.lk` is still configured as the custom domain and HTTPS is enforced. Domain/DNS settings are managed in GitHub and at the DNS provider, not by this ZIP.
6. Test the published site on mobile and desktop; verify all third-party demos, social profiles, search previews and the WhatsApp/email workflows.

**No live deployment, domain modification or third-party integration was performed as part of this ZIP update.**

## Content verification before launch

The repository includes testimonials, client names, project descriptions, technologies, a founding date and social media destinations supplied by the original codebase. These details were not independently verified: obtain permission to publish names/quotes and make sure all claims accurately describe completed work. Label prototypes and demonstrations clearly rather than describing them as production deployments.

External blog photographs and external demonstration websites may become unavailable or block embedding. Host imagery with permission and use **Open Full Site** when iframe previews are unavailable.

## Optimization and accessibility

Commonly loaded large PNG images have been given smaller WebP alternatives; original PNG source assets remain in the repository. Reduced-motion accessibility styling, more usable navigation controls, missing favicon fixes and metadata corrections have also been included.

See `AUDIT_AND_CHANGELOG.md` for a detailed breakdown, known limitations and post-deployment checks.
