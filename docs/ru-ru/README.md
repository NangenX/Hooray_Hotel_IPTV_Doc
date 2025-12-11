# Hooray IPTV Online Documentation

> Based on Hooray Hotel IPTV Platform v1.1.0_Release_Date_2025-03-10.

## Overview
This site documents how to configure and operate the Hooray Hotel IPTV management platform. It covers client/device setup, live/VOD configuration, ads and hotel services, system basics, and related integrations.

## Quick Local Preview
- Prerequisite: Node.js 16+ installed
- Install docsify CLI (once): `npm i -g docsify-cli`
- Start local preview: `docsify serve docs`
- Open in browser: `http://localhost:3000`

## Documentation Structure
- `index.html` — Docsify entry and global config
- `_coverpage.md` — Landing cover page
- `_navbar.md` / `_sidebar.md` — Top navigation and sidebar
- Feature guides — e.g. `quickstart.md`, `client_manage.md`, `live-setting.md`, `vod_setting.md`, `ads_setting.md`, `custom.md`, `flight.md`, `weather.md`, `facilities.md`, `authority.md`, `system.md`
- Assets — `_images/` for screenshots, `_media/` for favicon and examples
- `LICENSE` — License file

## Editing Guidelines
- Update the relevant `.md` file; save to see changes in local preview.
- Adding a new page: create the `.md`, then add its link to `_sidebar.md` (and `_navbar.md` if needed).
- Images: place under `_images/` and reference with relative paths.
- Keep terminology consistent; include clear steps and up-to-date screenshots when behavior changes.

## Deployment (GitHub Pages)
- Push to the default branch to publish via GitHub Pages.
- If running in restricted/offline environments, consider bundling CDN dependencies (Docsify, Prism, Vue) locally to improve reliability.

## Contributing
- Issues: report bugs, gaps, or requests.
- Pull Requests: welcome for typo fixes, new sections, and updated examples.
- Please include a brief change description and, when possible, screenshots for UI-related updates.

## Support
For questions about the IPTV platform or documentation improvements, open an issue or contact the maintainers through the project channel.