# iliaCollection | Cars – automatic posting

Posts one car per day to Instagram @iliacollectioncars at 17:47 Bucharest time (backup run 19:17).

- `schedule.json`: cars 074–100, from 2026-11-19 to 2026-12-15, with captions (5 hashtags).
- `cars/NNN/1..5.jpg`: front, side, engine, interior, rear.
- `posted.json`: what was already posted (prevents double posts).
- Secret `IG_TOKEN`: Instagram access token for @iliacollectioncars.
- Manual test: Actions → Publish daily car → Run workflow (car number + "Test only").
