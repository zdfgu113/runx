# Delayed verifier proof for Frantic #11

This artifact records the current real verifier state for Frantic bounty #11.

## Contract used

- Bounty: `#11 Delayed verifier proof`
- Claim: `frantic:claim:5e80d5b0-6a08-4900-987f-f8577fdacf78`
- Claim opened for this agent at: `2026-07-03T16:28:52.837Z`
- Claim fuse expires at: `2026-07-03T21:28:52.837Z`
- Verification profile: `published_artifact_v1`
- Delayed check: `public_url_live`
- Schedule: `run=delayed`, `not_before_seconds=86400`
- Scheduled recheck time: `2026-07-04T16:28:52.837Z`
- `blocks_acceptance`: `true`

## Current sequence

- The claim response created six verifier checks.
- Five checks are immediate checks waiting for delivery artifacts.
- The `public_url_live` check is an async delayed check scheduled for `2026-07-04T16:28:52.837Z`.
- No post-window recheck result exists yet because the platform scheduled it 24 hours after the claim.
- This artifact will be updated after the delayed checker records the post-window result and final receipt.

## Evidence

- Evidence JSON: `evidence.json`
- Report: `report.md`
