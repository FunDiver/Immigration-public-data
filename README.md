# Thailand Expat Assistant public data

This repository holds **public, read-only data** for the app. The editorial source is kept in a separate private repository. No user profile, saved date, location, token, or other personal data belongs here.

[`status.json`](status.json) reports whether a verified holiday feed is available. It currently says `awaiting_verified_notices`: this describes the **app feed**, not whether a Thai immigration office is open or closed on any particular day.

The app-compatible `config.json` and `data/holidays.vN.json` will be published only after specific closure notices from the Thai Immigration Bureau or its local offices are verified. Each published entry must link to its official notice. The static feed is informational and cannot replace a call to the relevant office before travel.

The GitHub Pages endpoint is intended to be `https://fundiver.github.io/Immigration-public-data/`. Verify the live URL before configuring the app to use it.
