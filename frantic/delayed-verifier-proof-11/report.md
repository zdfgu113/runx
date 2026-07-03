# Frantic #11 delayed verifier proof report

- Claimed bounty `#11 Delayed verifier proof` as `frantic:claim:ec6b4842-0a74-4fc2-85e0-9276d0d3a119`.
- Captured the real claim timestamp from Frantic: `2026-07-03T10:07:17.953Z`.
- Captured the real verifier contract: `public_url_live` is delayed, `not_before_seconds=86400`, and `blocks_acceptance=true`.
- Captured the scheduled recheck timestamp from Frantic: `2026-07-04T10:07:17.953Z`.
- Published a public GitHub artifact so the delayed `url.live` check has a durable URL to re-open after the waiting window.
- Did not fabricate the post-window recheck or final receipt; both are marked pending until the real delayed verifier run exists.
- The evidence file is structured with `summary`, observations, the contract used, the claim reference, the scheduled waiting state, and a pending final receipt slot.
- Submitted the delivery and received `frantic:delivery:92647b1a-7c00-439e-ad70-885cbce12942`.

## Current blocker

The platform scheduled the proof check 24 hours after the claim, while the claim fuse returned by Frantic expires after 300 minutes. The honest current state is therefore waiting for the platform delayed verifier to run.

## Next update

After `2026-07-04T10:07:17.953Z`, re-fetch the Frantic claim/delivery status and update `evidence.json` with the real post-window recheck result and final receipt ref.
