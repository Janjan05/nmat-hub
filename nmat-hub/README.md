# NMAT Hub — Setup Guide

## What's in this folder
- `index.html` — the main app
- `manifest.json` — makes it installable as a PWA
- `sw.js` — service worker (offline support)
- `icons/` — app icons

---

## How to deploy (GitHub Pages — FREE)

### Step 1: Create a GitHub account
Go to https://github.com and sign up (free).

### Step 2: Create a new repository
- Click the "+" icon → "New repository"
- Name it: `nmat-hub`
- Set to **Public**
- Click "Create repository"

### Step 3: Upload your files
- Click "uploading an existing file"
- Drag and drop ALL files from this folder:
  - index.html
  - manifest.json
  - sw.js
  - icons/ folder (upload the two .png files inside)
- Click "Commit changes"

### Step 4: Enable GitHub Pages
- Go to Settings → Pages
- Under "Source", select: **Deploy from a branch**
- Branch: **main**, folder: **/ (root)**
- Click Save

### Step 5: Get your URL
After ~1 minute, your app will be live at:
`https://YOUR-USERNAME.github.io/nmat-hub/`

---

## How to install on iPad
1. Open Safari → go to your GitHub Pages URL
2. Tap the Share button (box with arrow)
3. Tap "Add to Home Screen"
4. Tap "Add"
Done! It now appears on your home screen like a real app.

## How to install on laptop (Chrome)
1. Open Chrome → go to your URL
2. Look for the install icon in the address bar (looks like a computer with a down arrow)
3. Click it → "Install"
Done! It opens as a standalone window.

---

## How to use
1. Open NMAT Hub
2. Tap "Import" → give your reviewer a name, pick subject, select the .html file
3. Tap "Save Reviewer"
4. It appears in your library — tap "Open reviewer" anytime to launch it

Your reviewers are stored locally on each device (IndexedDB).
They persist across sessions and work offline once imported.
