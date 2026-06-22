# del&bits

del&bits is a Windows cleanup and file organization assistant by **Gaurav Verma**. This repository is used to publish installer builds, keep release notes tidy, and provide checksums for verification.

## Download

The latest installer is published on the Releases page:

- Latest version: `0.4.0`
- Installer: `del-and-bits-0.4.0-setup.exe`
- Platform: Windows
- Package type: setup installer

## Version history

The installers available locally show a short build progression from `0.1.0` to `0.4.0`. No feature-level changelog is embedded in the installer metadata, so this table only records details that can be verified from the files themselves.

| Version | Build date | Installer | Size | Notes |
|---|---|---|---:|---|
| 0.4.0 | 2026-06-21 22:49 | `del-and-bits-0.4.0-setup.exe` | 89.24 MB | Latest published setup build. |
| 0.3.0 | 2026-06-21 22:32 | `del-and-bits-0.3.0-setup.exe` | 89.23 MB | Earlier archived setup build; retained for version traceability. |
| 0.2.0 | 2026-06-21 22:15 | `del-and-bits-0.2.0-setup.exe` | 89.23 MB | Earlier archived setup build; retained for version traceability. |
| 0.1.0 | 2026-06-21 21:48 | `del-and-bits-0.1.0-setup.exe` | 89.23 MB | Earlier archived setup build; retained for version traceability. |

## Verification

SHA-256 hashes are listed in [`CHECKSUMS.md`](CHECKSUMS.md). After downloading an installer, verify it with PowerShell:

```powershell
Get-FileHash .\del-and-bits-0.4.0-setup.exe -Algorithm SHA256
```

Compare the output with the matching value in `CHECKSUMS.md`.

## Installer metadata

The Windows installer metadata identifies the product as `del&bits` and describes it as a privacy-first Windows cleanup and file organization assistant.

## Notes

This repository intentionally keeps the description simple and factual. It only describes what is present in the released installer files.
