# Rex Mundi — downloads

The built archives for [Rex Mundi](https://rexmundi.vercel.app), a
geopolitical sandbox where your own coding agent is the game master.

This repository holds releases and nothing else: no source, no issues. Get
the game from the [download page](https://rexmundi.vercel.app), or from
the [latest release](../../releases/latest) directly:

| | |
|---|---|
| Windows | [rexmundi-windows-x64.zip](../../releases/latest/download/rexmundi-windows-x64.zip) |
| macOS (Apple silicon) | [rexmundi-macos-arm64.tar.gz](../../releases/latest/download/rexmundi-macos-arm64.tar.gz) |
| macOS (Intel) | [rexmundi-macos-x64.tar.gz](../../releases/latest/download/rexmundi-macos-x64.tar.gz) |
| Linux | [rexmundi-linux-x64.tar.gz](../../releases/latest/download/rexmundi-linux-x64.tar.gz) |

Unpack the archive and keep its files together: the game reads its map,
its agent tool and SDL from beside the executable. After that it updates
itself — the version along the foot of its menu opens an Updates page.

The other files on a release are for that updater: `latest.json` describes
the newest version, `rexmundi-<platform>-program.tar.gz` is the game
without the map, and `rexmundi-assets.tar.gz` is the map on its own, so a
usual update is two megabytes rather than a hundred.
