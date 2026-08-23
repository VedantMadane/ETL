# Installed ETLStd consumer smoke tests

These checks validate an *installed* tree (not the in-repo build tree).

## Checklist

- [ ] Configure a tiny external CMake project that calls `find_package(ETLStd ...)`.
- [ ] Build and run a program that exercises one public API header.
- [ ] Confirm the test fails clearly if the install prefix is wrong.

Automate these steps in CI when an install artifact is produced.
