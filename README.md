# kiraaivn_frontend

Static chat UI ("Jarvis") for the Kira AI models. No build step — plain
HTML/CSS/JS, deployed on Vercel.

`/api/*` requests are proxied server-side to the backend
(`kiraaivn_backend`) via the rewrite in `vercel.json`, so the browser only
ever talks to this site's own domain — the backend's address and API key
stay off the client entirely.
