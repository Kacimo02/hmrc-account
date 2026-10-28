# HMRC — Single-File Website

A complete, responsive UK-style tax and employment account website.
All HTML, CSS and JavaScript is merged into a single `index.html` file,
making it super easy to deploy on GitHub Pages.

## Files to upload to GitHub

| File | Purpose |
|---|---|
| `index.html` | The entire website (HTML + CSS + JS all in one file) |
| `apple-touch-icon.png` | 180×180 icon for iPhone home screen shortcut |
| `icon.png` | Full-size crown icon used in the header |
| `favicon-32x32.png` | Browser tab icon (32×32) |
| `favicon-16x16.png` | Browser tab icon (16×16) |

## How to deploy on GitHub Pages

### Step 1: Create a GitHub repository
1. Go to https://github.com and sign in
2. Click the **+** icon (top right) → **New repository**
3. Name it something like `hmrc-account` (or any name)
4. Make it **Public** (required for free GitHub Pages)
5. Click **Create repository**

### Step 2: Upload the files
1. In your new repo, click **uploading an existing file** link
   (or click **Add file** → **Upload files**)
2. Drag and drop these 5 files:
   - `index.html`
   - `apple-touch-icon.png`
   - `icon.png`
   - `favicon-32x32.png`
   - `favicon-16x16.png`
3. Click **Commit changes**

### Step 3: Enable GitHub Pages
1. Go to **Settings** (top tab in your repo)
2. Click **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Choose **main** branch, **/ (root)** folder
5. Click **Save**
6. Wait 1–2 minutes, then visit the URL shown (e.g.
   `https://yourusername.github.io/hmrc-account/`)

## Add to iPhone home screen

1. Open the site in Safari on your iPhone
2. Tap the **Share** button (square with arrow)
3. Scroll down and tap **Add to Home Screen**
4. Tap **Add** — the crown icon will appear on your home screen

## Sign-in

- Email: `ch.belkacem12@gmail.com`
- Password: `Belkacem0212@`

## Run locally

Just double-click `index.html` — it opens in your browser. No build step,
no dependencies, no server needed.
