# FL-BSA Public Artifact Provenance

This repository is a public artifact distribution repository. Its git tags and
commits identify the public release-asset set in this repository, not the source
product commit in the producer repository.

For each release, treat the release asset `manifest.json` as the artifact-level
source of truth. It records the upstream product tag, product commit SHA,
evidence workflow run, publisher run, and per-asset SHA256 digests.

## v5.0.0-rc8.4

- Public artifact release:
  <https://github.com/equilens-labs/fl-bsa-pub/releases/tag/v5.0.0-rc8.4>
- Product release tag: `v5.0.0-rc8.4`
- Product tag commit:
  `8eaa4df2a929608e82756009cd67b5c6ade1c55d`
- Gold / robustness / WP evidence run:
  `26010961195` at product commit
  `8eaa4df2a929608e82756009cd67b5c6ade1c55d`
- Public publisher run:
  `26119192510` from publisher commit
  `b733840b35948aaeb65398cde561e028c4801cfc`
- Whitepaper source run:
  <https://github.com/equilens-labs/fl-bsa-whitepaper/actions/runs/26018062286>
- Public publisher mode:
  automated release asset publish, disclosed in `manifest.json`

The `fl-bsa-pub` git tag `v5.0.0-rc8.4` points to this repository's public
metadata commit. That SHA is expected to differ from the product repository tag
SHA above.

Disposition:

- Public artifacts are prerelease, synthetic/demo-only artifacts for the
  controlled RC8.4 pilot/review path.
- This release is not stable/general-production sign-off.
- Product repository release and evidence workflow links are operator-only
  provenance references; unauthenticated public readers should use this public
  repository's release assets plus `manifest.json` and `SHA256SUMS.txt`.
- `gold_bundle.zip` intentionally includes row-level synthetic/demo datasets and
  validation/evidence scaffolding for public review. These are not customer data
  or customer evidence bundles.

Disclosure note:

`customer_report.pdf` and `gender_bias_report.pdf` carry the
"DEMO / EVALUATION ONLY" watermark. `whitepaper.pdf` and
`robustness_report.pdf` use synthetic/demo framing but do not carry the same
repeating report watermark. Treat every asset in this release as prerelease
synthetic/demo material.

## v5.0.0-rc8

- Public artifact release:
  <https://github.com/equilens-labs/fl-bsa-pub/releases/tag/v5.0.0-rc8>
- Product release tag: `v5.0.0-rc8`
- Product tag commit:
  `4cd570523bc2d26f35201c22e911ab21c3bfcd16`
- Gold / robustness / WP evidence run:
  `25589285290`
- Public publisher run in the producer repository:
  `25633139594` from
  `44ddb71ee01a8d2c992023bc9979cf450d0ed05f`
- Whitepaper source run:
  <https://github.com/equilens-labs/fl-bsa-whitepaper/actions/runs/25625146311>
- Public publisher mode:
  automated release asset publish, disclosed in `manifest.json`

The `fl-bsa-pub` git tag `v5.0.0-rc8` points to this repository's public
metadata commit. That SHA is expected to differ from the product repository tag
SHA above.

Tag map:

- `v5.0.0-rc8` points to `4cd570523bc2d26f35201c22e911ab21c3bfcd16`.
- `v5.0.0-rc8-preflight-20260508` also points to
  `4cd570523bc2d26f35201c22e911ab21c3bfcd16`.
- The preflight tag is where the strict-disposition JSON was produced.

Input-mirror note:

The `robustness_summary_merged.public.json` strict-pass fields mirror the
release-evidence workflow's required-mode input. They are claim-shaped, not
outcome-verified. RC8 release posture was advisory-robustness in the private
release-tracking notes.

AIR cross-reference:

| AIR | Asset | Scenario | Disposition |
|---:|---|---|---|
| 0.991 | `customer_report.pdf` | general | WITHIN |
| 0.758 | `whitepaper.pdf` section 1.3 | gender on amplification slice | flagged |
| 0.650 | `gender_bias_report.pdf` | `02_gender_bias` adversarial probe | by-design OUTSIDE |

Probe context:

`gender_bias_report.pdf` reflects the `02_gender_bias` adversarial-probe
scenario, designed to surface intersectional bias. The outcome is by-design,
not a model defect. LC11 v5.0 excludes intersectional claims.

Watermark gap acknowledgment:

`whitepaper.pdf` and `robustness_report.pdf` lack the "DEMO / EVALUATION ONLY"
watermark that `customer_report.pdf` and `gender_bias_report.pdf` carry. This is
tracked upstream for re-render and is not resolved by this provenance update.

## v5.0.0-rc4

- Public artifact release:
  <https://github.com/equilens-labs/fl-bsa-pub/releases/tag/v5.0.0-rc4>
- Product release tag: `v5.0.0-rc4`
- Product tag commit:
  `34dbf3f923435ab23693ca45cb312703085d4030`
- Release evidence run:
  `24472375841`
- Public publisher mode:
  local manual backfill, disclosed in `manifest.json`

The `fl-bsa-pub` git tag `v5.0.0-rc4` points to this repository's public
metadata commit. That SHA is expected to differ from the product repository tag
SHA above.
