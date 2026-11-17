# Infinix X6886 proprietary vendor tree

Prebuilt vendor tree for the Infinix X6886 (HOT 60 Pro+), taken from the stock
XOS 16 dump for this device. Blobs are copied as-is and are never modified.

| Item | Value |
| --- | --- |
| Device | Infinix X6886 (HOT 60 Pro+) |
| Platform | MediaTek MT6789 |
| Stock build | XOS 16 / 155SP15, BP2A.250605.031.A3 |
| Stock Android | 16 (SDK 36) |
| Build branch | lineage-24.0 |

## Layout

`proprietary-files.txt` is the list of blobs. `extract-files.py` copies them
from the stock dump into `vendor/infinix/x6886` and `odm/`. The `vendor`, `odm`
and `*_dlkm` contents stay exactly as they are in the dump.

## Rules

- Blobs are copied from the stock dump, never modified.
- Every blob is listed in `proprietary-files.txt`.
- No blob from another device is added without explicit approval.
