# Wedding

Rachel & Xavier's wedding HQ: one shared planner for the April 22, 2027 elopement in the redwoods and the July 9, 2027 reception at The Betty.

Published as a Claude artifact: https://claude.ai/artifact/Xird27xUvYWHYDDxiZhJ85

- `index.html` is the page source. It is published as an artifact body, so it has no `<html>`/`<head>` wrapper of its own.
- `bg.jpg` is the default background (the redwoods). Any album photo can replace it.
- `photos/` holds the engagement photos that ship with the album. Photos added in the page are stored with the artifact.

Tasks, budget, people, photos and settings live in the artifact's shared database (`tasks`, `budget`, `people`, `photos`, `settings/main`), not in this repo. The Inbox tab reads Gmail through the viewer's own connector, using the email addresses on the People tab.
