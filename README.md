# My Tracker

A personal productivity web app — day and weekly planning with cloud sync.

**Live:** https://skimanz-tracker.netlify.app

## Features
- Day Tracker with focus, events, and tasks
- Live donut ring chart (task completion)
- Weekly overview — current week + next week
- Week 1–52 selector
- Firebase cloud sync (real-time, cross-device)
- Export / Import JSON backup

## Stack
- Single `index.html` — HTML, CSS, JS inline
- Firebase Auth (email/password)
- Firebase Firestore
- Hosted on Netlify (auto-deploy from GitHub)

## Updating
1. Edit `index.html`
2. Go to GitHub → click file → pencil icon
3. Select all → delete → drag new file in
4. Commit → Netlify deploys in ~30 seconds
