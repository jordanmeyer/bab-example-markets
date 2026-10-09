# How Replenish was built

## Opening request

“I need to prioritize regional markets for a fictional retail expansion. Show a map with plausible synthetic demand, competition and operating-cost data, let me change our priorities, and explain why rankings move. I want to compare shortlisted markets without sending data to a service or suggesting the sample predicts actual returns.”

## Actual planning records

[PLANNING-CONVERSATION.md](PLANNING-CONVERSATION.md) is the original simulated planning exchange, not a real student interview. It chose the refill-supply service, twelve-state footprint, fixed anchors and eligibility gates. The owner's October9 live revision request adds explicit rank-change causes and sensitivity. [PLAN.md](PLAN.md) defines the current contract; [DECISIONS.md](DECISIONS.md) explains what changed and why.

## The lesson

The starting priorities rank Georgia67.50 ahead of Tennessee67.00. Raising growth weight25→70 reverses them: Tennessee's10.8% growth beats Georgia's8.4%, and that component's relative contribution grows from5.00 to9.66 points. Holding all other settings fixed, the whole-number sweep puts Georgia first at0–27 and Tennessee at28–100. Gates are different from weights: a high score cannot overcome a failed setup ceiling. Real state boundaries supply geography; every commercial number is invented.

## Recipes and implementation

Browser App Builder Build, Evaluate, Deploy and Leaflet guidance structure the workflow. Leaflet1.9.4 renders locally bundled public Census polygons with native selector/table alternatives. Plain JavaScript owns scoring, gates, rank explanations and sensitivity. Campus Designer supplies color and locally licensed EB Garamond/Open Sans typography, with no institutional marks or affiliation. The palette ranks visible scores with ordered blue bands; it never changes model anchors. Exact dependencies are pinned, and no tiles, fonts, data, analytics or location are fetched from a remote service at runtime.

## Evidence and limits

[Evaluation](EVALUATION.md) retains actual checks and failed rounds; [independent review](REVIEW.md) names reviewed commits; [deployment](DEPLOYMENT.md) identifies published versions. Sensitivity checks whole-number weights, not every possible fractional crossover. Scores are discussion aids, not forecasts, customer discovery or actual market attractiveness. Inputs remain in memory; copied rationale carries the assumptions and provenance.

## Try the lesson

[Prediction exercises and answers](WALKTHROUGH.md) connect weight sensitivity, Florida's feasibility ceiling, Louisiana's missing-data policy and a short assumptions worksheet. An optional one-assumption editor is a bounded student extension, not an implemented feature. Current corrections use precise addressable-market terminology and distinguish map status from priority. Screen-reader, novice and physical touch evidence is not claimed.


The enlarged-text review exposed a layout failure even though the document width fit: Reset overlapped the ranking and a weight digit clipped. The control layout now wraps according to text-relative preferred widths, stacks each input above its normalized share and lets the heading/reset row wrap. The failed round remains in EVALUATION; this source change awaits an actual production visual retest.
