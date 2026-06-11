# Fala — releases

Public download and auto-update host for the **Fala** macOS app. Source code lives in the
private `LeapLane/fala` repo; only signed, notarized release artifacts and update manifests
are published here.

## Download

**[Download Fala for macOS](https://github.com/LeapLane/fala-releases/releases/download/stable/Fala.dmg)**
(universal, Intel + Apple Silicon). Open the `.dmg`, drag **Fala** to **Applications**, launch it.

## Channels

Auto-updates are delivered per channel via a rolling release whose tag is the channel name:

| Channel  | Audience        | Manifest |
|----------|-----------------|----------|
| `stable` | everyone        | `releases/download/stable/latest.json` |
| `dev`    | internal        | `releases/download/dev/latest.json` |

Assets on each channel release are overwritten on every publish, so the URLs above are permanent.