# Pomodoro Dial

A touch Pomodoro timer built for small landscape screens like the Echo Show 5 (960×480), installable as a PWA.

**Live:** https://whardier.github.io/pomodoro-pwa/

## Features
- Presets: a plain 30-minute Timer, then 25 Focus, 50 Deep, 5 Break, 15 Long
- Mode shows as strength, not hue: focus is solid, a plain timer a step more transparent, a break a step more again (dial arc, ring, main button, tab fill)
- Jog dial: touch to pause, turn clockwise to add time, counter-clockwise to remove it (5-second detents, 5 minutes per turn)
- Quick nudges: ±1, ±3, ±5, ±10, ±15 minutes, running or paused
- Outer ring lights up in the accent colour for the last quarter of the preset and breathes during the final minute
- Current time and the selected timer's local end time, aligned; while paused the end time keeps sliding later
- Three timers (red, orange, yellow) with rising chime pitches; idle tabs sit dim, running or expired tabs fill with their colour; tap a tab to put it on the dial
- Long break suggested after every 4th focus session
- A slow GPU-composited star field drifts behind the page at all times
- End chime (toggleable) and a half-brightness accent background until the time is touched; screen wake lock; full-screen button
- Timers keep counting across reloads
- Works offline once loaded

## Hosting
Served by GitHub Pages from the `main` branch root. When you change files, bump `VERSION` in `sw.js` so installed copies pick up the update.
