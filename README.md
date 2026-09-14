# Abdallah Ahmed — CV Website

Modern, responsive, static CV website built with HTML, CSS and vanilla JavaScript.

## Run locally

Open `index.html` directly, or run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to GitHub Pages

### Option A — User/organization site

Create a repository named:

```text
EngAbdalah.github.io
```

Then:

```bash
git init
git add .
git commit -m "Create modern responsive CV website"
git branch -M main
git remote add origin https://github.com/EngAbdalah/EngAbdalah.github.io.git
git push -u origin main
```

Your site will be available at:

```text
https://engabdalah.github.io/
```

### Option B — Normal project repository

Create a repository such as `cv-website`, push the files, then go to:

**GitHub → Repository → Settings → Pages**

Under **Build and deployment** choose:

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/ (root)`

Save and wait for GitHub Pages to publish.

## Before publishing

Update these values if needed:

- Email
- Phone
- GitHub URL
- LinkedIn URL
- Job/company information
- Project links

The website intentionally uses the information from the supplied CV as its content source.
