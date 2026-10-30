# SuperDiagnosticTool

A responsive, single-page website for SuperDiagnosticTool, with a cream-and-blue visual theme and subtle interface animations.

## Project structure

```text
SuperDiagnosticTool-Website/
├── index.html      # Complete website (HTML, CSS, JavaScript, and embedded image)
├── README.md       # Project and deployment instructions
└── .nojekyll       # Prevents GitHub Pages from applying Jekyll processing
```

## Run locally

No build tools or package installation are required.

1. Download or extract this folder.
2. Open `index.html` in a modern browser.

The Google Fonts stylesheet may require an internet connection. The page itself has no local asset folders or build step; its image is embedded in the HTML.

## Publish on GitHub

1. Create a new repository on GitHub.
2. Upload the contents of this folder (upload `index.html`, `README.md`, and `.nojekyll`, not the ZIP file).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site; the published URL will appear in the Pages settings.

## Deploy on Cloudflare Pages or Netlify

Create a new project and upload this folder, or connect the GitHub repository. Because this is a static site, leave the build command empty and set the output directory to the project root (`/`).

## Notes

- The site is static and does not require Node.js, Python, a backend, or a build command.
- Existing page interactions and scripts are kept inside `index.html`.
- The original project links and attribution shown in the page have been preserved.
- Review the original project's license and permissions before redistributing or modifying it publicly.
