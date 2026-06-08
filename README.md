# familyplan

A shared family planner for Bhavan and Mom — WFG client meetings, follow-ups, and reminders.

---

## Files

```
familyplan/
├── index.html      ← the whole app
├── manifest.json   ← PWA config
├── sw.js           ← service worker (offline support)
├── icon-192.png    ← app icon
├── icon-512.png    ← app icon (large)
└── README.md
```

---

## Deploy to GitHub Pages (free hosting)

1. Go to github.com and create a free account if you don't have one
2. Click **New repository** — name it `familyplan`, set it to Public
3. Upload all files in this folder (drag and drop them onto the repo page)
4. Go to **Settings → Pages**
5. Under "Source" select **Deploy from a branch**, pick `main`, folder `/root`
6. Click Save — your app will be live at:
   `https://YOUR-USERNAME.github.io/familyplan`

Share that link with Mom and you're both set.

---

## Add to iPhone home screen (both of you do this)

1. Open the link above in **Safari** (must be Safari, not Chrome)
2. Tap the **Share button** (the box with an arrow pointing up)
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **Add** in the top right
5. The app icon appears on your home screen — tap it to open full screen

> Reminders work on iOS 16.4+ when opened from the home screen icon.

---

## Export to Apple Calendar

Tap the **Export** tab at the bottom → tap the export button → open the `.ics` file → Apple Calendar imports all events automatically. Reminders are included.

---

## Tips

- Tap any time slot on the calendar to add an event there
- Events save automatically to your device
- Each person's data is stored on their own phone — the `.ics` export is how you share with Apple Calendar
