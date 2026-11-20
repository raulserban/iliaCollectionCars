# iliaCollection | Cars – automatic posting

Posts one car per day to Instagram @iliacollectioncars at 17:47 Bucharest time (backup run 19:17).

- `schedule.json`: cars 074–100, from 2026-11-19 to 2026-12-15, with captions (5 hashtags).
- `cars/NNN/1..5.jpg`: front, side, engine, interior, rear.
- `posted.json`: what was already posted (prevents double posts).
- Secret `IG_TOKEN`: Instagram access token for @iliacollectioncars.
- Manual test: Actions → Publish daily car → Run workflow (car number + "Test only").

## Cars of Nations (2027-01-10 → 2027-02-28)

Second series, posted by its own workflow (`.github/workflows/publish_nations.yml`) at the same time, 17:47 Bucharest.

- `schedule_nations.json`: cars 01–50, one per day from 2027-01-10 to 2027-02-28, with captions (5 hashtags).
- `Cars of Nations/NNN Country/1..5.jpg`: cover, story, data sheet, industry map, legacy.
- `posted_nations.json`: what was already posted for this series.
- Manual test: Actions → Publish Cars of Nations → Run workflow (car number + "Test only").
