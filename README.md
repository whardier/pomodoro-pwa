# Pomodoro Dial

A touch Pomodoro timer built for small landscape screens like the Echo Show 5 (960×480), installable as a PWA.

**Live:** https://whardier.github.io/pomodoro-pwa/

## Features
- Presets: 25 Focus, 50 Deep, 5 Break, 15 Long
- Jog dial: touch to pause, turn clockwise to add time, counter-clockwise to remove it (5-second detents, 5 minutes per turn)
- Quick nudges: ±1, ±3, ±5 minutes, running or paused
- Session dots with a long break after every 4th pomodoro
- End chime and dial clicks (toggleable), screen wake lock, full-screen button
- Works offline once loaded

## Hosting
Served by GitHub Pages from the `main` branch root. When you change files, bump `VERSION` in `sw.js` so installed copies pick up the update.
