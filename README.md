# Routine — Your Daily Schedule App

A dark academia-styled Progressive Web App showing your half-hourly schedule at a glance.

---

## How to install on Android (Chrome)

1. **Upload all files to a free host** — the easiest option is GitHub Pages (free, takes ~2 minutes):

   a. Go to https://github.com and sign in (or create a free account)
   b. Click the **+** button → **New repository**
   c. Name it `routine-app`, set it to **Public**, click **Create repository**
   d. Click **uploading an existing file**, drag all the files into the window:
      - `index.html`
      - `manifest.json`
      - `sw.js`
      - `icons/icon-192.png`
      - `icons/icon-512.png`
   e. Click **Commit changes**
   f. Go to **Settings → Pages**, set source to **main branch / root**, click **Save**
   g. Your app will be live at: `https://YOUR-USERNAME.github.io/routine-app`

2. **Add to your Android home screen:**
   a. Open the URL above in **Chrome** on your Android phone
   b. Tap the **⋮ three-dot menu** (top right)
   c. Tap **Add to Home screen**
   d. Tap **Add** — the app icon appears on your home screen
   e. Open it — it runs full-screen with no browser chrome, just like a native app

---

## Features

- Shows your **current half-hour slot** with live progress bar and countdown
- Shows the **next 2 upcoming slots**
- **Day-at-a-glance timeline** colour-coded by activity type
- **Day tabs** to preview any day of the week
- **Full schedule toggle** to see the whole day's list
- **Works offline** once installed (service worker caches everything)
- Updates every 10 seconds

---

## Updating your schedule

If you want to change your routine, open `index.html` in any text editor, find the `SCHEDULE` object near the bottom, and edit the activity names. Each entry is `[hour, minute, "Activity name"]`.

---

Built with dark academia energy. ✦
