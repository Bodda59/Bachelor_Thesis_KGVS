============================================================
  LOGICAL INCONSISTENCY DETECTION — ISOLATION TEST
============================================================
  Total triples injected : 21
  Expected DIRECT_CONFLICT        : 2
  Expected MONOTONICITY_VIOLATION : 3
  Expected TIER_ORDER_VIOLATION   : 2
  Expected false positives        : 0

[detect_logical_inconsistencies] 7 inconsistency/ies
  → [HIGH] DIRECT_CONFLICT: Subject 600 is classified as both 'prime' and 'deep subprime' for the same risk tier predicate.
  → [HIGH] DIRECT_CONFLICT: Subject 700 has conflicting interest rates of 8.31% and 15% for the same predicate.
  → [MEDIUM] MONOTONICITY_VIOLATION: Score 750 has a higher interest rate (14.5%) than score 660 (9.49%), violating the required decreasing direction.
  → [MEDIUM] MONOTONICITY_VIOLATION: Score 800 has lower approval odds (30%) than score 740 (89%), violating the required increasing direction.
  → [MEDIUM] MONOTONICITY_VIOLATION: Score 740 has a higher default probability (35%) than score 400 (28.7%), violating the required decreasing direction.
  → [MEDIUM] TIER_ORDER_VIOLATION: Score 350 is classified as 'super prime' while score 800 is classified as 'subprime', violating the tier order.
  → [MEDIUM] TIER_ORDER_VIOLATION: Score 500 is classified as 'prime' while score 580 is classified as 'subprime', violating the tier order.

============================================================
  RESULTS — 7 inconsistency/ies detected
============================================================

  [1] Type     : DIRECT_CONFLICT
      Severity : HIGH
      Explanation : Subject 600 is classified as both 'prime' and 'deep subprime' for the same risk tier predicate.
      Triples involved:
        (600, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, prime)
        (600, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, deep subprime)

  [2] Type     : DIRECT_CONFLICT
      Severity : HIGH
      Explanation : Subject 700 has conflicting interest rates of 8.31% and 15% for the same predicate.
      Triples involved:
        (700, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 8.31%)
        (700, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 15%)

  [3] Type     : MONOTONICITY_VIOLATION
      Severity : MEDIUM
      Explanation : Score 750 has a higher interest rate (14.5%) than score 660 (9.49%), violating the required decreasing direction.
      Triples involved:
        (750, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 14.5%)
        (660, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 9.49%)

  [4] Type     : MONOTONICITY_VIOLATION
      Severity : MEDIUM
      Explanation : Score 800 has lower approval odds (30%) than score 740 (89%), violating the required increasing direction.
      Triples involved:
        (800, APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD, 30%)
        (740, APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD, 89%)

  [5] Type     : MONOTONICITY_VIOLATION
      Severity : MEDIUM
      Explanation : Score 740 has a higher default probability (35%) than score 400 (28.7%), violating the required decreasing direction.
      Triples involved:
        (740, DEFAULT_PROBABILITY_RECORDED_AS_HISTORICAL_NONREPAYMENT_RATE, 35%)
        (400, DEFAULT_PROBABILITY_RECORDED_AS_HISTORICAL_NONREPAYMENT_RATE, 28.7%)

  [6] Type     : TIER_ORDER_VIOLATION
      Severity : MEDIUM
      Explanation : Score 350 is classified as 'super prime' while score 800 is classified as 'subprime', violating the tier order.
      Triples involved:
        (350, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, super prime)
        (800, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, subprime)

  [7] Type     : TIER_ORDER_VIOLATION
      Severity : MEDIUM
      Explanation : Score 500 is classified as 'prime' while score 580 is classified as 'subprime', violating the tier order.
      Triples involved:
        (500, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, prime)
        (580, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, subprime)

============================================================
  EVALUATION vs EXPECTED
============================================================
  ✓  DIRECT_CONFLICT                     expected=2  got=2
  ✓  MONOTONICITY_VIOLATION              expected=3  got=3
  ✓  TIER_ORDER_VIOLATION                expected=2  got=2
  ✓  false_positives                     expected=0  got=0

  RESULT: All expected inconsistencies detected correctly.
============================================================
