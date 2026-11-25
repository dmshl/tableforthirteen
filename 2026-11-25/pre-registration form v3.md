# Pre-registration · v1.0 · Nov 24, 2026 · commit [hash] <TBA>

## Forecasts
Two a month, on the 13th and the 26th. Each one is committed to GitHub before it's published. None are deleted, and annulled forecasts stay in the log. Each quarter covers *at least two domains*, with *at least one* **Hazard** seat and *at least one* **Stressor** seat. 

From Dec 13, every question comes from the indicator bank. Forecasts #1 and #2 come before the bank, and I'm saying so here. I prefer questions that a public source will resolve.

## Resolution
Each forecast resolves on the source and criterion named on its card, read on the resolution date. If the source doesn't publish by the annulment date, the forecast is annulled and stays listed.

## Scoring
[Brier score](https://en.wikipedia.org/wiki/Brier_score), (p − outcome)². 
Numeric questions are scored as yes/no thresholds stated on the card.
I list misses first. A rolling Brier score appears once n ≥ 20; until then, the log says "n = X, too few to judge." 
Where [Metaculus](https://www.metaculus.com/) has a matching question, I report the crowd's Brier score alongside mine.
Annulled forecasts are excluded from Brier scores.

## Relegation
Every Nov 13 from 2027, the 13 seats and the watchlist candidates are scored in the same model run (seed published in the repo). A seat is relegated if its P(bottom 3) ≥ 50%, up to 3 seats. If none qualifies, the seat with the highest P(rank 13) is the candidate for relegation. A relegated seat is replaced only by a candidate with a better median rank. Otherwise it stays, even if that means no change that year.

## Change control
Criteria and formulas change only on Nov 13, with semantic versioning. Scores can move in any quarter, but only with a cited source or a resolved indicator, and always with a changelog line.

## Corrections
Within 72 hours, at the top of the original post: what I said, what's correct, and the effect on scores.

## Bias Statement
I'm Ukrainian and live in the EU, and my gut file was written from a Ukrainian frame. The Russia lens can affect only my personal (P) scores, never the civilizational (C) ones. **Reviewer B** checks this on the Conflict seats before Feb 13, 2027.

## Reader data
[Privacy page link](https://tableforthirteen.substack.com/p/privacy-notice). 
Before analysis I remove test entries, exact duplicates, and bursts (more than 10 identical answers within 10 minutes, reported separately). Individual answers are deleted on Nov 13, 2029.

The form runs on Google Forms under a personal account, which comes with no data processing agreement with Google. I'll review this by Nov 13, 2027.

## Sealed
My stop rules and one business milestone: SHA-256: <TBA>, timestamped Nov 24. To be revealed Nov 13, 2027.