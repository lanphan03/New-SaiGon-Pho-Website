# New Saigon Pho — Website

Static website for New Saigon Pho, 202 South Plank Rd, Newburgh, NY.

## Deploy to Netlify (recommended)

1. Push this folder to a GitHub repository.
2. Go to [app.netlify.com](https://app.netlify.com) → **Add new site** → **Import from Git**.
3. Select the repo. Netlify reads `netlify.toml` automatically — no build command needed.
4. Deploy. Your site will be live at a `*.netlify.app` URL.

## Deploy to GitHub Pages

1. Push to GitHub.
2. Repo **Settings** → **Pages** → Source: **Deploy from branch**.
3. Branch: `main`, folder: `/ (root)`.
4. Save. Site will be at `https://<username>.github.io/<repo>/`.

## Local preview

Open `index.html` in a browser, or run:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.
