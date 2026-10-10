# hdrezka-ng releases

Signed release builds of **hdrezka-ng**, an Android client for HDrezka for
Android TV, tablets and phones. This repository holds only the published
artefacts:

- `BUILD/hdrezka-ng-<version>.apk`: the current release, signed with the
  project's release key. Only the latest APK is kept.
- `BUILD/latest.json`: the manifest the app's built-in updater reads on launch.
  It names the version, the APK's URL and its sha256, and carries the release
  notes shown in the update prompt.

## Install

Download the current build from the stable link and sideload it:

    https://github.com/davidturchak/hdrezka-rebuild/releases/latest/download/hdrezka-ng.apk

It always points at the newest release. On Android TV, paste it into an app such
as Downloader. From then on the app offers updates itself. Older builds stay
under [Releases](https://github.com/davidturchak/hdrezka-rebuild/releases).

The source code lives in a separate, private repository.
