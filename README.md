# Personal Academic Website (GitHub Pages Ready)

This repository contains a complete personal website you can publish on GitHub Pages.

## Quick Edit Before Publishing

Open `index.html` and replace:
- `Your Name`
- `AI PhD Student @ University`
- social links (`GitHub`, `LinkedIn`, `Email`, `CV`)
- news, publications, and experience text

To use your own profile image:
1. Put your photo in `assets/` (example: `assets/profile.jpg`)
2. In `index.html`, change:
   - `src="assets/profile-placeholder.svg"` to `src="assets/profile.jpg"`

## Publish To GitHub (First Time)

1. Create a new repository on GitHub.
- Repository name: `<your-username>.github.io`
- Keep it Public
- Do not add README/gitignore/license there (this folder already has files)

2. In this project folder, run:

```bash
git init
git add .
git commit -m "Initial personal website"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
git push -u origin main
```

3. Go to GitHub:
- Open repository `Settings` -> `Pages`
- Under `Build and deployment`:
  - Source: `Deploy from a branch`
  - Branch: `main` and `/ (root)`
  - Click `Save`

4. Wait 1-3 minutes, then open:
- `https://<your-username>.github.io`

## Local Preview

You can simply open `index.html` in your browser.

## Files Included

- `index.html` - Website content
- `styles.css` - Styling and responsive layout
- `assets/profile-placeholder.svg` - Replace with your photo
- `assets/publication-thumb.svg` - Placeholder publication thumbnail
