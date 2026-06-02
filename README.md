# The Plan — Daily Briefing PWA

A personal self-improvement tracker built as a Progressive Web App.

## Deploy to GitHub Pages (5 minutes)

### Step 1: Create a new repository
1. Go to [github.com/new](https://github.com/new)
2. Name it `the-plan` (or whatever you like)
3. Make it **Private** (this is personal)
4. Click **Create repository**

### Step 2: Upload the files
1. On your new empty repo page, click **"uploading an existing file"**
2. Drag and drop ALL of these files/folders:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icons/` (the whole folder with 3 image files)
3. Click **Commit changes**

### Step 3: Enable GitHub Pages
1. Go to your repo's **Settings** tab
2. Click **Pages** in the left sidebar
3. Under "Source", select **Deploy from a branch**
4. Select **main** branch, **/ (root)** folder
5. Click **Save**
6. Wait 1-2 minutes, then your site will be live at:
   `https://YOUR-USERNAME.github.io/the-plan/`

### Step 4: Add to your phone's home screen
#### iPhone (Safari):
1. Open your GitHub Pages URL in **Safari**
2. Tap the **Share** button (square with arrow)
3. Scroll down and tap **Add to Home Screen**
4. Name it "The Plan" and tap **Add**
5. It now appears as an app with the gold TP icon

#### Android (Chrome):
1. Open your GitHub Pages URL in **Chrome**
2. Tap the **three dots** menu
3. Tap **Add to Home screen** or **Install app**
4. It now appears as an app

## How to use

- **Morning**: Open the app, review today's habits
- **Throughout the day**: Check off items as you complete them
- **Evening**: Complete evening habits, journal prompt, check tomorrow's preview
- **Sunday**: Switch to Weekly Review tab, fill in reflections

## Files
```
the-plan/
├── index.html          # The app (everything in one file)
├── manifest.json       # PWA config (app name, icon, theme)
├── sw.js               # Service worker (offline + caching)
├── icons/
│   ├── icon.svg        # Source icon
│   ├── icon-192.png    # Android icon
│   ├── icon-512.png    # Splash screen icon
│   └── apple-touch-icon.png  # iOS icon
└── README.md           # This file
```

## Updating
To change habits, prompts, or settings: edit `index.html`, commit to GitHub, 
and the site updates automatically. Clear your browser cache or wait for the 
service worker to refresh (~24 hours).
