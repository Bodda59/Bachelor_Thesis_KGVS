============================================================
  LOGICAL INCONSISTENCY DETECTION — ISOLATION TEST
============================================================
  Total triples injected : 21
  Expected DIRECT_CONFLICT        : 2
  Expected MONOTONICITY_VIOLATION : 3
  Expected TIER_ORDER_VIOLATION   : 2
  Expected false positives        : 0

[detect_logical_inconsistencies] 5 inconsistency/ies
  → [HIGH] DIRECT_CONFLICT: The subject 600 has two different risk tier classifications: prime and deep subprime.
  → [HIGH] DIRECT_CONFLICT: The subject 700 has two different interest rates: 8.31% and 15%.
  → [MEDIUM] TIER_ORDER_VIOLATION: The subject 350 has a higher risk tier (super prime) than the subject 800 (subprime), despite having a lower credit score.
  → [MEDIUM] MONOTONICITY_VIOLATION: The subject 800 has a lower approval odds (30%) than the subject 620 (55%), despite having a higher credit score.
  → [MEDIUM] MONOTONICITY_VIOLATION: The subject 740 has a higher default probability (35%) than the subject 400 (28.7%), despite having a higher credit score.

============================================================
  RESULTS — 5 inconsistency/ies detected
============================================================

  [1] Type     : DIRECT_CONFLICT
      Severity : HIGH
      Explanation : The subject 600 has two different risk tier classifications: prime and deep subprime.
      Triples involved:
        (600, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, prime)
        (600, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, deep subprime)

  [2] Type     : DIRECT_CONFLICT
      Severity : HIGH
      Explanation : The subject 700 has two different interest rates: 8.31% and 15%.
      Triples involved:
        (700, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 8.31%)
        (700, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 15%)

  [3] Type     : TIER_ORDER_VIOLATION
      Severity : MEDIUM
      Explanation : The subject 350 has a higher risk tier (super prime) than the subject 800 (subprime), despite having a lower credit score.
      Triples involved:
        (350, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, super prime)
        (800, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, subprime)

  [4] Type     : MONOTONICITY_VIOLATION
      Severity : MEDIUM
      Explanation : The subject 800 has a lower approval odds (30%) than the subject 620 (55%), despite having a higher credit score.
      Triples involved:
        (800, APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD, 30%)
        (620, APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD, 55%)

  [5] Type     : MONOTONICITY_VIOLATION
      Severity : MEDIUM
      Explanation : The subject 740 has a higher default probability (35%) than the subject 400 (28.7%), despite having a higher credit score.
      Triples involved:
        (740, DEFAULT_PROBABILITY_RECORDED_AS_HISTORICAL_NONREPAYMENT_RATE, 35%)
        (400, DEFAULT_PROBABILITY_RECORDED_AS_HISTORICAL_NONREPAYMENT_RATE, 28.7%)

============================================================
  EVALUATION vs EXPECTED
============================================================
  ✓  DIRECT_CONFLICT                     expected=2  got=2
  ✗  MONOTONICITY_VIOLATION              expected=3  got=2
  ✗  TIER_ORDER_VIOLATION                expected=2  got=1
  ✓  false_positives                     expected=0  got=0

  RESULT: Some mismatches — review output above.
============================================================
