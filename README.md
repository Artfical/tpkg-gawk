# gawk

GNU awk 5.3.1

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install gawk
```

| | |
|---|---|
| Version | 5.3.1 |
| Licence | GPL-3.0-or-later |
| Upstream | - |
| Needs | none |
| Needs tOS build | 619 or newer |
| Size | 1026782 bytes (2076843 unpacked) |
| SHA-256 of the `.tpkg` | `647a1b9bb55dd13c4a8bf27c4022289fa3350831b07359243eccd86c16b38e35` |

## Commands it adds

| Command | Runs |
|---|---|
| `awk` | `bin/awk` |
| `gawk` | `bin/gawk` |
| `gawk-5.3.1` | `bin/gawk-5.3.1` |
| `gawkbug` | `bin/gawkbug` |

## Download

The package file (`gawk-5.3.1.tpkg`) and the sources it was built from are the assets of the
[v5.3.1 release](https://github.com/Artfical/tpkg-gawk/releases/tag/v5.3.1).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `gawk-5.3.1.tar.xz`

Check a download: `sha256sum gawk-5.3.1.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: GPL-3.0-or-later. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
