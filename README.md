# Rohith Bharadwaj Portfolio - GitHub Pages

This folder is a self-contained static portfolio. It does not require Node.js or a build command.

## Deploy

1. Create a public GitHub repository, for example `rohithbharadwaj2.github.io`.
2. Upload everything inside this folder to the repository root.
3. Open **Settings > Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.

Your site will appear at `https://rohithbharadwaj2.github.io/` when the repository has that exact name. For another repository name, the URL will be `https://rohithbharadwaj2.github.io/repository-name/`.

## Edit

- All page content, colors, animations, and layout are in `index.html`.
- Replace images in `assets/` while keeping the same filenames, or update their paths in the HTML.
- Replace résumé PDFs in `resumes/` while keeping the same filenames.
- Search for the existing text in `index.html` to update dates, metrics, links, phone number, or descriptions.

## Test locally

Open `index.html` directly in a browser. For video compatibility, a simple local web server is preferable:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.
