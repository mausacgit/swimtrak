# SWIMTRAK — Setup Guide

## Files in this repository

```
index.html          ← Aquaknights tracker
manifest-aq.json    ← Aquaknights PWA config
icon-aq.png         ← Aquaknights home screen icon (navy)

team2/
  index.html        ← IPSC tracker

manifest-ipsc.json  ← IPSC PWA config
icon-ipsc.png       ← IPSC home screen icon (green)
```

---

## One-time GitHub Pages setup

1. Go to your repository on github.com
2. Click **Settings** → **Pages** (left sidebar)
3. Under "Source", select **Deploy from a branch**
4. Set branch to **main**, folder to **/ (root)**
5. Click **Save**
6. Wait ~2 minutes, then your URLs will be:
   - `https://YOUR-USERNAME.github.io/REPO-NAME/` → Aquaknights
   - `https://YOUR-USERNAME.github.io/REPO-NAME/team2/` → IPSC

---

## Installing to iPhone Home Screen

### Aquaknights
1. Open `https://YOUR-USERNAME.github.io/REPO-NAME/` in **Safari**
2. Tap the **Share** button (box with arrow at the bottom)
3. Tap **Add to Home Screen**
4. Name it **Aquaknights** → tap **Add**

### IPSC
1. Open `https://YOUR-USERNAME.github.io/REPO-NAME/team2/` in **Safari**
2. Tap the **Share** button
3. Tap **Add to Home Screen**
4. Name it **SWIMTRAK IPSC** → tap **Add**

Both apps install as separate icons. Data is completely separate between teams.

---

## Updating the app

When you get an updated `.html` file:
1. Go to your repository on github.com
2. Click on `index.html` (or `team2/index.html`)
3. Click the **pencil/edit** icon
4. Click **"Upload file"** instead and replace it
5. Commit the change
6. Open the app on your phone — it updates automatically on next load

---

## Moving data between Mac and iPhone

### Mac → iPhone
1. Open the app on Mac, go to **Overview → Export data**
2. A `.json` file downloads
3. AirDrop it to your iPhone
4. Open the app on iPhone, go to **Overview → Import data**
5. Select the `.json` file

### iPhone → Mac
Same process in reverse.
