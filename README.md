# Ascend

A study tracker with spaced revision, a rival Arena with ranks, and **En (援)**, your study buddy.
Works offline, installs like an app, and keeps all data on your device.

## Install on GitHub Pages (free)

1. Sign in at github.com, tap **+**, then **New repository**. Name it `ascend`, set it to **Public**, leave "Add a README" unticked, then **Create repository**.
2. Click **uploading an existing file**. Drag in everything from this folder: `index.html`, `sw.js`, `manifest.webmanifest`, `.nojekyll`, `LICENSE`, and the `assets` and `icons` folders. Write a commit message and press **Commit changes**.
   - If folders will not upload in your browser, use the Git commands below instead.
3. Open the repository's **Settings**, then **Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, **Branch** to `main`, folder `/ (root)`, and press **Save**.
4. Wait about a minute. Your app is live at `https://YOUR-USERNAME.github.io/ascend/`.

### Or with Git

```bash
cd ascend
git init -b main
git add .
git commit -m "Ascend 1.2"
git remote add origin https://github.com/YOUR-USERNAME/ascend.git
git push -u origin main
```

Then do step 3 above.

## Install on your phone or computer

- **Android (Chrome):** open the link, tap the menu, then **Install app**.
- **iPhone (Safari):** open the link, tap **Share**, then **Add to Home Screen**.
- **Desktop (Chrome or Edge):** click the install icon in the address bar.

## Release an update

1. Replace the changed files in the repository.
2. In `sw.js`, change the version, for example `ascend-v1.2.0` to `ascend-v1.2.1`.
3. Commit. Installed apps show an **Update ready** button the next time they open.

## Good to know

- Data is stored in the browser on each device. Clearing site data erases it. Use **More, Backup and data** to export a copy.
- **More, Backup and data, Reset everything** wipes the app back to a first launch, including developer mode.
- The syllabus lists follow the current NCERT textbooks. Check against your own edition.
- Everything uses relative paths, so it works from any repository name.

## Files

| File | Purpose |
|---|---|
| `index.html` | The app |
| `assets/en.js` | En's artwork |
| `sw.js` | Offline cache and updates |
| `manifest.webmanifest` | Install details |
| `icons/` | App icons |

MIT licence.
