# Planetarium Architecture

## Layer 1 — Gecko / Firefox Platform

UNCHANGED BY DEFAULT

- Gecko
- SpiderMonkey
- Networking
- Media
- Storage
- Security
- WebExtensions
- DevTools
- Browser engine internals

## Layer 2 — Firefox Frontend

WHERE PLANETARIUM LIVES

- Browser chrome
- Home / New Tab
- Tabs
- Omnibox
- Bookmarks
- History
- Window frame
- Theme system
- Navigation transitions

## Layer 3 — Planetarium Interaction Model

- Center
- Orbit
- Stars
- Constellations
- Systems
- Starfield
- Atmospheres
- Micro-movement

## Current Boundary

Planetarium 0.x should require no Gecko engine modifications.
