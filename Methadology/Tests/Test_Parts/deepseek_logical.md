============================================================
  LOGICAL INCONSISTENCY DETECTION — ISOLATION TEST
============================================================
  Total triples injected : 21
  Expected DIRECT_CONFLICT        : 2
  Expected MONOTONICITY_VIOLATION : 3
  Expected TIER_ORDER_VIOLATION   : 2
  Expected false positives        : 0

[detect_logical_inconsistencies] 6 inconsistency/ies
  → [HIGH] DIRECT_CONFLICT: Subject 600 is simultaneously classified as both 'prime' and 'deep subprime' risk tiers.
  → [HIGH] DIRECT_CONFLICT: Subject 700 is assigned two different interest rates, 8.31% and 15%, for the same predicate.
  → [MEDIUM] TIER_ORDER_VIOLATION: Subject 350 (low score) is 'super prime' while subject 800 (high score) is 'subprime', contradicting the required tier order.
  → [MEDIUM] MONOTONICITY_VIOLATION: Subject 580 has an interest rate of 11.91%, which is lower than subject 750's rate of 14.5%, violating the required decreasing trend for interest rates.
  → [MEDIUM] MONOTONICITY_VIOLATION: Subject 620 has approval odds of 55%, which is higher than subject 800's odds of 30%, violating the required increasing trend for approval odds.
  → [MEDIUM] MONOTONICITY_VIOLATION: Subject 400 has a default probability of 28.7%, which is lower than subject 740's probability of 35%, violating the required decreasing trend for default probability.

============================================================
  RESULTS — 6 inconsistency/ies detected
============================================================

  [1] Type     : DIRECT_CONFLICT
      Severity : HIGH
      Explanation : Subject 600 is simultaneously classified as both 'prime' and 'deep subprime' risk tiers.
      Triples involved:
        (600, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, prime)
        (600, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, deep subprime)

  [2] Type     : DIRECT_CONFLICT
      Severity : HIGH
      Explanation : Subject 700 is assigned two different interest rates, 8.31% and 15%, for the same predicate.
      Triples involved:
        (700, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 8.31%)
        (700, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 15%)

  [3] Type     : TIER_ORDER_VIOLATION
      Severity : MEDIUM
      Explanation : Subject 350 (low score) is 'super prime' while subject 800 (high score) is 'subprime', contradicting the required tier order.
      Triples involved:
        (350, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, super prime)
        (800, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, subprime)

  [4] Type     : MONOTONICITY_VIOLATION
      Severity : MEDIUM
      Explanation : Subject 580 has an interest rate of 11.91%, which is lower than subject 750's rate of 14.5%, violating the required decreasing trend for interest rates.
      Triples involved:
        (580, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 11.91%)
        (750, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 14.5%)

  [5] Type     : MONOTONICITY_VIOLATION
      Severity : MEDIUM
      Explanation : Subject 620 has approval odds of 55%, which is higher than subject 800's odds of 30%, violating the required increasing trend for approval odds.
      Triples involved:
        (620, APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD, 55%)
        (800, APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD, 30%)

  [6] Type     : MONOTONICITY_VIOLATION
      Severity : MEDIUM
      Explanation : Subject 400 has a default probability of 28.7%, which is lower than subject 740's probability of 35%, violating the required decreasing trend for default probability.
      Triples involved:
        (400, DEFAULT_PROBABILITY_RECORDED_AS_HISTORICAL_NONREPAYMENT_RATE, 28.7%)
        (740, DEFAULT_PROBABILITY_RECORDED_AS_HISTORICAL_NONREPAYMENT_RATE, 35%)

============================================================
  EVALUATION vs EXPECTED
============================================================
  ✓  DIRECT_CONFLICT                     expected=2  got=2
  ✓  MONOTONICITY_VIOLATION              expected=3  got=3
  ✗  TIER_ORDER_VIOLATION                expected=2  got=1
  ✓  false_positives                     expected=0  got=0

  RESULT: Some mismatches — review output above.
============================================================
