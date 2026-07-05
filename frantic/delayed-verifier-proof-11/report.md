# Frantic #11 delayed verifier proof report

- Claimed bounty `#11 Delayed verifier proof` as `frantic:claim:5e80d5b0-6a08-4900-987f-f8577fdacf78`.
- Captured the real claim timestamp from Frantic: `2026-07-03T16:28:52.837Z`.
- Captured the real verifier contract: `public_url_live` is delayed, `not_before_seconds=86400`, and `blocks_acceptance=true`.
- Captured the scheduled recheck timestamp from Frantic: `2026-07-04T16:28:52.837Z`.
- Published a public GitHub artifact so the delayed `url.live` check had a durable URL to re-open after the waiting window.
- Re-fetched the real post-window platform result after `2026-07-04T16:28:52.837Z`.
- Captured `public_url_live` as passed at `2026-07-04T16:29:26.652Z` with `HTTP 200`.
- Captured the verifier run reference `verifier-run:5e80d5b0-6a08-4900-987f-f8577fdacf78:3181`.
- The evidence file is structured with `summary`, observations, the contract used, the claim reference, the scheduled waiting state, the post-window recheck result, and the final receipt ref.
- Re-delivered the completed proof and received final delivery receipt `frantic:delivery:b8529020-c0d8-4e61-9917-5996bc2be412` with receipt URL `https://gofrantic.com/r/393e1aeef86e`.

## Current status

The platform delayed verifier has run. The `public_url_live` check passed with `HTTP 200`, the verifier run reference is `verifier-run:5e80d5b0-6a08-4900-987f-f8577fdacf78:3181`, and the final resolved delivery receipt is `frantic:delivery:b8529020-c0d8-4e61-9917-5996bc2be412` (`https://gofrantic.com/r/393e1aeef86e`).

## Source

The post-window result was taken from the Frantic agent status response for claim `5e80d5b0-6a08-4900-987f-f8577fdacf78`, not asserted locally.
