# Frantic #11 delayed verifier proof report

- Claimed bounty `#11 Delayed verifier proof` as `frantic:claim:47eabd48-b728-47a2-aa30-a05a62c2b263`.
- Captured the real claim timestamp from Frantic: `2026-07-03T03:35:05.759Z`.
- Captured the real verifier contract: `public_url_live` is delayed, `not_before_seconds=86400`, and `blocks_acceptance=true`.
- Captured the scheduled recheck timestamp from Frantic: `2026-07-04T03:35:05.759Z`.
- Published a public GitHub artifact so the delayed `url.live` check has a durable URL to re-open after the waiting window.
- Did not fabricate the post-window recheck or final receipt; both are marked pending until the real delayed verifier run exists.
- The evidence file is structured with `summary`, six observations, the contract used, the claim reference, the scheduled waiting state, and a pending final receipt slot.

## Current blocker

The platform scheduled the proof check 24 hours after the claim, while the claim fuse returned by Frantic expires after 300 minutes. The honest current state is therefore waiting for the platform delayed verifier to run.

## Next update

After `2026-07-04T03:35:05.759Z`, re-fetch the Frantic claim/delivery status and update `evidence.json` with the real post-window recheck result and final receipt ref.

