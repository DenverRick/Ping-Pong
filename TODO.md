# Ping Pong Tracker – TODO

Live: https://ping-pong-tracker.netlify.app (deploys from `main` on GitHub)

## Done (2026-09-04)
- Extracted the Gemini output into a real `index.html` (the first commit had an empty file).
- Fixed reload after a win re-showing the same game (double-counted wins).
- Setup screen groups players by starting end (North / South).
- Game header shows Round · Game N of 3; team cards show that pair's running record.
- Rankings show Players and Teams tables (wins and games played), derived from a results log.
- Default names: Carl, Rick, Rico, Rich.

## Next
- Undo last result (mis-tap recovery) on the rankings screen.
- App icon, manifest, and iOS home-screen metadata.
- Optional: history of games played this session.
