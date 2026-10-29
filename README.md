# Blackwork Elements for macOS

Blackwork Elements is the desktop app of [Blackwork](https://blackwork.pro): a curated archive of historical engravings, illustrations and visual references for artists, designers and researchers. Browse and search the archive, keep favourites and boards, and drag artwork straight into your design tools.

This repository only hosts the downloads. The app's source code is not public.

## Preview

The macOS app is a **preview**. It is signed, but not yet notarized by Apple, so macOS asks you to confirm the first launch (see [Install](#install)). Updates are manual for now: download the newer version from [Releases](https://github.com/nomadvisuals/blackwork-elements-releases/releases).

Windows and Linux versions will follow.

## Download

Open the [latest release](https://github.com/nomadvisuals/blackwork-elements-releases/releases/latest) and pick the file for your Mac:

| Your Mac | File |
|---|---|
| Apple Silicon (M1 or newer) | `Blackwork-Elements-<version>-arm64.dmg` |
| Intel | `Blackwork-Elements-<version>-x64.dmg` |

Not sure? Apple menu → **About This Mac**. "Chip: Apple M…" means Apple Silicon; "Processor: Intel…" means Intel.

Requires macOS 13 Ventura or later.

## Install

1. Open the downloaded `.dmg` and drag **Blackwork Elements** into **Applications**.
2. Open **Applications** and double-click **Blackwork Elements**. macOS says that "Blackwork Elements" could not be opened, with the buttons **Done** and **Move to Trash** (**Move to Bin** on British English macOS).
   - Click **Done**. **Do not click Move to Trash / Move to Bin.**
3. Open **System Settings → Privacy & Security**, scroll down to **Security** and click **Open Anyway** next to the message about Blackwork Elements. Confirm with your password or Touch ID.
4. The app opens. Later launches open normally, without this step.

If macOS says the app "is damaged and can't be opened", don't open it: delete it and download it again from this page. If it happens again, write to us at hello@blackwork.pro.

## Check the download (optional)

Every release has a `SHA256SUMS.txt` file. In Terminal:

```sh
cd ~/Downloads
shasum -a 256 Blackwork-Elements-<version>-arm64.dmg
```

The printed value must be the same as the line for that file in `SHA256SUMS.txt`.

## Privacy, terms and support

- Privacy: https://blackwork.pro/privacy
- Terms: https://blackwork.pro/terms
- Support: hello@blackwork.pro
- Security issues: see [SECURITY.md](SECURITY.md)

## Licence

Blackwork Elements is proprietary software. © 2026 Blackwork. All rights reserved. See [TERMS.md](TERMS.md).
