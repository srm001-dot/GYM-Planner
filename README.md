# IRON//TRACK — Gym Planner

A mobile-first, dark themed, local-first gym schedule PWA.

## Features
- Your 6-day workout plan with sets/reps
- Separate primary and variation exercise days
- Exercise reference cards with Wikimedia Commons lookup/fallback
- Calendar with workout completion and gym attendance
- Entry/exit time calculator
- Weekly weight logging + chart
- Workout completion history
- Export/import JSON backup
- Installable as a PWA
- No backend and no login

## GitHub Pages
1. Create a new GitHub repository.
2. Upload all files from this folder.
3. Settings → Pages → Deploy from branch → `main` / root.
4. Open the generated Pages URL on your phone.
5. Use the browser menu → Add to Home Screen / Install App.

The app stores personal data in browser storage. Clearing site data can remove it, so use Export Backup periodically.

## Data model
Attendance, workouts, gym entry/exit logs, and weight history are stored locally in the browser using localStorage. No database or server is required. Use Export Backup regularly to keep a portable JSON copy.
