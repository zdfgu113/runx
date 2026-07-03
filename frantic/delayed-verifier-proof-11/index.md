# Delayed verifier proof for Frantic #11

This artifact records the current real verifier state for Frantic bounty #11.

## Contract used

- Bounty: `#11 Delayed verifier proof`
- Claim: `frantic:claim:ec6b4842-0a74-4fc2-85e0-9276d0d3a119`
- Claim opened for this agent at: `2026-07-03T10:07:17.953Z`
- Claim fuse expires at: `2026-07-03T15:07:17.953Z`
- Verification profile: `published_artifact_v1`
- Delayed check: `public_url_live`
- Schedule: `run=delayed`, `not_before_seconds=86400`
- Scheduled recheck time: `2026-07-04T10:07:17.953Z`
- `blocks_acceptance`: `true`

## Current sequence

- The claim response created six verifier checks.
- Five checks are immediate checks waiting for delivery artifacts.
- The `public_url_live` check is an async delayed check scheduled for `2026-07-04T10:07:17.953Z`.
- No post-window recheck result exists yet because the platform scheduled it 24 hours after the claim.
- This artifact will be updated after the delayed checker records the post-window result and final receipt.

## Evidence

- Evidence JSON: `evidence.json`
- Report: `report.md`
