# FL-BSA Public Artifact Provenance

This repository is a public artifact distribution repository. Its git tags and
commits identify the public release-asset set in this repository, not the source
product commit in `equilens-labs/fl-bsa`.

For each release, treat the release asset `manifest.json` as the artifact-level
source of truth. It records the upstream product tag, product commit SHA,
evidence workflow run, publisher run, and per-asset SHA256 digests.

## v5.0.0-rc8

- Public artifact release:
  <https://github.com/equilens-labs/fl-bsa-pub/releases/tag/v5.0.0-rc8>
- Product release:
  <https://github.com/equilens-labs/fl-bsa/releases/tag/v5.0.0-rc8>
- Product tag commit:
  `4cd570523bc2d26f35201c22e911ab21c3bfcd16`
- Gold / robustness / WP evidence run:
  <https://github.com/equilens-labs/fl-bsa/actions/runs/25589285290>
- Public publisher run:
  `25633139594` from
  `44ddb71ee01a8d2c992023bc9979cf450d0ed05f`
- Whitepaper source run:
  <https://github.com/equilens-labs/fl-bsa-whitepaper/actions/runs/25625146311>
- Public publisher mode:
  automated release asset publish, disclosed in `manifest.json`

The `fl-bsa-pub` git tag `v5.0.0-rc8` points to this repository's public
metadata commit. That SHA is expected to differ from the product repository tag
SHA above.

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
