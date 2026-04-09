# TelemetryDeck Copy Alignment

## Goal
Update website and privacy copy so it no longer claims "no tracking" while clearly stating that analytics are privacy-focused and do not include personally identifiable information.

## Approach
Revise only public-facing text in existing Astro pages and constants that currently claim no tracking, while preserving the site’s voice and minimal style. Keep claims precise and legally safer by avoiding absolute language where not verifiable.

Files to update:
- `src/pages/privacy-policy.astro`
- `src/pages/index.astro`
- `src/pages/about.astro`
- `src/consts.ts`

## Steps
1. Replace contradictory claims in privacy policy (no analytics/no tracking) with TelemetryDeck disclosure and explicit "no personally identifiable information" language.
2. Update homepage hero/trust copy to remove "no tracking" and replace with privacy-respecting analytics wording.
3. Update about page privacy principle text to align with TelemetryDeck usage.
4. Update global site description in constants to avoid stale "no tracking" claim.
5. Run a workspace text search for "no tracking"/"don't track" and resolve any remaining conflicts.

## Risks or open questions
- "Personally identifiable information" language should be accurate for your exact app instrumentation; if custom parameters include user content, this wording would need adjustment.
- Marketing phrasing can still imply broad promises; wording should remain specific and not over-claim.
