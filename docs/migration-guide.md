# ETLStd migration guide

## Installing ETLStd

Prefer the package manager / CMake package config exported by this project.

## Consumer smoke test

After installing headers/libs, a minimal consumer should:

1. Find the package (`find_package` / pkg-config as documented).
2. Link the ETLStd target.
3. Compile a one-translation-unit program that includes the public headers and returns 0.

## Compatibility notes

Record breaking changes here as they land. Until then, treat the latest mainline install tree as the source of truth.
