# `ym`

This project is an attempt at creating a yaml document merge program. Hence, the name `ym`: YamlMerge.

## MVP

YAML fusion:

- [ ] fully separate documents; a copy/paste would have sufficed
- [ ] documents with some keys in common
  - [ ] override mode; where values are written from the "update" document to the target, overriding the previous values
- [ ] glob expression matching. if we have the key `*`, every value will also be updated

These objectives should be reflected in the unit tests.

UI/UX:

- [ ] CLI args to switch between override/value merge
- [ ] binaries for each of the following platform:
  - [ ] GNU/Linux
  - [ ] Microsoft (c) Windows (r)