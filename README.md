# Yuzu releases

This repository contains **release binaries and update metadata** for Yuzu.
Source development stays in the private repository `pietroMastro92/yuzu`.

## Download

Download the latest universal build from the
[releases page](https://github.com/pietroMastro92/yuzu-releases/releases/latest):

- `Yuzu-<version>-universal.zip`
- `Yuzu-<version>-universal.dmg`
- `SHA256SUMS.txt`
- `updates.json`

The app is universal (`arm64 + x86_64`) and supports macOS 14 or later.

## Gatekeeper

Yuzu is ad-hoc signed and **not notarized by Apple**. macOS will block the first
launch. Right-click `Yuzu.app` → **Open** → **Open**, or run:

```bash
xattr -dr com.apple.quarantine /Applications/Yuzu.app
```

Use at your own risk. There is no Apple support or warranty.

## Updates

Yuzu checks `updates.json` / the latest GitHub release and offers the update to
the user (Download, Later or Skip). Downloads are verified against the SHA-256
in `updates.json` when present. Installation is guided because the sandboxed,
unsigned app cannot replace `/Applications/Yuzu.app` in place.

## Licenses

Bundled third-party and compatibility components keep their own licenses.
See `THIRD-PARTY.md` and `LEGAL.md`. The Tangerine compatibility components are
included with the owner's authorization; public redistribution may require
permission from their rights holders.
