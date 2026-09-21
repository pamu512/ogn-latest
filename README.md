# Only Good News — latest issue

[https://pamu512.github.io/ogn-latest/](https://pamu512.github.io/ogn-latest/) always redirects to the latest public Buttondown issue.

The Instagram bio stays on that URL forever. Do not change the bio after issue 1.

Subscribe lives at [https://buttondown.com/onlygoodnews#subscribe-form](https://buttondown.com/onlygoodnews#subscribe-form).

## After each Sunday Buttondown publish

1. Publish the issue in Buttondown and copy its public permalink.
2. Edit `TARGET` in `index.html`: the comment, the `meta http-equiv="refresh"` URL, and the JS `TARGET` constant. All three must be the same permalink.
3. Commit and push to `main`.

Until issue 1 exists, `TARGET` is the temporary landing: `https://buttondown.com/onlygoodnews`.

## Enable GitHub Pages (one click)

`gh` cannot turn Pages on from this environment. In the repo:

**Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `/ (root)` → Save**

The site URL is [https://pamu512.github.io/ogn-latest/](https://pamu512.github.io/ogn-latest/).
