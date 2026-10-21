# Kinesiology Course Engine Template

A zero-dependency, static web curriculum delivery engine built for higher education exercise science courses.

## Structure
- index.html: Dynamic course portal driven by content/manifest.json.
- viewer.html: Interactive modular lesson viewer with embedded activities tab.
- content/manifest.json: Central table of contents, course metadata, units, and chapters.
- content/ch{XX}/: Chapter folders containing lesson JSON ({XX.X}_content.json) and standalone HTML activities.
