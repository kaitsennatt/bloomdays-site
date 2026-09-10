# Bloom Days — marketing site

Static site, no build step. `index.html` plus `work/` (anonymized sample packets).

- `index.html` → https://bloomdays.co
- `work/*.html` → the three sample packets linked from "See the work"

## Publishing
GitHub Pages, `main` branch, root. `CNAME` holds `bloomdays.co`.
To update: edit the files, then `git add . && git commit -m "..." && git push`. Live in about a minute.

## Not the same as the clients repo
`kaitsennatt/bloomdays` serves clients.bloomdays.co and holds REAL packets with client
names and addresses. This repo is public-facing: the packets in `work/` are anonymized
copies. Keep the two straight — never copy a client packet in here without stripping it first.

## The form
Posts to Formspree (`xqpkpebb`). Free tier is 50 submissions/month.
Hidden `_gotcha` field is a spam honeypot; leave it in place.
