# schoolwork-feed

Published feed for Dave Koch's private Schoolwork iOS app.

- `feed.json` — the live feed the app fetches:
  https://davekoch-buddy.github.io/schoolwork-feed/feed.json
- `packets/<test-slug>/` — original Classroom PDFs gathered per test,
  referenced by URL from the feed's packet manifests.

Feed schema and publishing rules live in the app repo
(`~/workspace/projects/school-app/FEED.md`): dedupe by stable item ID,
`firstSeenAt` never rewritten, no completion/missing state.
