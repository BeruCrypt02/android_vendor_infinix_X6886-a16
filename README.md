# Infinix X6886 vendor tree

Prebuilt vendor blobs for the Infinix X6886 (HOT 60 Pro+). They were extracted
from the stock XOS 16 dump for this phone and are committed as-is.

- Device: Infinix X6886 (HOT 60 Pro+)
- Platform: MediaTek MT6789
- Stock build: XOS 16 / 155SP15, BP2A.250605.031.A3
- Stock Android: 16 (SDK 36)
- Branch: lineage-24.0

## Layout

The `vendor`, `odm` and `*_dlkm` contents match the dump byte for byte. The
blob list and extraction script live in the device tree at
`device/infinix/x6886/proprietary-files.txt` and
`device/infinix/x6886/extract-files.py`. Run extraction from there; it writes
the blobs into this tree.

## Rules

- Only blobs from the stock dump for this device go here, listed in
  `device/infinix/x6886/proprietary-files.txt`.
- Do not modify a blob after extraction.
- Adding a blob from another device needs explicit approval.
