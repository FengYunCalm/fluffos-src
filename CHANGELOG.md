# Changelog

## Unreleased (Fork)

- Windows: use `bash cp -f` for `cmake --install` to avoid “Permission denied” when replacing binaries.
- Warning cleanup: targeted fixes in scratchpad, preprocessor, ed, telnet_ext, external, and socket_efuns.
- Third‑party warnings: suppress warnings and disable IPO where needed in libevent/crypt/libwebsockets; align filesystem CMake minimum version.
- Documentation: rewrite README/README_CN for fork scope, add CONTRIBUTING/SECURITY/CODE_OF_CONDUCT, and align LICENSE/NOTICE references.
- Repository hygiene: remove internal AI guidance and private TODOs from the public tree.

## Upstream history

See the upstream `ChangeLog` file and release notes: https://github.com/fluffos/fluffos
