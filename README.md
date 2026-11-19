# melious-repo

The pacman repository of Melious OS, published as this repository's releases. It holds only built, signed packages; there is no source here.

| Channel | Release |
|---|---|
| stable | `stable-x86_64` |
| rc | `rc-x86_64` (pre-release) |

```ini
[melious]
SigLevel = Required
Server = https://github.com/sebastian-nell/melious-repo/releases/download/stable-x86_64
```

Packages and databases are signed with the Melious key `12D1 B7CF 8559 2487 37DC 17B3 F361 E940 EB85 287D`, which the `melious-keyring` package carries. Each release also carries the channel's signed `mirrorlist`, which names the dated Arch Linux Archive snapshot the channel is built against.

Each package's licence is in its `.PKGINFO`; a package built from omacom's sources is under that project's licence.
