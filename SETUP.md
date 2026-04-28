# Sara Saves — Setup Guide

## Files in this folder
- index.html — the main app
- manifest.json — makes it installable on iPhone
- icon-192.png / icon-512.png — app icons
- icon.svg — source icon

---

## Step 1: Upload to GitHub Pages

1. Go to github.com and sign in
2. Click the **+** in the top right → **New repository**
3. Name it: `sara-saves` (all lowercase, no spaces)
4. Make sure it's set to **Public**
5. Click **Create repository**
6. On the next screen, click **uploading an existing file**
7. Drag ALL 5 files from this folder into the upload area
8. Scroll down, click **Commit changes**
9. Now go to **Settings** (tab at the top of the repo)
10. In the left sidebar, click **Pages**
11. Under "Branch", select **main** and click **Save**
12. Wait 1-2 minutes, then your app will be live at:
    **https://[your-github-username].github.io/sara-saves**

---

## Step 2: Add to iPhone Home Screen

1. Open Safari on your iPhone (must be Safari, not Chrome)
2. Go to your GitHub Pages URL above
3. Tap the **Share** button (box with arrow pointing up)
4. Scroll down and tap **Add to Home Screen**
5. Name it **Sara Saves** and tap **Add**
6. It will appear on your home screen like an app

---

## Step 3: Set Up the Share Sheet (for 1-tap URL saving)

This lets you tap "Share" on ANY webpage and send it straight to Sara Saves.

1. On your iPhone, open the **Shortcuts** app (built-in, orange icon)
2. Tap the **+** in the top right to create a new shortcut
3. Tap **Add Action**
4. Search for **"Open URLs"** and select it
5. Tap the URL field and type:
   `https://[your-username].github.io/sara-saves?url=[URL]`
   — replace [URL] by tapping and inserting the **Shortcut Input** variable
   (tap the blue URL field, tap the variable icon, choose "Shortcut Input")
6. Tap the shortcut name at the top and rename it **Sara Saves**
7. Tap the **settings icon** (sliders) next to the name
8. Turn on **Show in Share Sheet**
9. Done — now when you tap Share on any page, "Sara Saves" appears in the list

---

## How to Use

**Paste method (for text, recipes, social posts):**
- Open Sara Saves from your home screen
- Tap + Save
- Paste anything
- Claude organizes it immediately

**Share Sheet method (for URLs/articles):**
- On any webpage, tap the Share button
- Tap Sara Saves in the share sheet
- The URL opens in the app ready to save

---

## Categories
Job Search, Querying, Recipes, Places, Kids, Writing Tips, People to Know
(Claude will suggest new ones as you go)
