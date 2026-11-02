# Klipeo

Klipeo is an AI video editor. You describe the edit in plain words and its agent, Vibe, cuts, captions, zooms, and adds music and graphics on a real multi-track timeline that you can also edit by hand. It runs in the browser, as a native Mac app (screen recording with controls in the MacBook notch, native exports), on Android (iOS is coming), with a Chrome extension for recording, and with a local bridge CLI that lets your own Claude Code, Codex, Gemini CLI, or OpenCode drive Vibe.

This repository is Klipeo's public download page. The app source is not in this repository.

## Downloads

| Platform | Version | Download |
| --- | --- | --- |
| Web | Latest | [klipeo.com](https://klipeo.com) |
| macOS 14+ | 0.4.8 | [Klipeo.dmg](https://github.com/Klipeo-org/klipeo/releases/download/macos-v0.4.8/Klipeo.dmg) |
| Android 8.0+ | 0.1.1 | [Klipeo-0.1.1-android.apk](https://github.com/Klipeo-org/klipeo/releases/download/android-v0.1.1/Klipeo-0.1.1-android.apk) |
| Chrome extension | 0.1.0 | [klipeo-extension-0.1.0-chrome.zip](https://github.com/Klipeo-org/klipeo/releases/download/extension-v0.1.0/klipeo-extension-0.1.0-chrome.zip) |
| Bridge CLI | 0.1.5 | [bytehumi-klipeo-bridge-0.1.5.tgz](https://github.com/Klipeo-org/klipeo/releases/download/bridge-v0.1.5/bytehumi-klipeo-bridge-0.1.5.tgz) or `npm i -g @bytehumi/klipeo-bridge` |

All builds are listed on the [Releases](https://github.com/Klipeo-org/klipeo/releases) page.

## Install

**Mac.** Open the DMG and drag Klipeo to Applications. The build is not yet notarized, so on first launch open System Settings > Privacy & Security and click Open Anyway.

**Android.** Open the APK and allow installs from your browser when asked. Requires Android 8.0 or later.

**Chrome extension.** Unzip the file, open `chrome://extensions`, turn on Developer mode, click Load unpacked, and pick the unzipped folder.

**Bridge CLI.** Run `npm i -g @bytehumi/klipeo-bridge`, then run `klipeo`. You can also install the downloaded file with `npm i -g ./bytehumi-klipeo-bridge-0.1.5.tgz`.

## Links

- Website: https://klipeo.com
- Docs: https://klipeo.com/docs
- Changelog: https://klipeo.com/changelog

## Terms

The binaries are distributed under Klipeo's terms at https://klipeo.com/terms.
