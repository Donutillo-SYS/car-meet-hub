# Car Meet Hub

Single-file web app for GTA Online car meets: create meets, add entries (player, car, screenshot), vote for the best car, set a voting deadline, enter Twitch vote counts, and see a Best Cars gallery and an all-time leaderboard.

## Files
- `index.html` — the whole app (HTML, CSS, JS and the background image are all inside)

## Important
Shared data (meets, votes, screenshots) comes from the Claude artifact runtime (`claude.use("db")`, `"assets"`, `"user"`). On GitHub Pages or any other host those aren't available, so this copy shows the design and the empty state only. The working app lives at the published Claude artifact link.

## View it
Open `index.html` in a browser, or enable GitHub Pages (Settings → Pages → deploy from the main branch, root folder).
