# Buff Games

Landing site and policy hub for Buff Games.

## Scope

This repository is for the web presence only:

- public landing pages
- game links
- privacy and support pages
- Cloudflare deployment setup

Game source code lives in separate repositories, starting with `flapsc/Glowstride`.

## Domain

Primary domain: `buffgames.app`

## Local Preview

```bash
python3 -m http.server 4173 --directory web
```

Open `http://127.0.0.1:4173`.

## Cloudflare Pages

- Build command: none
- Output directory: `web`
- `wrangler.toml` sets `pages_build_output_dir = "web"`
