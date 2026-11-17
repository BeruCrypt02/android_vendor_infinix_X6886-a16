# vendor/x6886

Stock blobs for the X6886 (MT6789), taken from the dump for this phone.

| | |
|---|---|
| Stock | XOS 16, 155SP15 |
| Build ID | BP2A.250605.031.A3 |
| Android | 16 / SDK 36 |
| Branch | `lineage-24.0` |
| Blobs | `vendor`, `odm`, `system`, `system_ext`, `*_dlkm` |

## Layout

```
proprietary/vendor/       stock vendor blobs
proprietary/odm/          stock odm blobs, panel configs included
proprietary/system/       stock system blobs
proprietary/system_ext/   stock system_ext blobs
proprietary/*_dlkm/       kernel modules from the dump
```

## Extraction

Blob list and extractor live in the device tree:

- `device/infinix/x6886/proprietary-files.txt`
- `device/infinix/x6886/extract-files.py`

Run extraction from there; it writes into this tree.

## Contributions

Files in this tree come from the X6886 dump and are listed in
`proprietary-files.txt`. Leave extracted blobs as they are. Blobs from another
device need approval first.
