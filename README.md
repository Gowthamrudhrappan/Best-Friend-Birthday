# Shabitha's Birthday Site

Just one file: `index.html`. All the photos and videos are already baked
inside it (as embedded data), so there's no separate "assets" or "images"
folder to upload — that's not a mistake, it's intentional. That's also why
the file itself is large (~8-9 MB) — upload exactly as-is.

## What's new
- The video clips play directly (tap to reveal, then tap play) — no extra
  files needed, they're embedded in the page.
- Background music: tap "Yes Sure" on the opening screen and the song
  starts playing for real (this only works on a live https link like
  GitHub Pages — it won't autoplay with sound from a double-clicked local
  file, browsers block that). It pauses if she switches tabs/apps and
  resumes when she's back. The 🎵 button in the corner toggles it manually.

## Host it free on GitHub Pages

1. Create a new GitHub repo (e.g. `shabitha-bday`), make it **Public** (Pages needs public on the free plan).
2. Upload `index.html` to the repo (repo page → "Add file → Upload files").
3. Commit the upload.
4. Go to **Settings → Pages**.
5. Under "Build and deployment", set **Source** to "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
6. Wait a minute or two, then your site will be live at:
   `https://<your-username>.github.io/<repo-name>/`

That link is what you'd share with Shabitha. Keep the repo public so Pages works, but there's nothing sensitive in the code itself — just don't post the link anywhere public before her birthday.
