# Wedding

Rachel & Xavier's wedding HQ: one shared planner for the April 22, 2027 elopement in the redwoods, the July 10, 2027 morning ceremony at Chapel Dulcinea, and that night's reception at The Betty.

Published as a Claude artifact: https://claude.ai/artifact/Xird27xUvYWHYDDxiZhJ85

- `index.html` is the page source. It is published as an artifact body, so it has no `<html>`/`<head>` wrapper of its own.
- `bg.jpg` is the background (the redwoods). `bg-blur.jpg` is a pre-blurred copy the glass surfaces show, pinned to the screen, in place of live `backdrop-filter` blur.
- `photos/` holds the engagement photos shown in the sidebar.

Tasks, budget, people and settings live in the artifact's shared database (`tasks`, `budget`, `people`, `settings/main`), not in this repo. The Inbox tab reads Gmail through the viewer's own connector, using the email addresses on the People tab.
