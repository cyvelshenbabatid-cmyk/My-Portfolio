# Cyvelshen Khesley Babatid Portfolio

Static portfolio website ready for public deployment.

## Files

- `index.html` - main page
- `styles.css` - site styling
- `script.js` - reveal-on-scroll interactions
- `assets/ea-resume.pdf` - downloadable resume
- `assets/portfolio.pdf` - downloadable and embedded portfolio

## GitHub Pages Deployment

This project includes a GitHub Actions workflow at `.github/workflows/deploy-pages.yml`
so it can deploy automatically to GitHub Pages whenever you push to the `main` branch.

### Publish Steps

1. Create a new GitHub repository.
2. Upload or push this entire folder to the repository.
3. Make sure your default branch is named `main`.
4. In GitHub, open `Settings` > `Pages`.
5. Under `Build and deployment`, set `Source` to `GitHub Actions`.
6. Push to `main` or run the workflow manually from the `Actions` tab.
7. Wait for the workflow to finish, then open the generated GitHub Pages URL.

### If You Are Uploading From Terminal

```bash
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin YOUR_GITHUB_REPO_URL
git push -u origin main
```

## Before Going Live

- Replace the email and phone number in `index.html` if needed.
- Add a custom domain in your hosting provider if you want a branded URL.
- If you want richer social sharing cards, add a custom preview image and update the Open Graph metadata in `index.html`.
