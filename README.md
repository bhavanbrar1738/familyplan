# familyplan — with real-time sync

Shared family planner for Bhavan and Mom. Events sync instantly between both phones via Supabase.

---

## Files

```
familyplan-sync/
├── index.html      ← the whole app
├── manifest.json   ← PWA config
├── sw.js           ← service worker (offline support)
├── icon-192.png    ← app icon
├── icon-512.png    ← app icon (large)
└── README.md
```

---

## Deploy to GitHub Pages (free)

1. Go to github.com → create a free account
2. Click **New repository** → name it `familyplan` → set to **Public**
3. Drag and drop all 6 files from this folder onto the repo page
4. Go to **Settings → Pages**
5. Under Source: select **Deploy from a branch** → pick `main` → folder `/root` → Save
6. Your app is live at: `https://YOUR-USERNAME.github.io/familyplan`

Share that link with Mom — you're both using the same app and same database.

---

## Add to iPhone home screen (both of you do this)

1. Open the link in **Safari** (must be Safari, not Chrome)
2. Tap the **Share button** (box with arrow pointing up)
3. Tap **"Add to Home Screen"**
4. Tap **Add**
5. The familyplan icon appears on your home screen

---

## How sync works

- The green dot at the top means you're live and connected
- When you add or edit an event, it saves to Supabase instantly
- Mom's phone receives the change in real time — no refresh needed
- If you go offline, the dot turns red — changes sync when you reconnect

---

## Export to Apple Calendar

Tap the **Follow-ups tab** → tap the export button → open the `.ics` file →
Apple Calendar imports all events with reminders included.

---

## Reminders

Reminders fire as notifications at your chosen time before each event.
On iPhone this works when the app is opened from the home screen icon (iOS 16.4+).
