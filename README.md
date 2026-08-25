# Sonira

**Voice-to-text for the Mac that turns speech into clean, ready-to-send writing, in every app.**
Hold one key, say what you mean, and the finished sentence lands where the cursor is. The
filler words, the false starts and the "no wait, scratch that" are gone before you see the text.

Sonira speaks English, European Portuguese and Brazilian Portuguese as three different
languages, not one bucket. The cleanup pass is forbidden from converting one variant into
another, or from formalising how you actually talk.

**[sonira.app](https://sonira.app)** has the full story, plus guides on dictating on a Mac,
dictating in English with an accent, and the difference between European and Brazilian
Portuguese dictation.

This repository hosts the public download and the auto-update manifests. The source code lives
in the private `LeapLane/sonira` repo, so only signed, notarized release artifacts are published
here.

## Download

**[Download Sonira for macOS](https://github.com/LeapLane/sonira-releases/releases/download/stable/Sonira.dmg)**
(universal, Intel + Apple Silicon). Open the `.dmg`, drag **Sonira** to **Applications**, launch it.

Free while in beta. Windows is next.

On first launch Sonira walks you through the two macOS permissions it needs: Accessibility and
Input Monitoring, so the hold-to-talk key works, and microphone access. Nothing is dictated
until you hold the key.

## Channels

Auto-updates are delivered per channel via a rolling release whose tag is the channel name:

| Channel  | Audience        | Manifest |
|----------|-----------------|----------|
| `stable` | everyone        | `releases/download/stable/latest.json` |
| `dev`    | internal        | `releases/download/dev/latest.json` |

Assets on each channel release are overwritten on every publish, so the URLs above are permanent.

## Issues

Bug reports and feature requests are welcome in this repository's issue tracker. The private
source repo is where they get fixed.
