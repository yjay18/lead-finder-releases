# Lead Finder — releases

Signed macOS builds of Lead Finder, and the manifest its in-app updater reads.

**There is no source code in this repository.** It exists only so that release
assets are reachable without a GitHub account: the app's updater and the client
portal both fetch from here anonymously, which a private repository cannot serve.

## Install

Download the latest `Lead-Finder-macOS-arm64.dmg` from
[Releases](https://github.com/yjay18/lead-finder-releases/releases/latest),
open it, and drag **Lead Finder** into Applications.

Apple Silicon, macOS 12 or later. The app is signed with a Developer ID
certificate and notarized by Apple, so a plain double-click works — no
right-click, no security warning.

## What each asset is

| Asset | Purpose |
|---|---|
| `Lead-Finder-macOS-arm64.dmg` | The installer. This is the one to download. |
| `Lead Finder.app.tar.gz` | Update payload, fetched by the app itself. |
| `latest.json` | Update manifest, fetched by the app itself. |

## Privacy

Lead Finder runs entirely on your Mac. Companies you scan, leads you save and
messages you draft never leave the machine, and the app never sends a message
or submits a form on its own — you approve every one.
