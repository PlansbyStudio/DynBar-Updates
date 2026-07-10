# DynBar-Updates

Public update feed for **[DynBar](https://github.com/PlansbyStudio/DynBar)** (the app repo is private).

- **`appcast.xml`** — the Sparkle feed the app checks for updates
  (`SUFeedURL` = `https://raw.githubusercontent.com/PlansbyStudio/DynBar-Updates/main/appcast.xml`).
- **Releases** — each app version is published here as a GitHub Release with a signed
  `DynBar-<version>.zip` asset. Because this repo is public, both the feed and the assets
  are reachable by every user's Sparkle updater.

Releases are produced from the private app repo via `scripts/release.sh` — do not edit
`appcast.xml` by hand.

> ⚠️ DynBar is **not notarized** (no Apple Developer Program). First-time users must
> right-click the app → **Open** once to get past Gatekeeper.
