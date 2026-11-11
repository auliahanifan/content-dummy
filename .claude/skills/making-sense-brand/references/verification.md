# Verifying AI News — Making Sense

Rule zero: a joke is only as good as the fact under it. Verify first, be funny second.

## Source hierarchy

| Tier | Examples | Role |
|---|---|---|
| **1 — Primary** | Official company blog/release, docs and changelogs, papers (arXiv/journals), model cards, filings and regulator releases, official repos, official event transcripts | Basis of the claim |
| **2 — Credible media** | Major tech/business outlets with named reporters and a corrections record | Confirmation, context |
| **3 — Secondary** | Newsletters, analysts, independent experts | Analysis and opinion, not core facts |
| **4 — Not enough** | Anonymous accounts, source-less screenshots, "they say", aggregators, AI-generated content, viral threads with no links | A lead to investigate, never a basis |

## Verification flow

1. **Pin down the claim**: who did what, when, and which numbers.
2. **Trace to the primary source.** If an article cites another article, follow the chain to the end.
3. **Check the timeline.** Is this the original publish date, or an old story making a comeback?
4. **Check the numbers.** Benchmarks: who measured, how, versus what baseline? "X% better" needs a baseline.
5. **Check quotes.** Exists in the original, full context intact, translation doesn't change meaning.
6. **Look for denials.** Has the company or party responded or corrected?
7. **Assign a label** (Confirmed / Reported / Rumor) and write down what is **still unknown**.
8. **Log sources** (title, publisher, URL, publish date, access date).

## AI hoax red flags

- No link to a primary source, only a screenshot.
- Dramatic claims: "AI became self-aware", "AI refused to be shut down", "AI invented its own language", "AGI achieved" without a paper or official statement.
- Executive or researcher quotes that can't be found in an interview or official account.
- Suspiciously round or too-good numbers with no methodology.
- Lookalike domains, or text that reads auto-generated.
- Images, video, or audio that could be a deepfake or generated.
- Emotional urgency: "SHARE BEFORE THEY DELETE THIS".
- A "leak" reported by exactly one account.

## Special cases

- **Product/model launches**: primary source suffices, but performance numbers are labeled "company claims" until independently evaluated.
- **Benchmarks**: name who ran it, plus version and date.
- **Regulation/legal**: cite the regulation text or official release, not just media summaries.
- **Funding/valuation/acquisitions**: without official confirmation or 2+ credible outlets, label "Reported".
- **AI safety/risk**: separate research findings, opinions, and hypothetical scenarios.
- **Predictions**: always labeled as predictions, with the predictor named.

## Source log format (for captions/descriptions)

```
Sources:
1. [Publisher] — "[Title]" (published DD MMM YYYY) — URL
2. ...
Status: ✅ Confirmed | 🟡 Reported
Last checked: DD MMM YYYY
```

## Corrections

If an error is found after publishing: (1) fix the content, (2) add a dated "Correction: ..." note, (3) don't erase the trail, (4) state what changed, briefly and clearly. A correction with good humor is fine ("We got a number wrong. Fixed. Our calculator has been spoken to."). A correction that dodges the error is not.
