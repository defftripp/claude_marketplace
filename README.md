# Claude Marketplace

Public marketplace repository for the `seedance-video` Claude plugin.

## Public Seedance URLs

- Home: `https://seedance-video.duckdns.org/`
- Pricing: `https://seedance-video.duckdns.org/pricing`
- Dashboard: `https://seedance-video.duckdns.org/dashboard?email=you@example.com`
- Docs: `https://seedance-video.duckdns.org/docs`

## Install in Claude Code

```text
/plugin marketplace add defftripp/claude_marketplace
/plugin install seedance-video
```

## Plugin config

- `api_endpoint`: `https://seedance-video.duckdns.org`
- `api_token`: personal `svk_...` token from the dashboard after checkout

## What this repo contains

- `.claude-plugin/marketplace.json`
- `plugins/seedance-video/.claude-plugin/plugin.json`
- `plugins/seedance-video/.mcp.json`
- plugin skills

Backend code and storefront live in a separate repository.
