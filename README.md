# PNG to PDF Guide - Render Static Site

This package contains two static HTML pages:

- `index.html`
- `png-to-pdf-quality-guide.html`

## Render deployment

1. Create a GitHub, GitLab, or Bitbucket repository.
2. Upload all files in this folder to the repository root.
3. In Render, choose **New > Static Site**.
4. Connect the repository.
5. If Render detects `render.yaml`, you can use the included Blueprint configuration.
6. Manual settings if needed:
   - Build Command: `echo "Static HTML site - no build required"`
   - Publish Directory: `.`
7. Deploy.

The site contains no framework or runtime dependencies.
