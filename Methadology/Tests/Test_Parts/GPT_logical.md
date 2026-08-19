============================================================
  LOGICAL INCONSISTENCY DETECTION — ISOLATION TEST
============================================================
  Total triples injected : 21
  Expected DIRECT_CONFLICT        : 2
  Expected MONOTONICITY_VIOLATION : 3
  Expected TIER_ORDER_VIOLATION   : 2
  Expected false positives        : 0

[detect_logical_inconsistencies] 6 inconsistency/ies
  → [HIGH] DIRECT_CONFLICT: Credit score 600 is classified both as 'prime' and 'deep subprime' for risk tier, which are logically incompatible classifications.
  → [HIGH] DIRECT_CONFLICT: Credit score 700 has two different annual interest rates assigned: 8.31% and 15%.
  → [MEDIUM] TIER_ORDER_VIOLATION: A lower credit score (350) is classified as 'super prime' while a higher credit score (800) is classified as 'subprime', violating tier order.
  → [MEDIUM] MONOTONICITY_VIOLATION: A lower credit score (580) has an interest rate of 11.91% while a higher score (750) has a higher rate of 14.5%, which violates the required decreasing direction.
  → [MEDIUM] MONOTONICITY_VIOLATION: Higher credit score (800) has a lower approval odds percentage (30%) than lower credit score (620) with 55%, violating the required increasing direction.
  → [MEDIUM] MONOTONICITY_VIOLATION: Higher credit score (740) has a higher default probability (35%) compared to lower score (400) with 28.7%, violating the required decreasing direction.

============================================================
  RESULTS — 6 inconsistency/ies detected
============================================================

  [1] Type     : DIRECT_CONFLICT
      Severity : HIGH
      Explanation : Credit score 600 is classified both as 'prime' and 'deep subprime' for risk tier, which are logically incompatible classifications.
      Triples involved:
        (600, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, prime)
        (600, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, deep subprime)

  [2] Type     : DIRECT_CONFLICT
      Severity : HIGH
      Explanation : Credit score 700 has two different annual interest rates assigned: 8.31% and 15%.
      Triples involved:
        (700, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 8.31%)
        (700, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 15%)

  [3] Type     : TIER_ORDER_VIOLATION
      Severity : MEDIUM
      Explanation : A lower credit score (350) is classified as 'super prime' while a higher credit score (800) is classified as 'subprime', violating tier order.
      Triples involved:
        (350, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, super prime)
        (800, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, subprime)

  [4] Type     : MONOTONICITY_VIOLATION
      Severity : MEDIUM
      Explanation : A lower credit score (580) has an interest rate of 11.91% while a higher score (750) has a higher rate of 14.5%, which violates the required decreasing direction.
      Triples involved:
        (580, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 11.91%)
        (750, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 14.5%)

  [5] Type     : MONOTONICITY_VIOLATION
      Severity : MEDIUM
      Explanation : Higher credit score (800) has a lower approval odds percentage (30%) than lower credit score (620) with 55%, violating the required increasing direction.
      Triples involved:
        (620, APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD, 55%)
        (800, APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD, 30%)

  [6] Type     : MONOTONICITY_VIOLATION
      Severity : MEDIUM
      Explanation : Higher credit score (740) has a higher default probability (35%) compared to lower score (400) with 28.7%, violating the required decreasing direction.
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
