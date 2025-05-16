# rubicon-kometa-assets

_A curated collection of custom overlays, posters, templates, and playlist artwork for use with [Kometa](https://github.com/Kometa-Team/Kometa). Maintained by RubiconTV to support structured, stylized, and standards-compliant media organization in Plex and Jellyfin environments._

---

## Project Status

> **Work in Progress**  
> This repository is actively under development. Most `.yaml` configuration and collection files are currently placeholders or stubs intended to scaffold future development. However, the project already includes a complete set of **ESRB-style age-based poster images** designed for parental guidance collections.

---

## Included Resources

### ✅ Ready-to-Use Assets

- **Poster Images**  
  ESRB-inspired, high-contrast, age-rating style posters for the following collection labels:
  - Preschool (Ages 2–4)
  - Little Kids (Ages 5–7)
  - Big Kids (Ages 8–9)
  - Tweens (Ages 10–12)
  - Teens (Ages 13–15)
  - Older Teens (Ages 16–17)
  - Adults (Ages 18+)

---

## Directory Structure

```text
.
├── config/                # Core configuration files (config.yaml, settings, schedules)
├── collections/
│   ├── Movies/            # Collection YAMLs for movies
│   └── TV/                # Collection YAMLs for TV shows
├── docs/                 # Usage guides and project documentation
├── images/
│   ├── posters/           # Poster images organized by type (kids, franchise, etc.)
│   └── backgrounds/       # Background art
├── overlays/              # Overlay artwork and YAMLs
│   └── badge/             # ESRB-style or badge overlays
├── playlists/             # Playlist-specific YAML configurations
├── scripts/               # Utility scripts for syncing and automation
└── templates/             # Collection, overlay, and playlist templates


⸻

Usage Instructions
	1.	Clone this repository to your Kometa host machine.
	2.	Reference the desired YAMLs and assets in your Kometa config.yaml using Git paths or local mount paths.
	3.	Use posters or overlays in collections via url_poster: or url_background: keys.
	4.	Customize the template files to fit your media taxonomy or style preferences.

⸻

License

This project is licensed under the MIT License unless otherwise specified. Individual assets (like posters) may have alternate usage rights—please refer to the comments in their respective folders.

⸻

About RubiconTV

RubiconTV develops and maintains modern, automated, and standards-compliant tools and visual assets to streamline media organization for Plex, Jellyfin, and other open-source platforms. For more, visit rubicontv.com.
```
