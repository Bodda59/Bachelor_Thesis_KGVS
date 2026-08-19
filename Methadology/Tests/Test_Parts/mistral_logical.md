============================================================
  LOGICAL INCONSISTENCY DETECTION — ISOLATION TEST
============================================================
  Total triples injected : 21
  Expected DIRECT_CONFLICT        : 2
  Expected MONOTONICITY_VIOLATION : 3
  Expected TIER_ORDER_VIOLATION   : 2
  Expected false positives        : 0

[detect_logical_inconsistencies] 7 inconsistency/ies
  → [HIGH] DIRECT_CONFLICT: The subject '600' is classified as both 'prime' and 'deep subprime' for the same predicate 'RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL'.
  → [HIGH] DIRECT_CONFLICT: The subject '700' is assigned two different interest rates, '8.31%' and '15%', for the same predicate 'INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE'.
  → [MEDIUM] TIER_ORDER_VIOLATION: A lower credit score '350' is classified as 'super prime', while a higher credit score '800' is classified as 'subprime', violating the required tier order.
  → [MEDIUM] TIER_ORDER_VIOLATION: A lower credit score '500' is classified as 'prime', while a higher credit score '800' is classified as 'subprime', violating the required tier order.
  → [MEDIUM] MONOTONICITY_VIOLATION: A higher credit score '750' has a higher interest rate (14.5%) than a lower credit score '580' (11.91%), violating the DECREASING direction requirement.
  → [MEDIUM] MONOTONICITY_VIOLATION: A higher credit score '800' has a lower approval odds (30%) than a lower credit score '620' (55%), violating the INCREASING direction requirement.
  → [MEDIUM] MONOTONICITY_VIOLATION: A higher credit score '740' has a higher default probability (35%) than a lower credit score '400' (28.7%), violating the DECREASING direction requirement.

============================================================
  RESULTS — 7 inconsistency/ies detected
============================================================

  [1] Type     : DIRECT_CONFLICT
      Severity : HIGH
      Explanation : The subject '600' is classified as both 'prime' and 'deep subprime' for the same predicate 'RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL'.
      Triples involved:
        (600, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, prime)
        (600, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, deep subprime)

  [2] Type     : DIRECT_CONFLICT
      Severity : HIGH
      Explanation : The subject '700' is assigned two different interest rates, '8.31%' and '15%', for the same predicate 'INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE'.
      Triples involved:
        (700, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 8.31%)
        (700, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 15%)

  [3] Type     : TIER_ORDER_VIOLATION
      Severity : MEDIUM
      Explanation : A lower credit score '350' is classified as 'super prime', while a higher credit score '800' is classified as 'subprime', violating the required tier order.
      Triples involved:
        (350, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, super prime)
        (800, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, subprime)

  [4] Type     : TIER_ORDER_VIOLATION
      Severity : MEDIUM
      Explanation : A lower credit score '500' is classified as 'prime', while a higher credit score '800' is classified as 'subprime', violating the required tier order.
      Triples involved:
        (500, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, prime)
        (800, RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL, subprime)

  [5] Type     : MONOTONICITY_VIOLATION
      Severity : MEDIUM
      Explanation : A higher credit score '750' has a higher interest rate (14.5%) than a lower credit score '580' (11.91%), violating the DECREASING direction requirement.
      Triples involved:
        (750, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 14.5%)
        (580, INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE, 11.91%)

  [6] Type     : MONOTONICITY_VIOLATION
      Severity : MEDIUM
      Explanation : A higher credit score '800' has a lower approval odds (30%) than a lower credit score '620' (55%), violating the INCREASING direction requirement.
      Triples involved:
        (800, APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD, 30%)
        (620, APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD, 55%)

  [7] Type     : MONOTONICITY_VIOLATION
      Severity : MEDIUM
      Explanation : A higher credit score '740' has a higher default probability (35%) than a lower credit score '400' (28.7%), violating the DECREASING direction requirement.
      Triples involved:
        (740, DEFAULT_PROBABILITY_RECORDED_AS_HISTORICAL_NONREPAYMENT_RATE, 35%)
        (400, DEFAULT_PROBABILITY_RECORDED_AS_HISTORICAL_NONREPAYMENT_RATE, 28.7%)

============================================================
  EVALUATION vs EXPECTED
============================================================
  ✓  DIRECT_CONFLICT                     expected=2  got=2
  ✓  MONOTONICITY_VIOLATION              expected=3  got=3
  ✓  TIER_ORDER_VIOLATION                expected=2  got=2
  ✓  false_positives                     expected=0  got=0

  RESULT: All expected inconsistencies detected correctly.
============================================================
