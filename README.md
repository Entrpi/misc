# misc

Odds and ends — standalone reports, sharable artifacts, and one-off documents
that don't belong inside a project repo but benefit from a stable URL.

Once GitHub Pages is enabled on this repo (Settings → Pages → branch `main` →
`/(root)`), every file is reachable at:

```
https://entrpi.github.io/misc/<path>
```

## Layout

One subdirectory per topic. Inside each topic, files are date-tagged when they
represent a snapshot of work that's expected to move on.

- `ds4/` — reports and notes related to the [ds4](https://github.com/antirez/ds4)
  inference engine and the [Entrpi/ds4](https://github.com/Entrpi/ds4) fork.

## Conventions

- Self-contained HTML preferred (inline CSS + inline SVG) so files render
  correctly on any static host without an asset pipeline.
- No build step. What lives in the repo is what gets served.
- Date-tagged file names (`*_YYYY-MM-DD.html`) for snapshot reports; un-dated
  names for living documents.
- Don't commit anything that wouldn't be fine on the public internet.
