# Deckhand

A macOS controller app for the **Mirabox Stream Dock N4**: ten LCD keys, four
knobs, and a four-panel touch strip, driven from your Mac.

This repository hosts Deckhand's signed, notarized downloads and its update
feed. Installed copies update themselves.

## Install

1. Download `Deckhand_<version>_aarch64.dmg` from the
   [latest release](https://github.com/DGSphp/deckhand-releases/releases/latest).
2. Open it and drag **Deckhand** to **Applications**.
3. Plug in your N4 and launch Deckhand.

Requires a Mac with Apple Silicon.

## Permissions

- **Accessibility**: needed for hotkey, type-text and media-key actions.
  Deckhand shows a banner on first launch; click **Grant Access**.
- **Automation**: macOS asks the first time an AppleScript action controls
  another app.
- **Notifications**: used to confirm each action you trigger from the deck.
