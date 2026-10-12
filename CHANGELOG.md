# Changelog

## 0.1.2

- `plugin.json` sets the documentation, support, privacy policy and terms URLs, so the directory listing doesn't read them from the README with the trailing full stop attached.
- README links are Markdown links.
- `.claude-plugin/icon.png` is the listing icon.

## 0.1.1

- Skills tell Claude to reconnect only on `401` or `AUTH003`. `AUTH004`, `AUTH014` and `AUTH006` are plan limits that reconnecting doesn't clear.
- `extract` skills also recognise `REQS007` for a domain Extract hasn't prepared.
- `getting-started` points to **Customize → Connectors** in Claude.
- Contact email is success@zenrows.com.

## 0.1.0

- First release: the Zenrows MCP server (OAuth sign-in) and nine skills: `using-zenrows`, `getting-started`, `scrape-webpage`, `extract-structured-data`, `batch`, `crawl`, `map`, `browser-automation` and `capture-api-calls`.
