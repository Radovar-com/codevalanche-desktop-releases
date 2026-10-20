# Codevalanche for Windows: releases

Codevalanche is a Windows desktop app that runs Claude Code, Codex and local models in one place.

This repository is where the app's installers and its update feed are published. It contains no application source code: Codevalanche itself is closed source.

**Download and release notes:** [codevalanche.com/download](https://codevalanche.com/download/) · [Changelog](https://codevalanche.com/changelog.html)

## What you will find here

- **Releases.** Each stable version of Codevalanche has a release on this page, with its Windows installer attached.
- **The update feed.** The app checks this repository for new versions and downloads its updates from here.

## How updates are verified

Every update is signed with the publisher's Ed25519 key. Before installing an update, Codevalanche checks that signature and refuses any update that does not match.

## First install on Windows

The installer is not yet signed with a Windows code-signing certificate. Because of that, Windows SmartScreen may show **"Windows protected your PC"** the first time you run it.

If you downloaded the installer from codevalanche.com or from this page, choose **More info**, check that the file name is the one you downloaded, then choose **Run anyway**. Updates installed from inside the app are checked with the Ed25519 signature described above.

## How the AI tools run

Codevalanche runs the official, unmodified command-line tools from each provider, signed in with your own account. Local models run on your own computer.

## Contact

- Security reports: [security@radovar.com](mailto:security@radovar.com). See [SECURITY.md](SECURITY.md).
- Everything else: [info@radovar.com](mailto:info@radovar.com)
- Updates on X: [@Codevalanche](https://x.com/Codevalanche)

Codevalanche is made by [Radovar](https://radovar.com).
