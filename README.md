# Marathon Tracker 🏃

A 24-week marathon training plan PWA — works offline, saves progress to your phone.

## Files included

```
index.html      ← the entire app (one file)
manifest.json   ← makes it installable as a home screen app
sw.js           ← service worker for offline support
icon-192.png    ← app icon (home screen)
icon-512.png    ← app icon (splash screen)
README.md       ← this file
```

---

## Deploy to GitHub Pages (free hosting)

### Step 1 — Create a GitHub account
Go to [github.com](https://github.com) and sign up if you haven't already.

### Step 2 — Create a new repository
1. Click the **+** in the top-right → **New repository**
2. Name it: `marathon-tracker` (or anything you like)
3. Set it to **Public**
4. Leave everything else as default
5. Click **Create repository**

### Step 3 — Upload the files
1. On your new repo page, click **uploading an existing file** (or drag and drop)
2. Upload all 5 files:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Scroll down and click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repo **Settings** tab
2. Scroll down to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Under **Branch**, select `main` and `/ (root)`
5. Click **Save**

### Step 5 — Get your URL
After ~60 seconds, refresh the Settings → Pages page.
Your app will be live at:
```
https://YOUR-USERNAME.github.io/marathon-tracker/
```

---

## Add to your iPhone home screen

1. Open the URL above in **Safari** (must be Safari, not Chrome)
2. Tap the **Share** button (box with arrow pointing up)
3. Scroll down and tap **Add to Home Screen**
4. Tap **Add**

The app will appear on your home screen like a native app — full screen, no browser bar, works offline, and saves your progress automatically.

## Add to Android home screen

1. Open the URL in **Chrome**
2. Tap the **⋮** menu → **Add to Home screen**
3. Tap **Add**

---

## Your progress is saved
All workout completions are stored in your phone's local storage — they persist between sessions and work offline once the app is cached.
