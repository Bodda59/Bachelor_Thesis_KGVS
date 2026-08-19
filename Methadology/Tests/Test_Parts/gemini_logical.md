============================================================
  LOGICAL INCONSISTENCY DETECTION — ISOLATION TEST
============================================================
  Total triples injected : 21
  Expected DIRECT_CONFLICT        : 2
  Expected MONOTONICITY_VIOLATION : 3
  Expected TIER_ORDER_VIOLATION   : 2
  Expected false positives        : 0

[detect_logical_inconsistencies] 6 inconsistency/ies
  → [HIGH] DIRECT_CONFLICT: The credit score 600 is simultaneously classified as both 'prime' and 'deep subprime'.
  → [HIGH] DIRECT_CONFLICT: The credit score 700 is assigned two different interest rates of 8.31% and 15% simultaneously.
  → [MEDIUM] TIER_ORDER_VIOLATION: A lower credit score (350) is assigned a higher risk tier (super prime) than a significantly higher credit score (800) assigned as subprime.
  → [MEDIUM] MONOTONICITY_VIOLATION: Higher credit score 800 has lower approval odds (30%) than the lower credit score 740 (89%) for a predicate that must increase with the score.
  → [MEDIUM] MONOTONICITY_VIOLATION: Higher credit score 740 has a higher default probability (35%) than the lower credit score 400 (28.7%) for a predicate that must decrease as the score increases.
  → [MEDIUM] MONOTONICITY_VIOLATION: Higher credit score 750 has a higher interest rate (14.5%) than the lower credit score 660 (9.49%) for a predicate that must decrease as the score increases.

============================================================
  RESULTS — 6 inconsistency/ies detected
============================================================

  [1] Type     : DIRECT_CONFLICT
      Severity : HIGH
      Explanation : The credit score 600 is simultaneously classified as both 'prime' and 'deep subprime'.
      Triples involved:
        (600, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, prime)
        (600, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, deep subprime)

  [2] Type     : DIRECT_CONFLICT
      Severity : HIGH
      Explanation : The credit score 700 is assigned two different interest rates of 8.31% and 15% simultaneously.
      Triples involved:
        (700, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 8.31%)
        (700, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 15%)

  [3] Type     : TIER_ORDER_VIOLATION
      Severity : MEDIUM
      Explanation : A lower credit score (350) is assigned a higher risk tier (super prime) than a significantly higher credit score (800) assigned as subprime.
      Triples involved:
        (350, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, super prime)
        (800, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, subprime)

  [4] Type     : MONOTONICITY_VIOLATION
      Severity : MEDIUM
      Explanation : Higher credit score 800 has lower approval odds (30%) than the lower credit score 740 (89%) for a predicate that must increase with the score.
      Triples involved:
        (740, APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD, 89%)
        (800, APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD, 30%)

  [5] Type     : MONOTONICITY_VIOLATION
      Severity : MEDIUM
      Explanation : Higher credit score 740 has a higher default probability (35%) than the lower credit score 400 (28.7%) for a predicate that must decrease as the score increases.
      Triples involved:
        (400, DEFAULT_PROBABILITY_RECORDED_AS_HISTORICAL_NONREPAYMENT_RATE, 28.7%)
        (740, DEFAULT_PROBABILITY_RECORDED_AS_HISTORICAL_NONREPAYMENT_RATE, 35%)

  [6] Type     : MONOTONICITY_VIOLATION
      Severity : MEDIUM
      Explanation : Higher credit score 750 has a higher interest rate (14.5%) than the lower credit score 660 (9.49%) for a predicate that must decrease as the score increases.
      Triples involved:
        (660, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 9.49%)
        (750, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 14.5%)

============================================================
  EVALUATION vs EXPECTED
============================================================
  ✓  DIRECT_CONFLICT                     expected=2  got=2
  ✓  MONOTONICITY_VIOLATION              expected=3  got=3
  ✗  TIER_ORDER_VIOLATION                expected=2  got=1
  ✓  false_positives                     expected=0  got=0

  RESULT: Some mismatches — review output above.
============================================================
