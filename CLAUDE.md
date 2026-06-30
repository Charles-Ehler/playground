# playground

Single-file static app: `index.html` (Tri-Tip Taco Bar prep/shopping/recipes planner). No build step, no server — open directly in a browser.

## Conventions

- `index.html` has an `APP_VERSION` constant near the top of the `<script>` block, displayed in the header next to "Camp Chef Woodwind · Serves 14". **Bump `APP_VERSION` by 1 every time `index.html` is edited** (any change, however small), so the version shown in the app always matches what's been changed. This is how the user tracks which version they're looking at.
