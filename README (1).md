# Classroom Group Maker

A single-file, client-side web app for randomly grouping students, with a "Who's Next?" picker and projector view. No build step, no server, no external dependencies — everything (HTML, CSS, and JavaScript) lives in `index.html`. All data (rosters, settings) is stored in the browser via `localStorage`/`indexedDB`, so nothing is sent to a server.

## Editing

Open `index.html` in any text editor and save — there's nothing to build or compile. To preview changes locally, just open the file in a browser, or run a tiny local server from this folder:

```
python3 -m http.server 8000
```

then visit `http://localhost:8000`.

## Deployment

This site is deployed on [Cloudflare Pages](https://pages.cloudflare.com/), connected to this GitHub repository. Every push to the `main` branch automatically redeploys the live site — no build command or output directory configuration needed (it's a single static HTML file).

Previously hosted on Netlify.
