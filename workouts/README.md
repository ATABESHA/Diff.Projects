# Workouts — iPhone PWA

A simple workout counter. Tap **+** next to a workout, type a number, save. Each entry stores date, time and count. Tap a workout to see Day / Week / Month / Year charts, stats and history.

## Install on iPhone
1. Open the GitHub Pages link in **Safari**.
2. Tap **Share → Add to Home Screen**.
3. Open it from the Home Screen icon — it runs full-screen and works offline.

## Features
- Workout list with today's total and a big **+** button per workout
- Numeric keypad entry with quick-pick of your recent amounts, plus Undo
- Charts: Day (by hour), Week, Month (by day), Year (by month); swipe or use arrows to go back in time; touch a bar for its value
- Stats: today, this week, this month, best day, best set, all time
- History grouped by day, with delete
- GIF per workout: pick from Photos/Files (saved inside the app) or paste a GIF link
- Units: reps, seconds, minutes, km
- Export / import backup (.json, includes GIFs)

Data is stored only on your phone (IndexedDB). Deleting the Home Screen app deletes its data, so export a backup now and then.

## Updating
After changing files, bump `VERSION` in `sw.js` so installed apps fetch the new version.
