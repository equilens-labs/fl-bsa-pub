# FL-BSA Public Artifact Provenance

This repository is a public artifact distribution repository. Its git tags and
commits identify the public release-asset set in this repository, not the source
product commit in the producer repository.

For each release, treat the release asset `manifest.json` as the artifact-level
source of truth. It records the available upstream evidence/product commit
SHAs, workflow runs, publisher run, and available per-asset SHA256 digests.

## v5.0.8-report-fix-20260929

Public release:

- Release:
  <https://github.com/equilens-labs/fl-bsa-pub/releases/tag/v5.0.8-report-fix-20260929>
- Release ID: `399150186`
- Published: `2026-09-29T12:58:45Z`
- Public repository tag target:
  `2b90d243efdeccb9a7b7cbc596925a18b5262da6`
- GitHub prerelease: `true`
- GitHub latest: `false`
- Immutable release: `true`
- Publication workflow:
  [`36571419803`](https://github.com/equilens-labs/fl-bsa/actions/runs/36571419803),
  attempt `1`
- Publisher App: `equilens-fl-bsa-public-release`

The release owner approved the exact report-only correction in
[`fl-bsa#1807`](https://github.com/equilens-labs/fl-bsa/issues/1807). Dry-run
publisher workflow
[`36569583192`](https://github.com/equilens-labs/fl-bsa/actions/runs/36569583192),
attempt `1`, produced the reviewed source artifact at publisher commit
`16bab857711eadabad3b31f4a026828d9c65cc66`.

Reviewed source artifact:

- Actions artifact name: `public-artifacts-v5.0.8-report-fix-20260929`
- Actions artifact ID: `11033118225`
- Actions artifact size: `190863` bytes
- Actions artifact digest:
  `sha256:b00fef1e2d3576e9a8301978159d2b7558b60e7dc70d9d4e4646138d08d02f45`
- Actions artifact expiry: `2026-10-13T12:43:15Z`
- Scanner rewrites: `0`
- Suppressed OCR warnings: `0`

Source binding:

- Comprehensive workflow:
  [`36563573635`](https://github.com/equilens-labs/fl-bsa/actions/runs/36563573635),
  attempt `1`
- Product/source commit:
  `683507a31a434d89d266316c6e25633de589a22e`
- Source report path:
  `gold/20260929T120145Z/01_balanced/report.pdf`
- Gold artifact: `gold-full-artifacts`
- Gold artifact ID: `11032570851`
- Gold artifact size: `27584329` bytes
- Gold artifact digest:
  `sha256:69d44f601a8f5f79170227487b81c6194a6a9493c96f66ae0bcc501e5db87967`
- Gold artifact expiry: `2026-10-06T12:16:01Z`
- Runtime-profile artifact: `ci-runtime-profile-contract`
- Runtime-profile artifact ID: `11032535950`
- Runtime-profile artifact size: `520` bytes
- Runtime-profile artifact digest:
  `sha256:5c9388d33f3a0d105daa75ee0618082956a5bab454ce8970c44e69180e675a7b`
- Runtime image identity:
  `683507a31a434d89d266316c6e25633de589a22e-commercial_no_datacebo`

The immutable public release contains exactly three assets:

| Asset | Size (bytes) | SHA-256 |
|---|---:|---|
| `customer_report.pdf` | 239223 | `8209216fa746ff8985dd3ad70d46b8bc0eeed7ad39393fffc6dfdefe64d0cf76` |
| `manifest.json` | 4153 | `d9e8ed15b627caedfba5c78ee8e3af45ee15a0afa4a674647f41b474927b5e2e` |
| `SHA256SUMS.txt` | 86 | `e59386801fa5a6ed36ef1ec40f977151ea8d1c6b0d6e795dfb5797d41228ec5d` |

`SHA256SUMS.txt` covers the report payload. The reviewed Actions artifact
digest binds the complete three-file source. Publication workflow run
`36571419803` promoted this exact tuple without rebuilding it, with these
reviewed coordinates:

- Run ID: `36569583192`
- Run attempt: `1`
- Artifact ID: `11033118225`
- Artifact digest:
  `sha256:b00fef1e2d3576e9a8301978159d2b7558b60e7dc70d9d4e4646138d08d02f45`

After publication, the release page and all three unauthenticated exact-tag
asset URLs returned HTTP 200. Fresh downloads matched the table, GitHub's
release-asset digests, and the reviewed dry-run bytes. The temporary Actions
and source artifacts may expire; that expiry does not affect the immutable
public release.

Public disposition:

- Exact public tag `v5.0.8-report-fix-20260929`, GitHub prerelease `true`,
  GitHub latest `false`
- Artifact profile `report_demo_v1`; classification `synthetic_demo_only`
- Customer-evidence posture `characterization_only`; no claim expansion
- Payload limited to `customer_report.pdf`, with manifest and checksum
  sidecars
- Canonical Average Odds Difference is unavailable with reason
  `requires_ground_truth_and_predictions`; no numeric AOD is claimed
- The controlling Race / Asian versus Black / `0.950` / `0.800` / Within
  Threshold comparison is presented together
- `gold_bundle.zip`, `whitepaper.pdf`, `WhitePaper_Intake_Bundle_v4.zip`,
  robustness materials, product artifacts, and every other asset remain held
- No certification or compliance approval, customer or live-data result,
  general-availability or Marketplace claim, production outcome, or regulatory
  or legal determination is authorized by this release

The report carries the `DEMO / EVALUATION ONLY` watermark. The publisher was
disabled again after success, `PUBLIC_ARTIFACTS_ENABLED=false`, and repository
immutable-release creation was turned off. The published release remains
immutable.

## v5.0.8

Public release:

- Release:
  <https://github.com/equilens-labs/fl-bsa-pub/releases/tag/v5.0.8>
- Release ID: `398600408`
- Published: `2026-09-28T20:29:50Z`
- Public repository tag target:
  `9a5518d9b467202d1d8fad56c6f65aa8358046d6`
- GitHub prerelease: `true`
- GitHub latest: `false`
- Immutable release: `true`
- Publication workflow:
  [`36478585711`](https://github.com/equilens-labs/fl-bsa/actions/runs/36478585711),
  attempt `1`
- Publisher App: `equilens-fl-bsa-public-release`

The release owner approved the bounded synthetic/demo release in
[`fl-bsa#1802`](https://github.com/equilens-labs/fl-bsa/issues/1802). The
publisher produced and verified its exact source bytes in dry-run workflow
[`36412393041`](https://github.com/equilens-labs/fl-bsa/actions/runs/36412393041),
attempt `1`.

Source binding:

- Product release tag: `v5.0.8`
- Product commit: `97356e5f65e0032e8363190c47104c96294f8f2a`
- Annotated product tag object:
  `81a60b5df9057f8e3f9d7648f2f8e620510d314f`
- Release Evidence run: `36152873675`, attempt `2`
- Signed inventory artifact ID: `10875824448`
- Signed inventory artifact digest:
  `sha256:3f9ddf080265ab45579d3d124062051c39fe16c6c84070854754bc0eef45041a`
- Signed Gold source: `gold-full-artifacts`, retained from evidence attempt `1`
- Signed Gold artifact ID: `10873153006`
- Signed Gold artifact digest:
  `sha256:18cb11dc190d56441a3e34af8467e8acb1a674400f413def59486bc797d29b85`
- Publisher commit:
  `24894f7eeaf0cfa289881926fc03cc0cf2c1817c`

Reviewed source artifact:

- Actions artifact name: `public-artifacts-v5.0.8`
- Actions artifact ID: `10965600831`
- Actions artifact digest:
  `sha256:8128d6920946cde8a09fcec4ea7f2fd15d4499dc3bf6450bae2b463fd621da63`
- Actions artifact expiry: `2026-10-12T11:01:02Z`
- Scanner inventory SHA-256:
  `4f687a0205cbb9a83cfd3f3c7d707b9f03f6b9d537a088fb770190cd1c26fb8a`
- Scanner rewrites: `0`
- Suppressed OCR warnings: `0`

The immutable public release contains exactly four assets:

| Asset | Size (bytes) | SHA-256 |
|---|---:|---|
| `customer_report.pdf` | 237593 | `2b2c39fc846097d6935b39f547eb80d0b022e32f23a52a3e129b8f6c27fcadf3` |
| `gold_bundle.zip` | 2931913 | `4ae706e1e4e16c9547dd0ee5cee8022383d1db861e7715ac4878515643a443c4` |
| `manifest.json` | 5767 | `b70da322ec022ecc998b3df5112ca3433468fa26863510cc01f3f79b2142ca81` |
| `SHA256SUMS.txt` | 168 | `dc1593e9cfdffe46889c2a6c2d35831d01021dcf78f15b8204311551bd14f57b` |

The `SHA256SUMS.txt` file covers the two payloads. The Actions artifact digest
binds the complete four-file source. Publication workflow run `36478585711`
promoted this exact tuple without rebuilding it:

- Run ID: `36412393041`
- Run attempt: `1`
- Artifact ID: `10965600831`
- Artifact digest:
  `sha256:8128d6920946cde8a09fcec4ea7f2fd15d4499dc3bf6450bae2b463fd621da63`

After publication, all four unauthenticated exact-tag URLs returned HTTP 200.
Fresh downloads matched this table, the GitHub release-asset digests, and the
reviewed source artifact byte-for-byte. The temporary Actions source expires at
`2026-10-12T11:01:02Z`; that expiry does not affect the immutable public
release.

Public disposition:

- Exact public tag `v5.0.8`, GitHub prerelease `true`, GitHub latest `false`
- Artifact profile `report_gold_demo_v1`; classification `synthetic_demo_only`
- Customer evidence posture `characterization_only`; no claim expansion
- Payloads limited to `customer_report.pdf` and `gold_bundle.zip`, with the
  manifest and checksum sidecars
- `whitepaper.pdf`, `WhitePaper_Intake_Bundle_v4.zip`, robustness materials,
  and every other asset remain held
- No certification or compliance approval, customer or live-data result,
  general-availability or Marketplace claim, production outcome, or regulatory
  or legal determination is authorized by this release

The report carries the `DEMO / EVALUATION ONLY` watermark. The release
manifest records `vendor_authorship_claimed=false`; the Gold bundle's keys
support bundle-consistency checks and are not a vendor-authorship trust anchor.
Publication does not change the website automatically. Under the recorded
decision, the website owner may retarget only direct `customer_report.pdf` and
`gold_bundle.zip` links; the current RC9 whitepaper, intake, integrity, and
release-page links remain unchanged.

### 2026-09-29 active-promotion correction

The immutable release and the hashes above remain the historical record. On
2026-09-29, `gold_bundle.zip` was withdrawn from active promotion and
technical-evaluation use because its regenerated `gold/summary.json` labels an
absolute selection-rate gap of `0.0049` as Average Odds Difference in the
`01_balanced` row while the canonical
scenario metrics and report record AOD as unavailable. The summary also omits
controlling warning comparisons, including `04_security` (`0.8941`) and
`06_xlsx_parity` (`0.8762`). This correction supersedes the preceding permission
to retarget a `gold_bundle.zip` website link; only the `customer_report.pdf`
permission remains. Website PR `equilens-labs/website#94` removed the Gold
link, and this repository's README no longer promotes the bundle.
The exact-tag Gold asset remains publicly downloadable for audit history and
must not be used as a current technical-evaluation artifact.
The older `customer_report.pdf` remains part of the immutable historical
release, but active report promotion is superseded by the report-only
`v5.0.8-report-fix-20260929` release above. No corrected Gold bundle was
published. The v5.0.8 release asset bytes, manifest, and recorded hashes must
not be replaced or edited.

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
