# libgcrypt

xlings payload repacked from upstream binaries (conda-forge / Debian) by
[`.agents/tools/repack/repack.py`](https://github.com/openxlings/xim-pkgindex/tree/main/.agents/tools/repack).
Recipe: [`xim-pkgindex`](https://github.com/openxlings/xim-pkgindex) `pkgs/l/libgcrypt.lua`.

Every release asset carries `PROVENANCE.md` (upstream artefacts, sha256, the exact command) and a `.sha256` sidecar.

## Sources

| artefact | sha256 | origin |
|---|---|---|
| https://conda.anaconda.org/conda-forge/linux-64/libgcrypt-lib-1.12.2-h7cc23a3_2.conda | `a67e7b569f08459fbd62619cbbc14a0e2da9d9e519feb11ee035bb31c653d1a9` | conda-forge libgcrypt-lib 1.12.2 h7cc23a3_2 (LGPL-2.1-or-later) |

## Command

```
.agents/tools/repack/repack.py \
    --name libgcrypt \
    --version 1.12.2 \
    --arch x86_64 \
    --src https://conda.anaconda.org/conda-forge/linux-64/libgcrypt-lib-1.12.2-h7cc23a3_2.conda#a67e7b569f08459fbd62619cbbc14a0e2da9d9e519feb11ee035bb31c653d1a9 \
    --require lib/libgcrypt.so.20
```

