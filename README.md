# Vid2WAM project website

A static, dependency-free project page for **Vid2WAM: Distilling Video Diffusion Priors into World Action Models**.

## Preview locally

From this folder, run:

```powershell
python -m http.server 4173
```

Then open `http://127.0.0.1:4173/`.

## Publish with GitHub Pages

1. Push this folder to a GitHub repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)`, then save.

All links and media use relative paths, so the page works for both `username.github.io` and repository project pages.

## Main files

- `index.html` — page structure and paper content
- `styles.css` — visual design and responsive layouts
- `script.js` — scroll reveals and method interaction
- `assets/` — paper figures, PDFs, video, and social preview

The author and affiliation block matches the camera-ready preprint.
