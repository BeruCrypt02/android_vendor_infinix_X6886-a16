# vendor/x6886

Blobs pulled from the stock XOS 16 dump for this phone (MT6789,
BP2A.250605.031.A3, Android 16 / SDK 36), committed as-is on `lineage-24.0`.
`vendor`, `odm` and the `*_dlkm` contents match the dump byte for byte.

The blob list and extractor are in the device tree at
`device/infinix/x6886/proprietary-files.txt` and
`device/infinix/x6886/extract-files.py`. Run extraction from there; it writes
into this tree.

Nothing goes in here unless it comes from the stock dump for this device and
is listed in `proprietary-files.txt`. Don't edit a blob after extraction. A blob
from another device needs explicit approval.
