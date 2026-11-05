# CodinGame dashboard

Where techmoocher's CodinGame bots stand: each project's league, rank and
ranking progress, and how much work is open or done.

Live: <https://techmoocher.github.io/codingame-dashboard/>

- `index.html` renders `data.json` in the browser. There is no build step.
- `data.json` is written by a script in our private repo after each submit
  and once a rank settles, through the GitHub API. Edits made here are
  overwritten.
- Code, strategy and task details stay private while a contest runs:
  CodinGame forbids sharing contest code before a contest ends.
