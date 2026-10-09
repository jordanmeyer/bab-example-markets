# Predict, change, reconcile

These are bounded classroom tasks using invented commercial inputs. Record a prediction before editing, then compare it with the answer. This is a developer-authored exercise, not evidence that a novice has completed it.

## 1. A close ranking and an abrupt gate

Starting screen: Georgia 67.50, Tennessee 67.00, North Carolina 61.75. Predict whether raising growth weight from 25 to 70 changes first place. Change it, then explain the contribution difference rather than treating the score as a forecast.

Answer: Tennessee 74.14 leads Georgia 68.28 and North Carolina 65.86. Tennessee's 10.8% growth versus Georgia's 8.4% increases its relative growth contribution from 5.00 to 9.66 points. The exact growth-weight crossover is 27.5; the integer sweep reports Georgia at 0–27 and Tennessee at 28–100. The initial half-point lead is close under these assumed weights, not a statistical confidence level. Ranking uses unrounded arithmetic.

Reset. Open Eligibility ceilings. Predict Florida's result at a setup ceiling of $299,999.99 and $300,000; keep all priorities fixed. Test both.

Answer: Florida remains excluded one cent below its $300,000 setup assumption, then becomes newly eligible at equality and ranks first at 75.50. Its score did not gradually improve: the ceiling is a feasibility assumption. Does the available budget include contingency, working capital and costs this synthetic setup estimate omits?

## 2. Missing data is a policy choice

Reset; set growth weight to zero and inspect Louisiana. Predict whether it enters the shortlist. Compare it with low-scoring but eligible Mississippi and delivery-excluded West Virginia.

Answer: Louisiana remains unscored because this app requires complete information for a comparable shortlist, even if a missing measure currently has zero weight. Missing is not zero. Mississippi is still eligible and ranked; West Virginia has a calculable score but fails its delivery ceiling. Symbols, detail and the table distinguish these states. Debate whether a decision maker should accept a partially observed candidate, and what disclosure or separate review would be needed. Do not fill the missing value with zero to force a rank.

## 3. Assumptions worksheet

Write one sentence of evidence you would need for each question:

| Question | Your evidence or limitation |
| --- | --- |
| Do market size and growth double-count opportunity? | Identify whether size already incorporates future growth and whether the two weights express distinct priorities. |
| Does delivery cost adequately represent route density? | A quote per order omits service frequency, customer dispersion, utilization and actual route constraints. |
| What does the competition index measure? | The index here is invented. A real definition needs a unit, direction, source, date and defensible comparison. |
| Is addressable market company revenue? | No. Total annual opportunity omits reachable share, conversion, pricing, retention and execution. |

The worksheet prompts investigation; adding arbitrary factors would not supply this missing evidence.

## 4. Compare scores, not screenshot shades

Open Map and market detail before and after the growth edit. Inspect the legend and exact values. Predict whether an unchanged shade means an unchanged score.

Answer: bands adapt to the four highest distinct values in each view. A tiny difference can cross a whole band; the same shade in two screenshots can represent different scores. Compare exact scores, normalized weights, gates and rank labels. The copied rationale includes this warning. Select a small state using the map, then its equivalent native selector/table. Movement starts disabled to preserve page navigation; enable it to pan, use zoom controls, and press Escape while the map has focus to stop movement and return to the movement button. Hide/show and Fit all states recover the footprint.

## Optional extension: edit one synthetic assumption

As a separate student implementation, add a local editor for one selected market's growth or delivery estimate. Keep the supplied data immutable, label the edit as a student assumption with a short provenance note, and reset both value and note to the supplied example. For delivery, retain integer cents and distinguish a changed score from crossing the eligibility ceiling. Add tests for changed ranking, invalid/missing value handling, equality, copied provenance and reset. No live feed, geocoding or visitor location is required. This extension is not implemented or claimed in the current app.

## Bounded human checks still required

A novice should attempt exercises 1 and 2 without coaching, then explain one limitation. Record the prediction, wrong turns and explanation. A screen-reader user should change a weight, encounter and recover from a blank input, inspect missing-data detail and copy the rationale, naming the reader/browser and observed announcements. Keyboard/DOM inspection does not stand in for either check. Touch gestures require a real touch-capable session; a narrow desktop frame alone does not prove touch usability.
