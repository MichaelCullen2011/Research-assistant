---
name: verify
description: Audit research outputs before handing them over. Checks that every claim is cited and traceable, quotes are verbatim, figures and dates match their sources, vendor claims are framed as claims, and confidence wording is justified. Use as the final step of every research project.
---

# Verify

Check `outputs/brief.md` (and `outputs/report.md` if it exists) against
`findings.md` and `sources.md`. Fix problems in place, then record the
result.

## Checklist

1. **Coverage**: every factual sentence has a source ID. Anything
   uncited is either cited, moved into an analysis section, or removed.
2. **Traceability**: every cited ID exists in `sources.md`, and the claim
   matches what that source's notes say. Spot-check at least 5 claims (or all
   of them if there are fewer than 10) by re-opening the original source.
3. **Quotes**: every quotation is verbatim and has a locator.
4. **Numbers & dates**: every figure, currency amount and date matches its
   source exactly. Units and currencies are stated.
5. **Tier framing**: T3-only claims are worded as "announced" or "claims".
   No T4 source is cited on its own.
6. **Confidence**: the bottom-line wording and each finding's wording match
   their confidence ratings.
7. **Recency**: sources fall inside the brief's time window, or stale ones
   are flagged.
8. **Analysis labelled**: interpretation is clearly separated from sourced
   fact.
9. **Visuals**: each has a caption and source IDs, and uses no made-up data.
10. **Brief vs report**: they do not contradict each other.
11. **Links**: URLs in the source tables are complete.

## Record the result
Append to the *Verification log* in `findings.md`:

```
### Verification — YYYY-MM-DD
- Claims checked: N (spot-checked against originals: M)
- Issues found / fixed: …
- Remaining caveats: …
- Result: PASS | PASS WITH CAVEATS | FAIL
```

On PASS or PASS WITH CAVEATS, set `status: verified` in `brief.md` and give
the user a 3–5 line summary: what was answered, overall confidence, number of
sources, main open questions, and links to the outputs.
