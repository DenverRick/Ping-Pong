# Ping Pong Tracker – TODO

Live: https://ping-pong-tracker.netlify.app (deploys from `main` on GitHub)

## Done (2026-09-04)
- Extracted the Gemini output into a real `index.html` (the first commit had an empty file).
- Fixed reload after a win re-showing the same game (double-counted wins).
- Setup screen groups players by starting end (North / South).
- Game screen is a top-down table: North end at the top, South at the bottom, each end showing its two players and running record; tap the end that won.
- Rankings show Players and Teams tables (wins and games played), derived from a results log.
- Default names: Carl, Rick, Rico, Rich.
- App icon (red paddle + white ball on navy), web manifest, and iOS home-screen metadata (standalone, title "Ping Pong").
- Undo: "Wrong end?" link on the rankings screen reverts the tap just made; "Undo last game's result" on the game screen reopens the previous game.

## Next
- Optional: history of games played this session.
