# Source Policy and Provenance

## Non-negotiable rules

1. Never fabricate sources, URLs, dates, quotes, or publication names.
2. If web/source access is unavailable, do not fake evidence. Explicitly output `EVIDENCE_ACCESS_LIMITED`.
3. Mark each key claim as one of:
   - `verified` (source checked)
   - `inferred` (reasoned, not source-verified)
   - `unknown` (insufficient data)
4. Distinguish factual statement from analytical inference.
5. Prefer primary sources; otherwise use high-quality secondary sources and label them.

## Access modes

- **Mode A: No external access**
  - Produce analysis with explicit uncertainty.
  - Include a "Data gaps" block and verification plan.

- **Mode B: External access allowed**
  - Use only approved/public sources.
  - For each source include URL + date + outlet/type + reliability score.

## Minimum provenance block

For each key claim include:
- claim_id
- status (verified/inferred/unknown)
- source_url (if verified)
- source_date (if verified)
- reliability_score (1-5)

## Fail-closed behavior

If a required source cannot be verified, downgrade confidence and keep claim as inferred/unknown.
Never upgrade confidence based on unverified evidence.
