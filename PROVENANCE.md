# FL-BSA Public Artifact Provenance

This repository is a public artifact distribution repository. Its git tags and
commits identify the public release-asset set in this repository, not the source
product commit in the producer repository.

For each release, treat the release asset `manifest.json` as the artifact-level
source of truth. It records the available upstream evidence/product commit
SHAs, workflow runs, publisher run, and available per-asset SHA256 digests.

## v5.0.0-rc9-public-fix-2724455

- Public artifact release:
  <https://github.com/equilens-labs/fl-bsa-pub/releases/tag/v5.0.0-rc9-public-fix-2724455>
- Evidence source commit:
  `272445518e369d99bc350e66d3ab85f4b84121a0`
- Gold / robustness / WP evidence run:
  `27058121862` at that evidence source commit
- Public publisher run:
  `27090038355` from publisher commit
  `63a92f8480873d9052b0aaf6496fc1179532ad57`
- Whitepaper source run:
  `27058588858` at whitepaper commit
  `881e8c99bc75db9c4c82d70b3c22b2dceddfab01`
- Public publisher mode:
  automated release-asset publish; `manifest.json` records the publisher run
  and commit SHA

The public repository tag points to metadata commit
`babde9bb88c75d20f58b4d73ecf5b22f8a69d096`. That SHA identifies this public
distribution repository and is expected to differ from the evidence source and
publisher SHAs above.

Whitepaper asset anchors:

- `whitepaper.pdf`:
  `2cfc8096d73769185bb0724d0c080408d292651a1bcf94d9b3d9d51863c69c20`
- `WhitePaper_Intake_Bundle_v4.zip`:
  `406679efcc66bab25d03f64baec5634e9f147992c5b122c42338566e1ba346f6`

Disposition:

- This is an RC9-era corrected, synthetic/demo, non-commercial technical-proof
  prerelease. It is not customer output, customer evidence, certification,
  general-availability approval, or proof of a public Marketplace listing.
- The publisher copies the selected whitepaper PDF byte-for-byte. It publishes
  the intake ZIP as a sanitized public projection of the cited WP evidence
  artifact, preserving the member set while canonicalizing JSON and scrubbing
  internal paths. The public-output hashes above anchor both assets. The release
  manifest does not list an arXiv source bundle.
- It is not a public publication of exact stable product `v5.0.0`. No
  exact-stable public release is recorded in this repository; that remains a
  separate release-owner, legal/claims, and publication decision.
- The release manifest records `vendor_authorship_claimed=false`; bundled keys
  support bundle-consistency checks and are not a vendor-authorship trust anchor.

Use the release's `manifest.json` and `SHA256SUMS.txt` for the complete asset
inventory, hashes, evidence-disposition fields, and trust-root boundaries.

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
