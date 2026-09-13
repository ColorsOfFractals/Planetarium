# Planetarium Development Log

Known-good Firefox source checkpoints used by Planetarium.

---

## 2026-09-12 23:37:28 — Establish borderless chrome and orbital window control

- Firefox branch: planetarium
- Firefox commit: 69ffea2ae1dd9d40dbb4f35c05769e3546a29fb4
- Subject: Planetarium: establish borderless chrome and orbital window control
- Patch: patches/firefox-69ffea2ae1dd.patch

### Recent Firefox checkpoints

```text
69ffea2ae1dd Planetarium: establish borderless chrome and orbital window control
297af50f5fda Planetarium: collapse vertical sidebar into invisible edge rail
5145c41d5a37 Planetarium: establish orbital new tab and native vertical sidebar shell
4becb68591bb planetarium: replace Firefox new tab with orbital shell
39dcc5beb77e Bug 2071588 - Rebase unpoison-thread-stacks patch for clang trunk after the section pragma GNUC guards. r=me
```

### Firefox tree state

```text
[clean]
```

### Checkpoint contents

```text
69ffea2ae1dd Planetarium: establish borderless chrome and orbital window control
 browser/base/content/browser.js          | 357 ++++++++++++++++++++++++++
 browser/themes/shared/browser-shared.css | 412 +++++++++++++++++++++++++++++++
 2 files changed, 769 insertions(+)
```

---


## 2026-09-13 01:54:03 — Restore Planetarium on clean Firefox artifact build

Firefox checkpoint recorded from the active development workbench.

- Branch: planetarium
- Commit: 32453cc9e4c79e4326d8a24a506efa2e63682168
- Subject: Restore Planetarium on clean Firefox artifact build
- Patch: patches/firefox-32453cc9e4c7-Restore-Planetarium-on-clean-Firefox-artifact-bu.patch

### Recent Firefox checkpoints

```text
32453cc9e4c7 Restore Planetarium on clean Firefox artifact build
69ffea2ae1dd Planetarium: establish borderless chrome and orbital window control
297af50f5fda Planetarium: collapse vertical sidebar into invisible edge rail
5145c41d5a37 Planetarium: establish orbital new tab and native vertical sidebar shell
4becb68591bb planetarium: replace Firefox new tab with orbital shell
```

### Firefox tree state

```text
[clean]
```

### Checkpoint contents

```text
32453cc9e4c7 Restore Planetarium on clean Firefox artifact build
 browser/base/content/browser.js                    | 242 +++++++++++
 .../unofficial/firefox.ico.pre-planetarium         | Bin 0 -> 200483 bytes
 .../components/Planetarium/Planetarium.jsx         | 234 ++++++++++-
 .../Planetarium.jsx.pre-constellation-mode         | 244 ++++++++++++
 .../Planetarium/Planetarium.jsx.pre-freeform       | 224 +++++++++++
 .../Planetarium/Planetarium.jsx.pre-orbit-drag     |  98 +++++
 .../Planetarium.jsx.pre-orbital-alignment          |  98 +++++
 .../components/Planetarium/Planetarium.scss        | 183 +++++++++
 .../Planetarium.scss.pre-constellation-mode        | 293 ++++++++++++++
 .../Planetarium/Planetarium.scss.pre-freeform      | 279 +++++++++++++
 .../Planetarium/Planetarium.scss.pre-orbit-drag    | 251 ++++++++++++
 .../Planetarium/Planetarium.scss.pre-radial-anchor | 215 ++++++++++
 browser/themes/shared/browser-shared.css           | 443 +++++++++++++++++++++
 13 files changed, 2788 insertions(+), 16 deletions(-)
```

---
