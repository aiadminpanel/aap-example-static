# aap-example-static

A minimal **static HTML** app, kept as a deploy example for [AI Admin Panel](https://aiadminpanel.com).

AI Admin Panel deploys it from this repository with **Git Deploy** (and **AI Deploy**) and checks
the result regularly: the page at `/` must contain the marker `aap-example:static`. Use it to see how
your own static HTML project is built, or as a starting point.

There is no build step and no server code: just `index.html` and `style.css`. This is what a hand-written landing page or an exported site builder page looks like.

- The app listens on `$PORT` (default 8080).
- No secrets in this repository.
- License: MIT.
