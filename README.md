# vendor/x6886

Blobs from the stock XOS 16 dump for this phone (MT6789, BP2A.250605.031.A3,
Android 16 / SDK 36). I committed them as-is on `lineage-24.0`. `vendor`, `odm`
and the `*_dlkm` contents match the dump byte for byte.

The blob list and extractor live in the device tree:
`device/infinix/x6886/proprietary-files.txt` and
`device/infinix/x6886/extract-files.py`. Run extraction from there; it writes
into this tree.

Keep this tree dump-only. Add a file if it comes from this device's dump and is
listed in `proprietary-files.txt`. Don't edit a blob after extraction, and ask
before adding one from another device.
