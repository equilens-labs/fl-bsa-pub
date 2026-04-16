# FL-BSA Public Artifact Provenance

This repository is a public artifact distribution repository. Its git tags and
commits identify the public release-asset set in this repository, not the source
product commit in `equilens-labs/fl-bsa`.

For each release, treat the release asset `manifest.json` as the artifact-level
source of truth. It records the upstream product tag, product commit SHA,
evidence workflow run, publisher run, and per-asset SHA256 digests.

## v5.0.0-rc4

- Public artifact release:
  <https://github.com/equilens-labs/fl-bsa-pub/releases/tag/v5.0.0-rc4>
- Product release:
  <https://github.com/equilens-labs/fl-bsa/releases/tag/v5.0.0-rc4>
- Product tag commit:
  `34dbf3f923435ab23693ca45cb312703085d4030`
- Release evidence run:
  <https://github.com/equilens-labs/fl-bsa/actions/runs/24472375841>
- Public publisher mode:
  local manual backfill, disclosed in `manifest.json`

The `fl-bsa-pub` git tag `v5.0.0-rc4` points to this repository's public
metadata commit. That SHA is expected to differ from the product repository tag
SHA above.
