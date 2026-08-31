# Panda-RPKI Website

This directory contains a simple static website for Panda-RPKI.

## Files

- `index.html` — website content
- `styles.css` — website styling
- `CNAME` — custom domain for GitHub Pages
- `assets/panda-rpki-logo.png` — Panda-RPKI project logo

## Publish with GitHub Pages

1. Create a GitHub repository for the website, or place these files in the repository you want to publish.
2. Commit `index.html`, `styles.css`, and `CNAME`.
3. Open **Settings → Pages** in the GitHub repository.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the branch containing these files, normally `main`, and choose `/ (root)`.
6. In **Custom domain**, enter `panda-rpki.cn`.
7. Configure the DNS records for `panda-rpki.cn` at your DNS provider according to GitHub Pages documentation.
8. After GitHub verifies the domain and provisions the certificate, enable **Enforce HTTPS**.

## Before publishing

Review these values in `index.html`:

- GitHub repository URL
- Contact email
- Feature descriptions
- Documentation links

The current template uses:

- GitHub: `https://github.com/lanchengthu/panda-rpki`
- Contact: `contact@panda-rpki.cn`

Change them if necessary.
