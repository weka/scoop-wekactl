# scoop-wekactl

[Scoop](https://scoop.sh/) bucket for [`wekactl`](https://github.com/weka/goweka),
the Go-based Weka CLI, on Windows.

> **Generated content — do not edit by hand.**
> `bucket/wekactl.json` is rewritten by the release pipeline in
> `weka/goweka` (`.github/workflows/scoop.yml`) on every release. Manual edits
> will be overwritten on the next release.

## What lives where

- **`bucket/wekactl.json`** is the Scoop manifest for the current release. It
  points at the Windows `.zip` archives published as
  [Releases](../../releases) in this repo — that's the public, unauthenticated
  download surface (`weka/goweka` itself is INTERNAL, so its own release
  assets are not public).
- **[Releases](../../releases)** hold every published version's archives, so
  older versions remain available for manual download.

## Installing

```
scoop bucket add wekactl https://github.com/weka/scoop-wekactl
scoop install wekactl
```

## Source

Packaging and publishing logic lives in
**[weka/goweka](https://github.com/weka/goweka)**. File issues and changes
there, not here.
