# PebblePaste by HandyPebble

**Copy here. Paste there.**

Copy text, links, files, and folders on one Windows PC, then paste them on
another using your usual shortcuts. PebblePaste connects approved PCs on the
same private network without an account or cloud file storage.

- [Official product page and setup guide](https://handypebble.com/pebblepaste/)
- [Download PebblePaste 0.2.1 for Windows x64](https://handypebble.com/pebblepaste/downloads/PebblePaste-0.2.1-x64-setup.exe)
- [Send feedback](https://handypebble.com/pebblepaste-feedback/)
- [HandyPebble](https://handypebble.com/)

![Illustration of copying files between two nearby PCs; not an application screenshot](images/copy-paste-workflow.webp)

## How it works

1. Install the same version on both Windows 10/11 x64 PCs.
2. Join the same private Wi-Fi or Ethernet network.
3. Select the other PC, compare all six digits, and allow the connection on both
   screens. Trusted PCs can reconnect automatically.
4. Resume sharing on both PCs. Only new copies are shared.
5. Copy on one PC and paste on the other. For files and folders, use File
   Explorer. Once the copied selection reaches the other PC, you can start
   pasting before every file arrives. Windows handles copy progress, speed,
   cancellation, and naming conflicts.

Keep both PCs connected, running, and sharing until copying finishes. It is
always a copy, never a move. Pause sharing before copying private items.

## What is included

- Plain text and links, files, folders, and mixed file selections.
- Direct encrypted transfers between approved PCs on your local network.
- A tray menu, pause/resume controls, saved pairing, and optional reconnection.
- Explicit update checking and a separate feedback page.

Received files use a temporary local disk cache. These cache files are not
encrypted at rest. If copying is interrupted, destination files may remain;
PebblePaste does not delete them. Reconnect and copy again to restart the
transfer. This version does not resume halfway through a file.

Paths within a copied selection must be shorter than 260 characters. Folder
junctions and other reparse points are rejected. Rich text, clipboard images,
phones, macOS, and Windows 7 are not supported.

## Install or update

The approximately 209 MB installer includes Microsoft's offline WebView2
installer. You do not need Node, Rust, or a local server. Exit PebblePaste from
its tray menu before updating; updating preserves pairing and saved settings
by default. Update both PCs to the same version.

The installer is unsigned. Windows or workplace policy may warn about or block
it. Do not disable Windows security. Ask your administrator before installing
on a work or school PC.

SHA-256 for `PebblePaste-0.2.1-x64-setup.exe`:

```text
8501BB33C34C7590FB8B2F80A252B2BC329BE688C0F300F965E57D9092596FE4
```

## About this repository

This is the official **public product showcase**, not a source-code repository.
It contains only product information, release notes, and a product illustration.
Installers are hosted on HandyPebble. This page describes the currently published
0.2.1 release, not unfinished upgrades.

**Source code is not publicly available. Proprietary software. All rights reserved.**

See [release notes](CHANGELOG.md), [security reporting](SECURITY.md), and the
[rights notice](LICENSE-NOTICE.md).
