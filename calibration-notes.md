# Calibration Notes — 2026 FIFA World Cup Predictions

## 2026-07-12 Calibration

### Match: Argentina 3–1 Switzerland (QF, AET)

### Bias patterns found

- **Handicap inflation bias**: Favorites winning by 2+ goals in extra time inflate the margin beyond what 90-min lines cover. A standard -1.5 AHC Argentina bet would have lost at 90 min (1–1) and only covered via ET. Do NOT apply ET goals to 90-min handicap bets.

- **Red card after equalizer, not before**: The Embolo red card (72') came FIVE minutes AFTER Switzerland equalized (67'). This sequence (equalizer → red card) means the 10-man team had already levelled the score, so the numerical disadvantage did not prevent them from controlling for the rest of regulation. This pattern is dangerous for handicap bettors who expect rapid goals after a red card.

- **O/U 2.5 at 90 min under-corrected by red card + defensive shape**: With 10 men, Switzerland defended deep. Score at 90 min was 1–1 (UNDER 2.5). Red cards to a team already level do NOT mechanically produce more goals at 90 min.

- **BTTS safe even in 10 vs 11**: Switzerland scored before the red card, so BTTS was settled early. When BTTS has already happened by the 67th minute, it is not affected by subsequent red cards.

- **Knockout round ET frequency**: Both July 11/12 QF matches went to extra time (England-Norway, Argentina-Switzerland). Knockout matches with evenly-matched teams should have ET probability priced higher (~35-40% for QF stage). Standard AHC lines do not account for ET.

### Adjustments for next prediction

- **Semi-finals (July 14–15)**: Both remaining matches feature high-quality teams. Expect ET probability ~30-40% per match. Avoid AHC lines requiring +1 margin at 90 minutes unless odds are very favorable.

- **O/U for high-stakes matches**: Knockout games trend UNDER at 90 min compared to group stage. Recommend pricing knockout O/U at ~2.0 goals rather than 2.5 if betting 90-min markets. Argentina-England especially likely to be cautious.

- **Argentina AHC caution**: Argentina only scored twice in the final 8 minutes + 2' of added time against 10-man Switzerland. Do not assume Argentina will cover -1 AHC against a full-strength England.

- **BTTS for semi-finals**: Both Spain-France and Argentina-England have high attacking talent on both sides. BTTS YES is defensible, but defensive organization at this stage is elite — price it at ~55-60% probability, not higher.

- **Resume predictions immediately**: No knockout prediction has been filed since group stage (last: 2026-06-16). The system needs to generate predictions for:
  - 2026-07-14: France vs Spain
  - 2026-07-15: Argentina vs England

---

*First calibration entry. Updated: 2026-07-13. Match reviewed: 2026-07-12.*

---

## 2026-07-17 Calibration

### Matches reviewed: SF1 France 0–2 Spain (Jul 14) | SF2 England 1–2 Argentina (Jul 15)
### Status: Rest Day (Jul 17) — no matches

### Bias patterns found

- **O/U 2.5 split outcome**: Spain–France was UNDER 2.5 (2 goals). England–Argentina was OVER 2.5 (3 goals). The prior calibration note (Jul 12) recommended pricing knockout O/U at 2.0 for 90-min markets — both semi-finals confirm this is a fragile call: final-minute goals (85', ~90') swung the England–Argentina total over 2.5. Single late goals can flip O/U at 90 min in knockout matches.

- **BTTS calibration: correct direction, wrong confidence**: Jul 12 note priced BTTS at ~55-60%. Actual results: SF1 No BTTS (Spain kept clean sheet), SF2 BTTS YES. 1/2 hit rate matches the 55% probability estimate. However, Spain's defensive profile (0.3 xG conceded vs France) makes their clean sheet far more predictable in hindsight — the Spain match should have been priced at ~30% BTTS, not 55%.

- **Spain's xGA is an extreme outlier**: Across 7 matches, Spain conceded only 1 goal (vs Belgium in QF). xGA in SF was 0.3. This is statistically extraordinary and should have been the primary input for Spain match predictions: strong Under 2.5, No BTTS, -AHC Spain. Narrative bias (France's squad depth) overrode objective defensive metrics.

- **Argentina's late-game trait is now a two-instance pattern**: Jul 12 Argentina won in extra time (goals at 112', 120+1'). Jul 15 Argentina won via goals at 85' and ~90'. In both matches, Argentina trailed or were level at the 84th minute and found a winner. This is a repeatable strategic trait — they absorb pressure and strike late with individual quality (Messi assist, Fernandez from distance, Martinez headers).

- **No prediction files still missing**: Third consecutive match day without a prediction file in `predictions/`. The workflow has never filed a prediction during the knockout stage.

- **Favorite mis-identification**: README predicted France as #1 (champion). Spain beat France 2-0 with France generating 0.3 xG — the most one-sided semi-final possible. Pre-tournament odds (France +420) were significantly worse predictors than Spain's in-tournament defensive metrics.

### Adjustments for next prediction

- **Final (Jul 19): Spain vs Argentina**: This is the only remaining match to predict.
  - **Score prediction**: Spain 1-0 or 1-1 AET. Spain's defense makes 0 goals conceded likely; Argentina need a Messi-level moment to break through.
  - **O/U**: Strongly favor Under 2.5. Spain have held 5 of 7 opponents scoreless. Argentina's forward line is dangerous but Spain is the best defense left.
  - **BTTS**: Lean NO. Spain concede ~0.14 goals per match; Argentina need to score 1 against the tournament's best defense. Price BTTS NO at ~65%.
  - **AHC**: Spain -0.5 AHC is the safe pick. Argentina +0.5 AHC offers value if backing the draw/Argentina scenario.
  - **Result**: Spain to win in 90 min or AET. Price Spain at ~55% to win, Draw ~25%, Argentina ~20%.

- **Weight xGA over pre-tournament odds**: For remaining predictions, use in-tournament stats (goals per game, xG, xGA) as primary inputs. Pre-tournament market odds are now significantly stale relative to 7-match tournament form.

- **Late-goal risk management for Argentina**: Do not settle any Argentina prediction before 85 minutes. Their pattern strongly suggests late efficiency — any in-play or pre-match handicap that requires Argentina to score first is risky.

- **Process fix**: Before Jul 18 bronze final (France vs England), generate and save `predictions/2026-07-18.md`. Before Jul 19 final, generate `predictions/2026-07-19.md`. These are the only two remaining match days in the tournament.

---

*Updated: 2026-07-17. Semifinal results reviewed.*
