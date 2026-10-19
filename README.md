# MyShift

A personal time clock, timesheet, to-do list, and reminder app that runs in your browser and syncs to the cloud.


## Features

- **Time clock** — Clock in and out with live elapsed time tracking
- **Multiple punches per day** — Clock out for lunch, clock back in; breaks are tracked automatically
- **Timesheet** — Weekly summaries with net hours, break time, daily balance, and 4-week trends
- **To-do list** — Add, complete, and clear tasks
- **Reminders** — Set one-time alerts with quick presets (lunch, clock-out check, end of day)
- **Cloud sync** — Connect Supabase (free) or any REST endpoint to keep data synced across devices
- **PWA** — Install as a standalone app on desktop and mobile
- **Dark mode** — Toggle between light and dark themes
- **Export** — CSV timesheet export and JSON backup/restore

## Default schedule

10 hours/day, Monday–Friday (50-hour week). Change this in Settings anytime.

## Quick start

1. Open `index.html` in any modern browser
2. Your data saves locally automatically
3. Go to **Settings & cloud** to connect a database for cross-device sync

## Cloud sync setup (Supabase)

1. Create a free project at [supabase.com](https://supabase.com)
2. Open the **SQL Editor**, paste the SQL from the app's Settings panel, and run it
3. Copy your **Project URL** and **anon public key** from Project Settings → API
4. Paste them into the app, press **Test connection**, then **Push to cloud**
5. On your other device, enter the same details and press **Pull from cloud**

## File structure

```
myshift/
├── index.html          # The entire app (single file)
└── README.md           # This file
```

## Data privacy

Your data is stored in your browser's localStorage first, then mirrored to your own database only when you enable cloud sync. The app does not send data anywhere else.

## Install as an app

### Desktop (Chrome/Edge)
Click the **Install app** button in the header, or use the browser menu → Install MyShift.

### iPhone (Safari)
Tap the share button → **Add to Home Screen**.

### Android (Chrome)
Tap the menu → **Add to Home screen**.

## Keyboard shortcuts

- The app is fully keyboard-navigable
- Tab through fields, Enter to activate buttons
- All actions have visible focus indicators

## Browser support

- Chrome / Edge (recommended)
- Firefox
- Safari
- Mobile browsers (iOS Safari, Chrome Android)

## Copyright

© 2026 Ryan Francis Camacho Romano