# Roblox Chart Radar

A weekly scan of the Roblox charts (Top Trending, Up-and-Coming, Top Playing Now), updated every Friday by a scheduled task.

`latest.md` holds the current trends, risers, fallers, idea signals and icon and thumbnail patterns. It's rewritten every week.
`snapshots/YYYY-MM-DD.txt` holds the raw chart data, one line per game: `sort | rank | universeId | name | players | upvotes | downvotes | like% | genre`. Used to work out week-over-week changes.

Source: the public Roblox explore API and roblox.com/charts, US and computer filter, logged out. Only names and numbers are stored; no images are copied.
