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
