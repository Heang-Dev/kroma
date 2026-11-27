# Notes for AI agents

This repo (`Heang-Dev/kroma`) only holds **built output**: the installers in Releases, and the built website on the `gh-pages` branch. Don't change the website here. `gh-pages` is overwritten every time the site is published.

The website, its docs and the app are all edited in **`../KROMA.STUDIO`** (`Heang-Dev/KROMA.STUDIO`). Its `CLAUDE.md` explains how to release, and when the site and docs must be updated:

- **Every release** (patch, minor or major) updates the changelog, **first**: the version's section goes into `CHANGELOG.md` in `../KROMA.STUDIO` before the version is tagged. That section is the release's notes on this repo's Releases, and the site is republished so its Changelog shows it.
- **Minor or major releases** (0.1.x → 0.2.0) also update the docs: a new docs version and a full review of the site. Patches never change the docs.

Only two files here change by hand:
- `CHANGELOG.md`: a copy of `../KROMA.STUDIO/CHANGELOG.md`, copied over at every release. Never edit it here; edit the one in `KROMA.STUDIO` and copy it.
- `README.md`: update it at minor and major releases: its feature text, its screenshots, and any docs links that name a version.
