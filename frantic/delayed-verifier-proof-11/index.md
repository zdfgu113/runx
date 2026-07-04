# Delayed verifier proof for Frantic #11

This artifact records the current real verifier state for Frantic bounty #11, including the completed post-window recheck.

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
- Five checks were immediate artifact checks.
- The `public_url_live` check is an async delayed check scheduled for `2026-07-04T16:28:52.837Z`.
- The post-window `public_url_live` recheck ran at `2026-07-04T16:29:26.652Z`.
- The delayed checker returned `HTTP 200` and marked `public_url_live` as `passed`.
- The recorded verifier run reference is `verifier-run:5e80d5b0-6a08-4900-987f-f8577fdacf78:3181`.
- `evidence.json` contains the immediate-pass record, scheduled waiting state, post-window recheck result, and final receipt ref.

## Evidence

- Evidence JSON: `evidence.json`
- Report: `report.md`
