# scoop-wekactl

[Scoop](https://scoop.sh/) bucket for [`wekactl`](https://github.com/weka/goweka),
the Go-based Weka CLI, on Windows.

> **Generated content — do not edit by hand.**
> `bucket/wekactl.json` is rewritten by the release pipeline in
> `weka/goweka` (`.github/workflows/scoop.yml`) on every release. Manual edits
> will be overwritten on the next release.

## Installing

1. **Add the bucket**

   ```powershell
   scoop bucket add wekactl https://github.com/weka/scoop-wekactl
   ```

2. **Install `wekactl`**

   ```powershell
   scoop install wekactl
   ```

Scoop picks the right build for your architecture (x64 or Arm64) automatically.
Upgrade to the latest release with:

```powershell
scoop update wekactl
```

To uninstall:

```powershell
scoop uninstall wekactl
scoop bucket rm wekactl
```

> **First-run warning:** the Windows binaries are not yet code-signed, so on
> first run Windows SmartScreen may show a warning. Choose **More info**, then
> **Run anyway** to proceed. Code signing is planned for a future release.

## Command completion

To enable tab-completion in PowerShell, add this line to your profile (the file
named by `$PROFILE`):

```powershell
wekactl completion powershell | Out-String | Invoke-Expression
```

## What lives where

- **`bucket/wekactl.json`** is the Scoop manifest for the current release. It
  describes a single version with one entry per CPU architecture (x64 and
  Arm64), and points at the Windows `.zip` archives published as
  [Releases](../../releases) in this repo — that's the public, unauthenticated
  download surface (`weka/goweka` itself is INTERNAL, so its own release
  assets are not public).
- **[Releases](../../releases)** hold every published version's archives, so
  older versions remain available for manual download.

## Source

Packaging and publishing logic lives in
**[weka/goweka](https://github.com/weka/goweka)**. File issues and changes
there, not here.
