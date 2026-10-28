# Jacobs Game Hub

🎮Jacobs Game Hub (JGH) is an unblocked games website made specifically for Jacob A, this website also contains a built in Ultraviolet web proxy and Apps 🕹

> ## This is owned by CybriaTech 10% and Jacob A Will Own 90% of it, meaning that I made it. He decides what will be in it.

## Deploying to Netlify

Netlify publishes the existing HTML, CSS, and images from `static/`. The
repository's `netlify.toml` overrides the dashboard build command and publish
directory. No compilation or Expo export is needed; this is not an Expo project.
Netlify installs dependencies automatically from `package.json` and
`package-lock.json`, so the build command does not need an extra `npm install`.

This deployment serves only the static site. The Node HTTP/WebSocket proxy in
`index.mjs` requires a separate compatible server host; it does not run on
Netlify's static hosting. Links to pages, games, or scripts that are absent from
`static/` also require those files to be added separately.
