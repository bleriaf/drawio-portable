# draw.io portable (Windows x64)

Unofficial portable packaging of the draw.io desktop application, built for running from a
single directory on Windows 10/11 x64.

- draw.io desktop **32.6.10** (Electron 32.x)
- locales trimmed to `en-US` / `en-GB`
- packaged as a plain ZIP (no installer, no MSI)

## Download

Grab the archive from **Releases**:

```
draw.io-32.6.10-win-x64-portable.zip
```

Extract it into a folder of your choice and start `draw.io.exe`.

## Checksums

`SHA256SUMS` lists the archive digest. Verify before use:

```powershell
Get-FileHash .\draw.io-32.6.10-win-x64-portable.zip -Algorithm SHA256
```

## Notes

- This is an unofficial repackaging. draw.io itself is © JGraph Ltd and licensed under Apache-2.0.
- The packaging scripts and metadata in this repository are MIT licensed (see `LICENSE`).
- Issues are disabled; this repo only carries build artifacts.
