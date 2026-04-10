# STEM Pathfinder AI (static site)

Multi-page static website for **STEM Pathfinder AI**: home, roadmap, resources, about, categories (Science / Technology / Engineering / Math with quizzes), AI chat embed, and blog-style posts.

## Run locally

Open `index.html` in a browser, or serve the folder so asset paths resolve consistently:

```powershell
# PowerShell (Python 3)
cd $PSScriptRoot
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Assets

- Site background: `assets/stem_background.jpg`
- Category hero images (optional): `assets/images/math-main.jpg`, `science-main.jpg`, `technology-main.jpg`, `engineering-main.jpg`

## GitHub

1. Create a new empty repository on GitHub (no README/license if you are pushing this repo as-is).
2. From this folder:

```powershell
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git branch -M main
git push -u origin main
```

### GitHub Pages (optional)

In the repo: **Settings → Pages → Build and deployment → Branch** → choose `main` and folder `/ (root)`, then save. The site will be published at `https://YOUR_USERNAME.github.io/YOUR_REPO/`.

## License

Add a `LICENSE` file in the repository if you want to specify terms for your content and code.
