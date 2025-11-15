# RAL — Static Site

This is a simple static site (single `index.html`) with media in the `media/` folder. It's ready to be deployed to Netlify.

Quick deploy options

- Drag & drop (fastest):
  1. Zip the `RAL` folder or leave it as-is.
  2. Open https://app.netlify.com/drop
  3. Drag the `RAL` folder onto the page — Netlify will deploy it.

- GitHub + Netlify (CI):
  1. Create a GitHub repository and push this folder to it.
  2. In Netlify, choose "New site from Git" and connect the repo.
  3. Set the publish directory to `/` (the root). The included `netlify.toml` sets this by default.

- Local preview:
```bash
# from the project root
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

Notes
- Filenames are case-sensitive on Netlify (Linux). The references in `index.html` match the files in `media/`.
- If you want me to push this to GitHub and set up the Netlify connection, tell me the repo name or provide a remote URL and I'll prepare the git commands.
