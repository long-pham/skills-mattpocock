---
"mattpocock-skills": patch
---

Add `.claude-plugin/marketplace.json` so this repo is discoverable as a native Claude Code / Claude Cowork plugin marketplace, not just via the skills.sh installer. Claude Cowork's Marketplace section adds plugins by finding a `marketplace.json` at the repo root — without one, it couldn't see this plugin even though `.claude-plugin/plugin.json` existed. Also fills out `plugin.json` with `description`, `author`, `homepage`, `repository`, and `license` metadata so the plugin card renders properly, and documents the `/plugin marketplace add` / Cowork install path in the README.
