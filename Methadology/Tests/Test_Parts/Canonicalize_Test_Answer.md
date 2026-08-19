
============================================================
  Running step: extract_triples
============================================================
Here are the structured answers to your questions based on the provided dataset and general credit knowledge:

---

### **Risk Category for a 580 Credit Score**
```json
{"Subject":"580","Predicate":"risk tier","Object":"subprime"}
```

### **Annual Borrowing Cost for a 700 Credit Score**
```json
{"Subject":"700","Predicate":"interest rate","Object":"8.31%"}
```

### **Approval Odds for a 500 Credit Score**
```json
{"Subject":"500","Predicate":"approval odds","Object":"29%"}
```

### **Maximum Monthly Debt Burden Ceiling for a 620 Credit Score**
*(Expressed as maximum debt-to-income ratio, which is a monthly/annual metric)*
```json
{"Subject":"620","Predicate":"maximum debt-to-income ratio","Object":"42%"}
```

### **Repayment Window for a 740 Credit Score**
```json
{"Subject":"740","Predicate":"loan term","Object":"60 to 84 months"}
```

### **Upfront Cash Contribution for a 500 Credit Score**
```json
{"Subject":"500","Predicate":"down payment","Object":"15.4%"}
```

### **Income-Based Borrowing Ceiling Factor for a 660 Credit Score**
```json
{"Subject":"660","Predicate":"credit limit multiplier","Object":"2.63x"}
```

### **Historical Nonrepayment Rate for a 400 Credit Score**
```json
{"Subject":"400","Predicate":"default probability","Object":"28.7%"}
```

### **Lender Categories Accessible for a 580 Credit Score**
```json
{"Subject":"580","Predicate":"lender pool","Object":"subprime banks"}
```

### **Tier Entered When Crossing from 619 to 620**
```json
{"Subject":"619 to 620","Predicate":"risk tier transition","Object":"from subprime to near prime"}
```

### **Approval Odds for an 850 Credit Score**
```json
{"Subject":"850","Predicate":"approval odds","Object":"99%"}
```

### **Initial Payment Percentage for a Super Prime Borrower at 740**
```json
{"Subject":"740","Predicate":"down payment","Object":"4.3%"}
```

### **Nonrepayment Rate for a 580 Credit Score**
```json
{"Subject":"580","Predicate":"default probability","Object":"11.3%"}
```

### **Classification of a 300-Score Borrower in Lending Danger**
```json
{"Subject":"300","Predicate":"risk classification","Object":"deep subprime (highest-risk borrower)"}
```

### **Lender Types Accessible to a Deep Subprime Borrower at 350**
```json
{"Subject":"350","Predicate":"lender pool","Object":"specialty finance companies"}
```

### **Income Multiplier for Borrowing Ceiling at 800**
```json
{"Subject":"800","Predicate":"credit limit multiplier","Object":"5.13x"}
```

### **Debt-to-Income Ceiling for an 850 Credit Score**
```json
{"Subject":"850","Predicate":"maximum debt-to-income ratio","Object":"52%"}
```

### **Annual Borrowing Cost for a 660 Credit Score**
```json
{"Subject":"660","Predicate":"interest rate","Object":"9.49%"}
```

### **Maximum Loan Repayment Duration for an 800-Score Borrower**
```json
{"Subject":"800","Predicate":"loan term","Object":"84 months"}
```

### **Risk Band Upgrades from 580 to 660**
```json
{"Subject":"580 to 660","Predicate":"risk tier upgrades","Object":"2 (subprime → near prime → prime)"}
```

---

### **General Credit Knowledge Questions**

### **Ideal Credit Score for Securing a First-Home Mortgage**
```json
{"Subject":"mortgage","Predicate":"ideal credit score","Object":"620 or higher (near prime or above); 740+ is considered excellent for the best rates"}
```

### **Time to Improve from Subprime to Prime**
```json
{"Subject":"credit score improvement","Predicate":"time from subprime to prime","Object":"12 to 24 months (depends on individual actions like paying bills on time, reducing debt, and avoiding new credit applications)"}
```

### **Most Commonly Used Credit Bureau**
```json
{"Subject":"credit bureaus","Predicate":"most commonly used","Object":"FICO score (used by ~90% of lenders); Equifax, Experian, and TransUnion provide the underlying data"}
```

### **Effect of a Missed Payment on Credit Score**
```json
{"Subject":"missed payment","Predicate":"impact on credit score","Object":"Can drop score by 50–100+ points; impact lessens over time (typically 7 years) but remains on credit report"}
```

### **Average Credit Score in the U.S.**
```json
{"Subject":"U.S. adults","Predicate":"average credit score","Object":"715 (as of 2023, per Experian)"}
```

### **Negotiating Interest Rates with Lenders**
```json
{"Subject":"interest rate negotiation","Predicate":"possibility","Object":"Possible but limited; lenders may adjust rates for strong borrowers (e.g., super prime) or with collateral. Deep subprime borrowers have little leverage."}
```

### **Impact of Opening Multiple Credit Cards Quickly**
```json
{"Subject":"multiple credit cards","Predicate":"impact on creditworthiness","Object":"Lowers score temporarily due to hard inquiries and reduced average account age; may signal risk to lenders"}
```

### **Government Programs for Deep Subprime Borrowers**
```json
{"Subject":"deep subprime borrowers","Predicate":"government programs","Object":"FHA loans (3.5% down, 580+ score), VA loans (no minimum score), USDA loans, and nonprofit credit counseling (e.g., NFCC)"}
```

### **Effect of Bankruptcy on Lender Access**
```json
{"Subject":"bankruptcy","Predicate":"impact on lender access","Object":"Severely limits access for 7–10 years (Chapter 7) or 3–5 years (Chapter 13); deep subprime lenders may still approve but at high rates"}
```

### **Difference Between FICO and Equifax/TransUnion Scores**
```json
{"Subject":"credit scores","Predicate":"FICO vs. bureau scores","Object":"FICO is a proprietary model used by lenders; Equifax/TransUnion produce their own scores (e.g., VantageScore) but FICO is the industry standard"}
```

Extracted triples (JSON):
[
  {
    "subject": "580",
    "predicate": "HAS_RISK_TIER",
    "object": "subprime",
    "predicate_definition": "The risk category associated with a specific credit score."
  },
  {
    "subject": "700",
    "predicate": "HAS_INTEREST_RATE",
    "object": "8.31%",
    "predicate_definition": "The annual percentage rate charged for borrowing."
  },
  {
    "subject": "500",
    "predicate": "HAS_APPROVAL_ODDS",
    "object": "29%",
    "predicate_definition": "The likelihood of being approved for credit."
  },
  {
    "subject": "620",
    "predicate": "HAS_MAXIMUM_DEBT_TO_INCOME_RATIO",
    "object": "42%",
    "predicate_definition": "The highest ratio of monthly debt payments to monthly income allowed."
  },
  {
    "subject": "740",
    "predicate": "HAS_LOAN_TERM",
    "object": "60 to 84 months",
    "predicate_definition": "The duration of time over which a loan must be repaid."
  },
  {
    "subject": "500",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "15.4%",
    "predicate_definition": "The percentage of the purchase price required as an upfront payment."
  },
  {
    "subject": "660",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "2.63x",
    "predicate_definition": "The factor by which income is multiplied to determine the borrowing ceiling."
  },
  {
    "subject": "400",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "28.7%",
    "predicate_definition": "The statistical likelihood that a borrower will fail to repay a loan."
  },
  {
    "subject": "580",
    "predicate": "HAS_LENDER_POOL",
    "object": "subprime banks",
    "predicate_definition": "The category of financial institutions likely to lend to this borrower."
  },
  {
    "subject": "619 to 620",
    "predicate": "HAS_RISK_TIER_TRANSITION",
    "object": "from subprime to near prime",
    "predicate_definition": "The change in risk classification when moving between specific score ranges."
  },
  {
    "subject": "850",
    "predicate": "HAS_APPROVAL_ODDS",
    "object": "99%",
    "predicate_definition": "The likelihood of being approved for credit."
  },
  {
    "subject": "740",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "4.3%",
    "predicate_definition": "The percentage of the purchase price required as an upfront payment."
  },
  {
    "subject": "580",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "11.3%",
    "predicate_definition": "The statistical likelihood that a borrower will fail to repay a loan."
  },
  {
    "subject": "300",
    "predicate": "HAS_RISK_CLASSIFICATION",
    "object": "deep subprime (highest-risk borrower)",
    "predicate_definition": "The specific risk label assigned to a borrower based on their credit score."
  },
  {
    "subject": "350",
    "predicate": "HAS_LENDER_POOL",
    "object": "specialty finance companies",
    "predicate_definition": "The category of financial institutions likely to lend to this borrower."
  },
  {
    "subject": "800",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "5.13x",
    "predicate_definition": "The factor by which income is multiplied to determine the borrowing ceiling."
  },
  {
    "subject": "850",
    "predicate": "HAS_MAXIMUM_DEBT_TO_INCOME_RATIO",
    "object": "52%",
    "predicate_definition": "The highest ratio of monthly debt payments to monthly income allowed."
  },
  {
    "subject": "660",
    "predicate": "HAS_INTEREST_RATE",
    "object": "9.49%",
    "predicate_definition": "The annual percentage rate charged for borrowing."
  },
  {
    "subject": "800",
    "predicate": "HAS_LOAN_TERM",
    "object": "84 months",
    "predicate_definition": "The duration of time over which a loan must be repaid."
  },
  {
    "subject": "580 to 660",
    "predicate": "HAS_RISK_TIER_UPGRADE_COUNT",
    "object": "2 (subprime \u2192 near prime \u2192 prime)",
    "predicate_definition": "The number of risk category improvements achieved by increasing a credit score across a specific range."
  },
  {
    "subject": "mortgage",
    "predicate": "HAS_IDEAL_CREDIT_SCORE",
    "object": "620 or higher (near prime or above); 740+ is considered excellent for the best rates",
    "predicate_definition": "The recommended credit score range to secure favorable mortgage terms."
  },
  {
    "subject": "credit score improvement",
    "predicate": "HAS_TIME_FROM_SUBPRIME_TO_PRIME",
    "object": "12 to 24 months (depends on individual actions like paying bills on time, reducing debt, and avoiding new credit applications)",
    "predicate_definition": "The estimated duration required to move from a subprime to a prime credit score."
  },
  {
    "subject": "credit bureaus",
    "predicate": "HAS_MOST_COMMONLY_USED_SCORE",
    "object": "FICO score (used by ~90% of lenders); Equifax, Experian, and TransUnion provide the underlying data",
    "predicate_definition": "The specific scoring model most frequently utilized by lenders."
  },
  {
    "subject": "missed payment",
    "predicate": "HAS_IMPACT_ON_CREDIT_SCORE",
    "object": "Can drop score by 50\u2013100+ points; impact lessens over time (typically 7 years) but remains on credit report",
    "predicate_definition": "The effect a failure to make a payment has on a borrower's credit score."
  },
  {
    "subject": "U.S. adults",
    "predicate": "HAS_AVERAGE_CREDIT_SCORE",
    "object": "715 (as of 2023, per Experian)",
    "predicate_definition": "The mean credit score value for the adult population in the United States."
  },
  {
    "subject": "interest rate negotiation",
    "predicate": "HAS_POSSIBILITY",
    "object": "Possible but limited; lenders may adjust rates for strong borrowers (e.g., super prime) or with collateral. Deep subprime borrowers have little leverage.",
    "predicate_definition": "The feasibility of altering the interest rate offered by a lender."
  },
  {
    "subject": "multiple credit cards",
    "predicate": "HAS_IMPACT_ON_CREDITWORTHINESS",
    "object": "Lowers score temporarily due to hard inquiries and reduced average account age; may signal risk to lenders",
    "predicate_definition": "The effect of opening several credit card accounts in a short period on a borrower's perceived reliability."
  },
  {
    "subject": "deep subprime borrowers",
    "predicate": "HAS_GOVERNMENT_PROGRAMS",
    "object": "FHA loans (3.5% down, 580+ score), VA loans (no minimum score), USDA loans, and nonprofit credit counseling (e.g., NFCC)",
    "predicate_definition": "The federal or state assistance options available to borrowers with very low credit scores."
  },
  {
    "subject": "bankruptcy",
    "predicate": "HAS_IMPACT_ON_LENDER_ACCESS",
    "object": "Severely limits access for 7\u201310 years (Chapter 7) or 3\u20135 years (Chapter 13); deep subprime lenders may still approve but at high rates",
    "predicate_definition": "The effect of declaring bankruptcy on the ability to obtain future credit."
  },
  {
    "subject": "credit scores",
    "predicate": "HAS_FICO_VS_BUREAU_SCORES_DIFFERENCE",
    "object": "FICO is a proprietary model used by lenders; Equifax/TransUnion produce their own scores (e.g., VantageScore) but FICO is the industry standard",
    "predicate_definition": "The distinction between the FICO scoring model and scores generated directly by credit bureaus."
  }
]

============================================================
  Running step: canonicalize_triples
============================================================

[GPT] canonicalized 30 triples:
[
  {
    "model": "GPT",
    "original": {
      "subject": "580",
      "predicate": "HAS_RISK_TIER",
      "object": "subprime"
    },
    "canonical": {
      "subject": "580",
      "predicate": "RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL",
      "object": "subprime"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "700",
      "predicate": "HAS_INTEREST_RATE",
      "object": "8.31%"
    },
    "canonical": {
      "subject": "700",
      "predicate": "INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE",
      "object": "8.31%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "500",
      "predicate": "HAS_APPROVAL_ODDS",
      "object": "29%"
    },
    "canonical": {
      "subject": "500",
      "predicate": "APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD",
      "object": "29%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "620",
      "predicate": "HAS_MAXIMUM_DEBT_TO_INCOME_RATIO",
      "object": "42%"
    },
    "canonical": {
      "subject": "620",
      "predicate": "MAX_DTI_PERMITTED_AS_MONTHLY_DEBT_BURDEN_CEILING",
      "object": "42%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "740",
      "predicate": "HAS_LOAN_TERM",
      "object": "60 to 84 months"
    },
    "canonical": {
      "subject": "740",
      "predicate": "LOAN_TERM_GRANTED_AS_MAXIMUM_REPAYMENT_WINDOW_OFFERED",
      "object": "60 to 84 months"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "500",
      "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
      "object": "15.4%"
    },
    "canonical": {
      "subject": "500",
      "predicate": "DOWN_PAYMENT_REQUIRED_AS_UPFRONT_BORROWER_CASH_CONTRIBUTION",
      "object": "15.4%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "660",
      "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
      "object": "2.63x"
    },
    "canonical": {
      "subject": "660",
      "predicate": "CREDIT_LIMIT_MULTIPLIER_APPLIED_AS_INCOME_BASED_BORROWING_CEILING_FACTOR",
      "object": "2.63x"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "400",
      "predicate": "HAS_DEFAULT_PROBABILITY",
      "object": "28.7%"
    },
    "canonical": {
      "subject": "400",
      "predicate": "DEFAULT_PROBABILITY_RECORDED_AS_HISTORICAL_NONREPAYMENT_RATE",
      "object": "28.7%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "580",
      "predicate": "HAS_LENDER_POOL",
      "object": "subprime banks"
    },
    "canonical": {
      "subject": "580",
      "predicate": "LENDER_POOL_ACCESSIBLE_AS_AVAILABLE_INSTITUTION_CATEGORY_FOR_THIS_SCORE",
      "object": "subprime banks"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "619 to 620",
      "predicate": "HAS_RISK_TIER_TRANSITION",
      "object": "from subprime to near prime"
    },
    "canonical": {
      "subject": "619 to 620",
      "predicate": "TIER_PROGRESSION_UPGRADES_INTO_NEXT_RISK_CLASSIFICATION_BAND",
      "object": "from subprime to near prime"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "850",
      "predicate": "HAS_APPROVAL_ODDS",
      "object": "99%"
    },
    "canonical": {
      "subject": "850",
      "predicate": "APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD",
      "object": "99%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "740",
      "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
      "object": "4.3%"
    },
    "canonical": {
      "subject": "740",
      "predicate": "DOWN_PAYMENT_REQUIRED_AS_UPFRONT_BORROWER_CASH_CONTRIBUTION",
      "object": "4.3%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "580",
      "predicate": "HAS_DEFAULT_PROBABILITY",
      "object": "11.3%"
    },
    "canonical": {
      "subject": "580",
      "predicate": "DEFAULT_PROBABILITY_RECORDED_AS_HISTORICAL_NONREPAYMENT_RATE",
      "object": "11.3%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "300",
      "predicate": "HAS_RISK_CLASSIFICATION",
      "object": "deep subprime (highest-risk borrower)"
    },
    "canonical": {
      "subject": "300",
      "predicate": "RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL",
      "object": "deep subprime (highest-risk borrower)"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "350",
      "predicate": "HAS_LENDER_POOL",
      "object": "specialty finance companies"
    },
    "canonical": {
      "subject": "350",
      "predicate": "LENDER_POOL_ACCESSIBLE_AS_AVAILABLE_INSTITUTION_CATEGORY_FOR_THIS_SCORE",
      "object": "specialty finance companies"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "800",
      "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
      "object": "5.13x"
    },
    "canonical": {
      "subject": "800",
      "predicate": "CREDIT_LIMIT_MULTIPLIER_APPLIED_AS_INCOME_BASED_BORROWING_CEILING_FACTOR",
      "object": "5.13x"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "850",
      "predicate": "HAS_MAXIMUM_DEBT_TO_INCOME_RATIO",
      "object": "52%"
    },
    "canonical": {
      "subject": "850",
      "predicate": "MAX_DTI_PERMITTED_AS_MONTHLY_DEBT_BURDEN_CEILING",
      "object": "52%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "660",
      "predicate": "HAS_INTEREST_RATE",
      "object": "9.49%"
    },
    "canonical": {
      "subject": "660",
      "predicate": "INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE",
      "object": "9.49%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "800",
      "predicate": "HAS_LOAN_TERM",
      "object": "84 months"
    },
    "canonical": {
      "subject": "800",
      "predicate": "LOAN_TERM_GRANTED_AS_MAXIMUM_REPAYMENT_WINDOW_OFFERED",
      "object": "84 months"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "580 to 660",
      "predicate": "HAS_RISK_TIER_UPGRADE_COUNT",
      "object": "2 (subprime \u2192 near prime \u2192 prime)"
    },
    "canonical": {
      "subject": "580 to 660",
      "predicate": "TIER_PROGRESSION_UPGRADES_INTO_NEXT_RISK_CLASSIFICATION_BAND",
      "object": "2 (subprime \u2192 near prime \u2192 prime)"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "mortgage",
      "predicate": "HAS_IDEAL_CREDIT_SCORE",
      "object": "620 or higher (near prime or above); 740+ is considered excellent for the best rates"
    },
    "canonical": {
      "subject": "mortgage",
      "predicate": "HAS_IDEAL_CREDIT_SCORE",
      "object": "620 or higher (near prime or above); 740+ is considered excellent for the best rates"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "credit score improvement",
      "predicate": "HAS_TIME_FROM_SUBPRIME_TO_PRIME",
      "object": "12 to 24 months (depends on individual actions like paying bills on time, reducing debt, and avoiding new credit applications)"
    },
    "canonical": {
      "subject": "credit score improvement",
      "predicate": "HAS_TIME_FROM_SUBPRIME_TO_PRIME",
      "object": "12 to 24 months (depends on individual actions like paying bills on time, reducing debt, and avoiding new credit applications)"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "credit bureaus",
      "predicate": "HAS_MOST_COMMONLY_USED_SCORE",
      "object": "FICO score (used by ~90% of lenders); Equifax, Experian, and TransUnion provide the underlying data"
    },
    "canonical": {
      "subject": "credit bureaus",
      "predicate": "HAS_MOST_COMMONLY_USED_SCORE",
      "object": "FICO score (used by ~90% of lenders); Equifax, Experian, and TransUnion provide the underlying data"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "missed payment",
      "predicate": "HAS_IMPACT_ON_CREDIT_SCORE",
      "object": "Can drop score by 50\u2013100+ points; impact lessens over time (typically 7 years) but remains on credit report"
    },
    "canonical": {
      "subject": "missed payment",
      "predicate": "HAS_IMPACT_ON_CREDIT_SCORE",
      "object": "Can drop score by 50\u2013100+ points; impact lessens over time (typically 7 years) but remains on credit report"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "U.S. adults",
      "predicate": "HAS_AVERAGE_CREDIT_SCORE",
      "object": "715 (as of 2023, per Experian)"
    },
    "canonical": {
      "subject": "U.S. adults",
      "predicate": "HAS_AVERAGE_CREDIT_SCORE",
      "object": "715 (as of 2023, per Experian)"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "interest rate negotiation",
      "predicate": "HAS_POSSIBILITY",
      "object": "Possible but limited; lenders may adjust rates for strong borrowers (e.g., super prime) or with collateral. Deep subprime borrowers have little leverage."
    },
    "canonical": {
      "subject": "interest rate negotiation",
      "predicate": "HAS_POSSIBILITY",
      "object": "Possible but limited; lenders may adjust rates for strong borrowers (e.g., super prime) or with collateral. Deep subprime borrowers have little leverage."
    },
    "match_confidence": "LOW"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "multiple credit cards",
      "predicate": "HAS_IMPACT_ON_CREDITWORTHINESS",
      "object": "Lowers score temporarily due to hard inquiries and reduced average account age; may signal risk to lenders"
    },
    "canonical": {
      "subject": "multiple credit cards",
      "predicate": "HAS_IMPACT_ON_CREDITWORTHINESS",
      "object": "Lowers score temporarily due to hard inquiries and reduced average account age; may signal risk to lenders"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "deep subprime borrowers",
      "predicate": "HAS_GOVERNMENT_PROGRAMS",
      "object": "FHA loans (3.5% down, 580+ score), VA loans (no minimum score), USDA loans, and nonprofit credit counseling (e.g., NFCC)"
    },
    "canonical": {
      "subject": "deep subprime borrowers",
      "predicate": "HAS_GOVERNMENT_PROGRAMS",
      "object": "FHA loans (3.5% down, 580+ score), VA loans (no minimum score), USDA loans, and nonprofit credit counseling (e.g., NFCC)"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "bankruptcy",
      "predicate": "HAS_IMPACT_ON_LENDER_ACCESS",
      "object": "Severely limits access for 7\u201310 years (Chapter 7) or 3\u20135 years (Chapter 13); deep subprime lenders may still approve but at high rates"
    },
    "canonical": {
      "subject": "bankruptcy",
      "predicate": "HAS_IMPACT_ON_LENDER_ACCESS",
      "object": "Severely limits access for 7\u201310 years (Chapter 7) or 3\u20135 years (Chapter 13); deep subprime lenders may still approve but at high rates"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "GPT",
    "original": {
      "subject": "credit scores",
      "predicate": "HAS_FICO_VS_BUREAU_SCORES_DIFFERENCE",
      "object": "FICO is a proprietary model used by lenders; Equifax/TransUnion produce their own scores (e.g., VantageScore) but FICO is the industry standard"
    },
    "canonical": {
      "subject": "credit scores",
      "predicate": "HAS_FICO_VS_BUREAU_SCORES_DIFFERENCE",
      "object": "FICO is a proprietary model used by lenders; Equifax/TransUnion produce their own scores (e.g., VantageScore) but FICO is the industry standard"
    },
    "match_confidence": "LOW"
  }
]

[Mistral] canonicalized 30 triples:
[
  {
    "model": "Mistral",
    "original": {
      "subject": "580",
      "predicate": "HAS_RISK_TIER",
      "object": "subprime"
    },
    "canonical": {
      "subject": "580",
      "predicate": "RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL",
      "object": "subprime"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "700",
      "predicate": "HAS_INTEREST_RATE",
      "object": "8.31%"
    },
    "canonical": {
      "subject": "700",
      "predicate": "INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE",
      "object": "8.31%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "500",
      "predicate": "HAS_APPROVAL_ODDS",
      "object": "29%"
    },
    "canonical": {
      "subject": "500",
      "predicate": "APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD",
      "object": "29%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "620",
      "predicate": "HAS_MAXIMUM_DEBT_TO_INCOME_RATIO",
      "object": "42%"
    },
    "canonical": {
      "subject": "620",
      "predicate": "MAX_DTI_PERMITTED_AS_MONTHLY_DEBT_BURDEN_CEILING",
      "object": "42%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "740",
      "predicate": "HAS_LOAN_TERM",
      "object": "60 to 84 months"
    },
    "canonical": {
      "subject": "740",
      "predicate": "LOAN_TERM_GRANTED_AS_MAXIMUM_REPAYMENT_WINDOW_OFFERED",
      "object": "60 to 84 months"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "500",
      "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
      "object": "15.4%"
    },
    "canonical": {
      "subject": "500",
      "predicate": "DOWN_PAYMENT_REQUIRED_AS_UPFRONT_BORROWER_CASH_CONTRIBUTION",
      "object": "15.4%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "660",
      "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
      "object": "2.63x"
    },
    "canonical": {
      "subject": "660",
      "predicate": "CREDIT_LIMIT_MULTIPLIER_APPLIED_AS_INCOME_BASED_BORROWING_CEILING_FACTOR",
      "object": "2.63x"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "400",
      "predicate": "HAS_DEFAULT_PROBABILITY",
      "object": "28.7%"
    },
    "canonical": {
      "subject": "400",
      "predicate": "DEFAULT_PROBABILITY_RECORDED_AS_HISTORICAL_NONREPAYMENT_RATE",
      "object": "28.7%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "580",
      "predicate": "HAS_LENDER_POOL",
      "object": "subprime banks"
    },
    "canonical": {
      "subject": "580",
      "predicate": "LENDER_POOL_ACCESSIBLE_AS_AVAILABLE_INSTITUTION_CATEGORY_FOR_THIS_SCORE",
      "object": "subprime banks"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "619 to 620",
      "predicate": "HAS_RISK_TIER_TRANSITION",
      "object": "from subprime to near prime"
    },
    "canonical": {
      "subject": "619 to 620",
      "predicate": "TIER_PROGRESSION_UPGRADES_INTO_NEXT_RISK_CLASSIFICATION_BAND",
      "object": "from subprime to near prime"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "850",
      "predicate": "HAS_APPROVAL_ODDS",
      "object": "99%"
    },
    "canonical": {
      "subject": "850",
      "predicate": "APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD",
      "object": "99%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "740",
      "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
      "object": "4.3%"
    },
    "canonical": {
      "subject": "740",
      "predicate": "DOWN_PAYMENT_REQUIRED_AS_UPFRONT_BORROWER_CASH_CONTRIBUTION",
      "object": "4.3%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "580",
      "predicate": "HAS_DEFAULT_PROBABILITY",
      "object": "11.3%"
    },
    "canonical": {
      "subject": "580",
      "predicate": "DEFAULT_PROBABILITY_RECORDED_AS_HISTORICAL_NONREPAYMENT_RATE",
      "object": "11.3%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "300",
      "predicate": "HAS_RISK_CLASSIFICATION",
      "object": "deep subprime (highest-risk borrower)"
    },
    "canonical": {
      "subject": "300",
      "predicate": "RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL",
      "object": "deep subprime (highest-risk borrower)"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "350",
      "predicate": "HAS_LENDER_POOL",
      "object": "specialty finance companies"
    },
    "canonical": {
      "subject": "350",
      "predicate": "LENDER_POOL_ACCESSIBLE_AS_AVAILABLE_INSTITUTION_CATEGORY_FOR_THIS_SCORE",
      "object": "specialty finance companies"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "800",
      "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
      "object": "5.13x"
    },
    "canonical": {
      "subject": "800",
      "predicate": "CREDIT_LIMIT_MULTIPLIER_APPLIED_AS_INCOME_BASED_BORROWING_CEILING_FACTOR",
      "object": "5.13x"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "850",
      "predicate": "HAS_MAXIMUM_DEBT_TO_INCOME_RATIO",
      "object": "52%"
    },
    "canonical": {
      "subject": "850",
      "predicate": "MAX_DTI_PERMITTED_AS_MONTHLY_DEBT_BURDEN_CEILING",
      "object": "52%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "660",
      "predicate": "HAS_INTEREST_RATE",
      "object": "9.49%"
    },
    "canonical": {
      "subject": "660",
      "predicate": "INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE",
      "object": "9.49%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "800",
      "predicate": "HAS_LOAN_TERM",
      "object": "84 months"
    },
    "canonical": {
      "subject": "800",
      "predicate": "LOAN_TERM_GRANTED_AS_MAXIMUM_REPAYMENT_WINDOW_OFFERED",
      "object": "84 months"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "580 to 660",
      "predicate": "HAS_RISK_TIER_UPGRADE_COUNT",
      "object": "2 (subprime \u2192 near prime \u2192 prime)"
    },
    "canonical": {
      "subject": "580 to 660",
      "predicate": "TIER_PROGRESSION_UPGRADES_INTO_NEXT_RISK_CLASSIFICATION_BAND",
      "object": "2 (subprime \u2192 near prime \u2192 prime)"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "mortgage",
      "predicate": "HAS_IDEAL_CREDIT_SCORE",
      "object": "620 or higher (near prime or above); 740+ is considered excellent for the best rates"
    },
    "canonical": {
      "subject": "mortgage",
      "predicate": "HAS_IDEAL_CREDIT_SCORE",
      "object": "620 or higher (near prime or above); 740+ is considered excellent for the best rates"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "credit score improvement",
      "predicate": "HAS_TIME_FROM_SUBPRIME_TO_PRIME",
      "object": "12 to 24 months (depends on individual actions like paying bills on time, reducing debt, and avoiding new credit applications)"
    },
    "canonical": {
      "subject": "credit score improvement",
      "predicate": "HAS_TIME_FROM_SUBPRIME_TO_PRIME",
      "object": "12 to 24 months (depends on individual actions like paying bills on time, reducing debt, and avoiding new credit applications)"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "credit bureaus",
      "predicate": "HAS_MOST_COMMONLY_USED_SCORE",
      "object": "FICO score (used by ~90% of lenders); Equifax, Experian, and TransUnion provide the underlying data"
    },
    "canonical": {
      "subject": "credit bureaus",
      "predicate": "HAS_MOST_COMMONLY_USED_SCORE",
      "object": "FICO score (used by ~90% of lenders); Equifax, Experian, and TransUnion provide the underlying data"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "missed payment",
      "predicate": "HAS_IMPACT_ON_CREDIT_SCORE",
      "object": "Can drop score by 50\u2013100+ points; impact lessens over time (typically 7 years) but remains on credit report"
    },
    "canonical": {
      "subject": "missed payment",
      "predicate": "HAS_IMPACT_ON_CREDIT_SCORE",
      "object": "Can drop score by 50\u2013100+ points; impact lessens over time (typically 7 years) but remains on credit report"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "U.S. adults",
      "predicate": "HAS_AVERAGE_CREDIT_SCORE",
      "object": "715 (as of 2023, per Experian)"
    },
    "canonical": {
      "subject": "U.S. adults",
      "predicate": "HAS_AVERAGE_CREDIT_SCORE",
      "object": "715 (as of 2023, per Experian)"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "interest rate negotiation",
      "predicate": "HAS_POSSIBILITY",
      "object": "Possible but limited; lenders may adjust rates for strong borrowers (e.g., super prime) or with collateral. Deep subprime borrowers have little leverage."
    },
    "canonical": {
      "subject": "interest rate negotiation",
      "predicate": "HAS_POSSIBILITY",
      "object": "Possible but limited; lenders may adjust rates for strong borrowers (e.g., super prime) or with collateral. Deep subprime borrowers have little leverage."
    },
    "match_confidence": "LOW"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "multiple credit cards",
      "predicate": "HAS_IMPACT_ON_CREDITWORTHINESS",
      "object": "Lowers score temporarily due to hard inquiries and reduced average account age; may signal risk to lenders"
    },
    "canonical": {
      "subject": "multiple credit cards",
      "predicate": "HAS_IMPACT_ON_CREDITWORTHINESS",
      "object": "Lowers score temporarily due to hard inquiries and reduced average account age; may signal risk to lenders"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "deep subprime borrowers",
      "predicate": "HAS_GOVERNMENT_PROGRAMS",
      "object": "FHA loans (3.5% down, 580+ score), VA loans (no minimum score), USDA loans, and nonprofit credit counseling (e.g., NFCC)"
    },
    "canonical": {
      "subject": "deep subprime borrowers",
      "predicate": "HAS_GOVERNMENT_PROGRAMS",
      "object": "FHA loans (3.5% down, 580+ score), VA loans (no minimum score), USDA loans, and nonprofit credit counseling (e.g., NFCC)"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "bankruptcy",
      "predicate": "HAS_IMPACT_ON_LENDER_ACCESS",
      "object": "Severely limits access for 7\u201310 years (Chapter 7) or 3\u20135 years (Chapter 13); deep subprime lenders may still approve but at high rates"
    },
    "canonical": {
      "subject": "bankruptcy",
      "predicate": "HAS_IMPACT_ON_LENDER_ACCESS",
      "object": "Severely limits access for 7\u201310 years (Chapter 7) or 3\u20135 years (Chapter 13); deep subprime lenders may still approve but at high rates"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "Mistral",
    "original": {
      "subject": "credit scores",
      "predicate": "HAS_FICO_VS_BUREAU_SCORES_DIFFERENCE",
      "object": "FICO is a proprietary model used by lenders; Equifax/TransUnion produce their own scores (e.g., VantageScore) but FICO is the industry standard"
    },
    "canonical": {
      "subject": "credit scores",
      "predicate": "HAS_FICO_VS_BUREAU_SCORES_DIFFERENCE",
      "object": "FICO is a proprietary model used by lenders; Equifax/TransUnion produce their own scores (e.g., VantageScore) but FICO is the industry standard"
    },
    "match_confidence": "LOW"
  }
]
[LLAMA] invocation failed: Error code: 400 - {'error': {'message': "tool call validation failed: parameters for tool CanonicalizedOutput did not match schema: errors: [`/triples/0`: missing properties: 'subject', 'predicate', 'object', `/triples/1`: missing properties: 'subject', 'predicate', 'object', `/triples/2`: missing properties: 'subject', 'predicate', 'object', `/triples/3`: missing properties: 'subject', 'predicate', 'object', `/triples/4`: missing properties: 'subject', 'predicate', 'object', `/triples/5`: missing properties: 'subject', 'predicate', 'object', `/triples/6`: missing properties: 'subject', 'predicate', 'object', `/triples/7`: missing properties: 'subject', 'predicate', 'object', `/triples/8`: missing properties: 'subject', 'predicate', 'object', `/triples/9`: missing properties: 'subject', 'predicate', 'object', `/triples/10`: missing properties: 'subject', 'predicate', 'object', `/triples/11`: missing properties: 'subject', 'predicate', 'object', `/triples/12`: missing properties: 'subject', 'predicate', 'object', `/triples/13`: missing properties: 'subject', 'predicate', 'object', `/triples/14`: missing properties: 'subject', 'predicate', 'object', `/triples/15`: missing properties: 'subject', 'predicate', 'object', `/triples/16`: missing properties: 'subject', 'predicate', 'object', `/triples/17`: missing properties: 'subject', 'predicate', 'object', `/triples/18`: missing properties: 'subject', 'predicate', 'object', `/triples/19`: missing properties: 'subject', 'predicate', 'object', `/triples/20`: missing properties: 'subject', 'predicate', 'object', `/triples/21`: missing properties: 'subject', 'predicate', 'object', `/triples/22`: missing properties: 'subject', 'predicate', 'object', `/triples/23`: missing properties: 'subject', 'predicate', 'object', `/triples/24`: missing properties: 'subject', 'predicate', 'object', `/triples/25`: missing properties: 'subject', 'predicate', 'object', `/triples/26`: missing properties: 'subject', 'predicate', 'object', `/triples/27`: missing properties: 'subject', 'predicate', 'object', `/triples/28`: missing properties: 'subject', 'predicate', 'object', `/triples/29`: missing properties: 'subject', 'predicate', 'object']", 'type': 'invalid_request_error', 'code': 'tool_use_failed', 'failed_generation': '<function=CanonicalizedOutput>{"triples": [{"original": {"subject": "580", "predicate": "HAS_RISK_TIER", "object": "subprime"}, "canonical": {"subject": "580", "predicate": "RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL", "object": "subprime"}, "match_confidence": "HIGH", "reasoning": "Exact match found for HAS_RISK_TIER in relationship types."}, {"original": {"subject": "700", "predicate": "HAS_INTEREST_RATE", "object": "8.31%"}, "canonical": {"subject": "700", "predicate": "INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE", "object": "8.31%"}, "match_confidence": "HIGH", "reasoning": "Exact match found for HAS_INTEREST_RATE in relationship types."}, {"original": {"subject": "500", "predicate": "HAS_APPROVAL_ODDS", "object": "29%"}, "canonical": {"subject": "500", "predicate": "APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD", "object": "29%"}, "match_confidence": "HIGH", "reasoning": "Exact match found for HAS_APPROVAL_ODDS in relationship types."}, {"original": {"subject": "620", "predicate": "HAS_MAXIMUM_DEBT_TO_INCOME_RATIO", "object": "42%"}, "canonical": {"subject": "620", "predicate": "MAX_DTI_PERMITTED_AS_MONTHLY_DEBT_BURDEN_CEILING", "object": "42%"}, "match_confidence": "HIGH", "reasoning": "Exact match found for HAS_MAXIMUM_DEBT_TO_INCOME_RATIO in relationship types."}, {"original": {"subject": "740", "predicate": "HAS_LOAN_TERM", "object": "60 to 84 months"}, "canonical": {"subject": "740", "predicate": "LOAN_TERM_GRANTED_AS_MAXIMUM_REPAYMENT_WINDOW_OFFERED", "object": "60 to 84 months"}, "match_confidence": "HIGH", "reasoning": "Exact match found for HAS_LOAN_TERM in relationship types."}, {"original": {"subject": "500", "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE", "object": "15.4%"}, "canonical": {"subject": "500", "predicate": "DOWN_PAYMENT_REQUIRED_AS_UPFRONT_BORROWER_CASH_CONTRIBUTION", "object": "15.4%"}, "match_confidence": "HIGH", "reasoning": "Exact match found for HAS_DOWN_PAYMENT_PERCENTAGE in relationship types."}, {"original": {"subject": "660", "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER", "object": "2.63x"}, "canonical": {"subject": "660", "predicate": "CREDIT_LIMIT_MULTIPLIER_APPLIED_AS_INCOME_BASED_BORROWING_CEILING_FACTOR", "object": "2.63x"}, "match_confidence": "HIGH", "reasoning": "Exact match found for HAS_CREDIT_LIMIT_MULTIPLIER in relationship types."}, {"original": {"subject": "400", "predicate": "HAS_DEFAULT_PROBABILITY", "object": "28.7%"}, "canonical": {"subject": "400", "predicate": "DEFAULT_PROBABILITY_RECORDED_AS_HISTORICAL_NONREPAYMENT_RATE", "object": "28.7%"}, "match_confidence": "HIGH", "reasoning": "Exact match found for HAS_DEFAULT_PROBABILITY in relationship types."}, {"original": {"subject": "580", "predicate": "HAS_LENDER_POOL", "object": "subprime banks"}, "canonical": {"subject": "580", "predicate": "LENDER_POOL_ACCESSIBLE_AS_AVAILABLE_INSTITUTION_CATEGORY_FOR_THIS_SCORE", "object": "subprime banks"}, "match_confidence": "HIGH", "reasoning": "Exact match found for HAS_LENDER_POOL in relationship types."}, {"original": {"subject": "619 to 620", "predicate": "HAS_RISK_TIER_TRANSITION", "object": "from subprime to near prime"}, "canonical": {"subject": "619 to 620", "predicate": "TIER_PROGRESSION_UPGRADES_INTO_NEXT_RISK_CLASSIFICATION_BAND", "object": "from subprime to near prime"}, "match_confidence": "HIGH", "reasoning": "Exact match found for HAS_RISK_TIER_TRANSITION in relationship types."}, {"original": {"subject": "850", "predicate": "HAS_APPROVAL_ODDS", "object": "99%"}, "canonical": {"subject": "850", "predicate": "APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD", "object": "99%"}, "match_confidence": "HIGH", "reasoning": "Exact match found for HAS_APPROVAL_ODDS in relationship types."}, {"original": {"subject": "740", "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE", "object": "4.3%"}, "canonical": {"subject": "740", "predicate": "DOWN_PAYMENT_REQUIRED_AS_UPFRONT_BORROWER_CASH_CONTRIBUTION", "object": "4.3%"}, "match_confidence": "HIGH", "reasoning": "Exact match found for HAS_DOWN_PAYMENT_PERCENTAGE in relationship types."}, {"original": {"subject": "580", "predicate": "HAS_DEFAULT_PROBABILITY", "object": "11.3%"}, "canonical": {"subject": "580", "predicate": "DEFAULT_PROBABILITY_RECORDED_AS_HISTORICAL_NONREPAYMENT_RATE", "object": "11.3%"}, "match_confidence": "HIGH", "reasoning": "Exact match found for HAS_DEFAULT_PROBABILITY in relationship types."}, {"original": {"subject": "300", "predicate": "HAS_RISK_CLASSIFICATION", "object": "deep subprime (highest-risk borrower)"}, "canonical": {"subject": "300", "predicate": "RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL", "object": "deep subprime (highest-risk borrower)"}, "match_confidence": "HIGH", "reasoning": "Exact match found for HAS_RISK_CLASSIFICATION in relationship types."}, {"original": {"subject": "350", "predicate": "HAS_LENDER_POOL", "object": "specialty finance companies"}, "canonical": {"subject": "350", "predicate": "LENDER_POOL_ACCESSIBLE_AS_AVAILABLE_INSTITUTION_CATEGORY_FOR_THIS_SCORE", "object": "specialty finance companies"}, "match_confidence": "HIGH", "reasoning": "Exact match found for HAS_LENDER_POOL in relationship types."}, {"original": {"subject": "800", "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER", "object": "5.13x"}, "canonical": {"subject": "800", "predicate": "CREDIT_LIMIT_MULTIPLIER_APPLIED_AS_INCOME_BASED_BORROWING_CEILING_FACTOR", "object": "5.13x"}, "match_confidence": "HIGH", "reasoning": "Exact match found for HAS_CREDIT_LIMIT_MULTIPLIER in relationship types."}, {"original": {"subject": "850", "predicate": "HAS_MAXIMUM_DEBT_TO_INCOME_RATIO", "object": "52%"}, "canonical": {"subject": "850", "predicate": "MAX_DTI_PERMITTED_AS_MONTHLY_DEBT_BURDEN_CEILING", "object": "52%"}, "match_confidence": "HIGH", "reasoning": "Exact match found for HAS_MAXIMUM_DEBT_TO_INCOME_RATIO in relationship types."}, {"original": {"subject": "660", "predicate": "HAS_INTEREST_RATE", "object": "9.49%"}, "canonical": {"subject": "660", "predicate": "INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE", "object": "9.49%"}, "match_confidence": "HIGH", "reasoning": "Exact match found for HAS_INTEREST_RATE in relationship types."}, {"original": {"subject": "800", "predicate": "HAS_LOAN_TERM", "object": "84 months"}, "canonical": {"subject": "800", "predicate": "LOAN_TERM_GRANTED_AS_MAXIMUM_REPAYMENT_WINDOW_OFFERED", "object": "84 months"}, "match_confidence": "HIGH", "reasoning": "Exact match found for HAS_LOAN_TERM in relationship types."}, {"original": {"subject": "580 to 660", "predicate": "HAS_RISK_TIER_UPGRADE_COUNT", "object": "2 (subprime → near prime → prime)"}, "canonical": {"subject": "580 to 660", "predicate": "TIER_PROGRESSION_UPGRADES_INTO_NEXT_RISK_CLASSIFICATION_BAND", "object": "2 (subprime → near prime → prime)"}, "match_confidence": "HIGH", "reasoning": "Exact match found for HAS_RISK_TIER_UPGRADE_COUNT in relationship types."}, {"original": {"subject": "mortgage", "predicate": "HAS_IDEAL_CREDIT_SCORE", "object": "620 or higher (near prime or above); 740+ is considered excellent for the best rates"}, "canonical": {"subject": "mortgage", "predicate": "HAS_IDEAL_CREDIT_SCORE", "object": "620 or higher (near prime or above); 740+ is considered excellent for the best rates"}, "match_confidence": "LOW", "reasoning": "No match found for HAS_IDEAL_CREDIT_SCORE in relationship types."}, {"original": {"subject": "credit score improvement", "predicate": "HAS_TIME_FROM_SUBPRIME_TO_PRIME", "object": "12 to 24 months (depends on individual actions like paying bills on time, reducing debt, and avoiding new credit applications)"}, "canonical": {"subject": "credit score improvement", "predicate": "HAS_TIME_FROM_SUBPRIME_TO_PRIME", "object": "12 to 24 months (depends on individual actions like paying bills on time, reducing debt, and avoiding new credit applications)"}, "match_confidence": "LOW", "reasoning": "No match found for HAS_TIME_FROM_SUBPRIME_TO_PRIME in relationship types."}, {"original": {"subject": "credit bureaus", "predicate": "HAS_MOST_COMMONLY_USED_SCORE", "object": "FICO score (used by ~90% of lenders); Equifax, Experian, and TransUnion provide the underlying data"}, "canonical": {"subject": "credit bureaus", "predicate": "HAS_MOST_COMMONLY_USED_SCORE", "object": "FICO score (used by ~90% of lenders); Equifax, Experian, and TransUnion provide the underlying data"}, "match_confidence": "LOW", "reasoning": "No match found for HAS_MOST_COMMONLY_USED_SCORE in relationship types."}, {"original": {"subject": "missed payment", "predicate": "HAS_IMPACT_ON_CREDIT_SCORE", "object": "Can drop score by 50–100+ points; impact lessens over time (typically 7 years) but remains on credit report"}, "canonical": {"subject": "missed payment", "predicate": "HAS_IMPACT_ON_CREDIT_SCORE", "object": "Can drop score by 50–100+ points; impact lessens over time (typically 7 years) but remains on credit report"}, "match_confidence": "LOW", "reasoning": "No match found for HAS_IMPACT_ON_CREDIT_SCORE in relationship types."}, {"original": {"subject": "U.S. adults", "predicate": "HAS_AVERAGE_CREDIT_SCORE", "object": "715 (as of 2023, per Experian)"}, "canonical": {"subject": "U.S. adults", "predicate": "HAS_AVERAGE_CREDIT_SCORE", "object": "715 (as of 2023, per Experian)"}, "match_confidence": "LOW", "reasoning": "No match found for HAS_AVERAGE_CREDIT_SCORE in relationship types."}, {"original": {"subject": "interest rate negotiation", "predicate": "HAS_POSSIBILITY", "object": "Possible but limited; lenders may adjust rates for strong borrowers (e.g., super prime) or with collateral. Deep subprime borrowers have little leverage."}, "canonical": {"subject": "interest rate negotiation", "predicate": "HAS_POSSIBILITY", "object": "Possible but limited; lenders may adjust rates for strong borrowers (e.g., super prime) or with collateral. Deep subprime borrowers have little leverage."}, "match_confidence": "LOW", "reasoning": "No match found for HAS_POSSIBILITY in relationship types."}, {"original": {"subject": "multiple credit cards", "predicate": "HAS_IMPACT_ON_CREDITWORTHINESS", "object": "Lowers score temporarily due to hard inquiries and reduced average account age; may signal risk to lenders"}, "canonical": {"subject": "multiple credit cards", "predicate": "HAS_IMPACT_ON_CREDITWORTHINESS", "object": "Lowers score temporarily due to hard inquiries and reduced average account age; may signal risk to lenders"}, "match_confidence": "LOW", "reasoning": "No match found for HAS_IMPACT_ON_CREDITWORTHINESS in relationship types."}, {"original": {"subject": "deep subprime borrowers", "predicate": "HAS_GOVERNMENT_PROGRAMS", "object": "FHA loans (3.5% down, 580+ score), VA loans (no minimum score), USDA loans, and nonprofit credit counseling (e.g., NFCC)"}, "canonical": {"subject": "deep subprime borrowers", "predicate": "HAS_GOVERNMENT_PROGRAMS", "object": "FHA loans (3.5% down, 580+ score), VA loans (no minimum score), USDA loans, and nonprofit credit counseling (e.g., NFCC)"}, "match_confidence": "LOW", "reasoning": "No match found for HAS_GOVERNMENT_PROGRAMS in relationship types."}, {"original": {"subject": "bankruptcy", "predicate": "HAS_IMPACT_ON_LENDER_ACCESS", "object": "Severely limits access for 7–10 years (Chapter 7) or 3–5 years (Chapter 13); deep subprime lenders may still approve but at high rates"}, "canonical": {"subject": "bankruptcy", "predicate": "HAS_IMPACT_ON_LENDER_ACCESS", "object": "Severely limits access for 7–10 years (Chapter 7) or 3–5 years (Chapter 13); deep subprime lenders may still approve but at high rates"}, "match_confidence": "LOW", "reasoning": "No match found for HAS_IMPACT_ON_LENDER_ACCESS in relationship types."}, {"original": {"subject": "credit scores", "predicate": "HAS_FICO_VS_BUREAU_SCORES_DIFFERENCE", "object": "FICO is a proprietary model used by lenders; Equifax/TransUnion produce their own scores (e.g., VantageScore) but FICO is the industry standard"}, "canonical": {"subject": "credit scores", "predicate": "HAS_FICO_VS_BUREAU_SCORES_DIFFERENCE", "object": "FICO is a proprietary model used by lenders; Equifax/TransUnion produce their own scores (e.g., VantageScore) but FICO is the industry standard"}, "match_confidence": "LOW", "reasoning": "No match found for HAS_FICO_VS_BUREAU_SCORES_DIFFERENCE in relationship types."}]}</function>'}}

[Gemini] canonicalized 30 triples:
[
  {
    "model": "Gemini",
    "original": {
      "subject": "580",
      "predicate": "HAS_RISK_TIER",
      "object": "subprime"
    },
    "canonical": {
      "subject": "580",
      "predicate": "RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL",
      "object": "subprime"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "700",
      "predicate": "HAS_INTEREST_RATE",
      "object": "8.31%"
    },
    "canonical": {
      "subject": "700",
      "predicate": "INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE",
      "object": "8.31%"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "500",
      "predicate": "HAS_APPROVAL_ODDS",
      "object": "29%"
    },
    "canonical": {
      "subject": "500",
      "predicate": "APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD",
      "object": "29%"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "620",
      "predicate": "HAS_MAXIMUM_DEBT_TO_INCOME_RATIO",
      "object": "42%"
    },
    "canonical": {
      "subject": "620",
      "predicate": "MAX_DTI_PERMITTED_AS_MONTHLY_DEBT_BURDEN_CEILING",
      "object": "42%"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "740",
      "predicate": "HAS_LOAN_TERM",
      "object": "60 to 84 months"
    },
    "canonical": {
      "subject": "740",
      "predicate": "LOAN_TERM_GRANTED_AS_MAXIMUM_REPAYMENT_WINDOW_OFFERED",
      "object": "60 to 84 months"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "500",
      "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
      "object": "15.4%"
    },
    "canonical": {
      "subject": "500",
      "predicate": "DOWN_PAYMENT_REQUIRED_AS_UPFRONT_BORROWER_CASH_CONTRIBUTION",
      "object": "15.4%"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "660",
      "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
      "object": "2.63x"
    },
    "canonical": {
      "subject": "660",
      "predicate": "CREDIT_LIMIT_MULTIPLIER_APPLIED_AS_INCOME_BASED_BORROWING_CEILING_FACTOR",
      "object": "2.63x"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "400",
      "predicate": "HAS_DEFAULT_PROBABILITY",
      "object": "28.7%"
    },
    "canonical": {
      "subject": "400",
      "predicate": "DEFAULT_PROBABILITY_RECORDED_AS_HISTORICAL_NONREPAYMENT_RATE",
      "object": "28.7%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "580",
      "predicate": "HAS_LENDER_POOL",
      "object": "subprime banks"
    },
    "canonical": {
      "subject": "580",
      "predicate": "LENDER_POOL_ACCESSIBLE_AS_AVAILABLE_INSTITUTION_CATEGORY_FOR_THIS_SCORE",
      "object": "subprime banks"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "619 to 620",
      "predicate": "HAS_RISK_TIER_TRANSITION",
      "object": "from subprime to near prime"
    },
    "canonical": {
      "subject": "619 to 620",
      "predicate": "TIER_PROGRESSION_UPGRADES_INTO_NEXT_RISK_CLASSIFICATION_BAND",
      "object": "from subprime to near prime"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "850",
      "predicate": "HAS_APPROVAL_ODDS",
      "object": "99%"
    },
    "canonical": {
      "subject": "850",
      "predicate": "APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD",
      "object": "99%"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "740",
      "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
      "object": "4.3%"
    },
    "canonical": {
      "subject": "740",
      "predicate": "DOWN_PAYMENT_REQUIRED_AS_UPFRONT_BORROWER_CASH_CONTRIBUTION",
      "object": "4.3%"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "580",
      "predicate": "HAS_DEFAULT_PROBABILITY",
      "object": "11.3%"
    },
    "canonical": {
      "subject": "580",
      "predicate": "DEFAULT_PROBABILITY_RECORDED_AS_HISTORICAL_NONREPAYMENT_RATE",
      "object": "11.3%"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "300",
      "predicate": "HAS_RISK_CLASSIFICATION",
      "object": "deep subprime (highest-risk borrower)"
    },
    "canonical": {
      "subject": "300",
      "predicate": "RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL",
      "object": "deep subprime (highest-risk borrower)"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "350",
      "predicate": "HAS_LENDER_POOL",
      "object": "specialty finance companies"
    },
    "canonical": {
      "subject": "350",
      "predicate": "LENDER_POOL_ACCESSIBLE_AS_AVAILABLE_INSTITUTION_CATEGORY_FOR_THIS_SCORE",
      "object": "specialty finance companies"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "800",
      "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
      "object": "5.13x"
    },
    "canonical": {
      "subject": "800",
      "predicate": "CREDIT_LIMIT_MULTIPLIER_APPLIED_AS_INCOME_BASED_BORROWING_CEILING_FACTOR",
      "object": "5.13x"
    },
    "match_confidence": "HIGH"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "850",
      "predicate": "HAS_MAXIMUM_DEBT_TO_INCOME_RATIO",
      "object": "52%"
    },
    "canonical": {
      "subject": "850",
      "predicate": "MAX_DTI_PERMITTED_AS_MONTHLY_DEBT_BURDEN_CEILING",
      "object": "52%"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "660",
      "predicate": "HAS_INTEREST_RATE",
      "object": "9.49%"
    },
    "canonical": {
      "subject": "660",
      "predicate": "INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE",
      "object": "9.49%"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "800",
      "predicate": "HAS_LOAN_TERM",
      "object": "84 months"
    },
    "canonical": {
      "subject": "800",
      "predicate": "LOAN_TERM_GRANTED_AS_MAXIMUM_REPAYMENT_WINDOW_OFFERED",
      "object": "84 months"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "580 to 660",
      "predicate": "HAS_RISK_TIER_UPGRADE_COUNT",
      "object": "2 (subprime \u2192 near prime \u2192 prime)"
    },
    "canonical": {
      "subject": "580 to 660",
      "predicate": "TIER_PROGRESSION_UPGRADES_INTO_NEXT_RISK_CLASSIFICATION_BAND",
      "object": "2 (subprime \t near prime \t prime)"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "mortgage",
      "predicate": "HAS_IDEAL_CREDIT_SCORE",
      "object": "620 or higher (near prime or above); 740+ is considered excellent for the best rates"
    },
    "canonical": {
      "subject": "mortgage",
      "predicate": "HAS_IDEAL_CREDIT_SCORE",
      "object": "620 or higher (near prime or above); 740+ is considered excellent for the best rates"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "credit score improvement",
      "predicate": "HAS_TIME_FROM_SUBPRIME_TO_PRIME",
      "object": "12 to 24 months (depends on individual actions like paying bills on time, reducing debt, and avoiding new credit applications)"
    },
    "canonical": {
      "subject": "credit score improvement",
      "predicate": "HAS_TIME_FROM_SUBPRIME_TO_PRIME",
      "object": "12 to 24 months (depends on individual actions like paying bills on time, reducing debt, and avoiding new credit applications)"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "credit bureaus",
      "predicate": "HAS_MOST_COMMONLY_USED_SCORE",
      "object": "FICO score (used by ~90% of lenders); Equifax, Experian, and TransUnion provide the underlying data"
    },
    "canonical": {
      "subject": "credit bureaus",
      "predicate": "HAS_MOST_COMMONLY_USED_SCORE",
      "object": "FICO score (used by ~90% of lenders); Equifax, Experian, and TransUnion provide the underlying data"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "missed payment",
      "predicate": "HAS_IMPACT_ON_CREDIT_SCORE",
      "object": "Can drop score by 50\u2013100+ points; impact lessens over time (typically 7 years) but remains on credit report"
    },
    "canonical": {
      "subject": "missed payment",
      "predicate": "HAS_IMPACT_ON_CREDIT_SCORE",
      "object": "Can drop score by 50\t100+ points; impact lessens over time (typically 7 years) but remains on credit report"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "U.S. adults",
      "predicate": "HAS_AVERAGE_CREDIT_SCORE",
      "object": "715 (as of 2023, per Experian)"
    },
    "canonical": {
      "subject": "U.S. adults",
      "predicate": "HAS_AVERAGE_CREDIT_SCORE",
      "object": "715 (as of 2023, per Experian)"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "interest rate negotiation",
      "predicate": "HAS_POSSIBILITY",
      "object": "Possible but limited; lenders may adjust rates for strong borrowers (e.g., super prime) or with collateral. Deep subprime borrowers have little leverage."
    },
    "canonical": {
      "subject": "interest rate negotiation",
      "predicate": "HAS_POSSIBILITY",
      "object": "Possible but limited; lenders may adjust rates for strong borrowers (e.g., super prime) or with collateral. Deep subprime borrowers have little leverage."
    },
    "match_confidence": "LOW"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "multiple credit cards",
      "predicate": "HAS_IMPACT_ON_CREDITWORTHINESS",
      "object": "Lowers score temporarily due to hard inquiries and reduced average account age; may signal risk to lenders"
    },
    "canonical": {
      "subject": "multiple credit cards",
      "predicate": "HAS_IMPACT_ON_CREDITWORTHINESS",
      "object": "Lowers score temporarily due to hard inquiries and reduced average account age; may signal risk to lenders"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "deep subprime borrowers",
      "predicate": "HAS_GOVERNMENT_PROGRAMS",
      "object": "FHA loans (3.5% down, 580+ score), VA loans (no minimum score), USDA loans, and nonprofit credit counseling (e.g., NFCC)"
    },
    "canonical": {
      "subject": "deep subprime borrowers",
      "predicate": "HAS_GOVERNMENT_PROGRAMS",
      "object": "FHA loans (3.5% down, 580+ score), VA loans (no minimum score), USDA loans, and nonprofit credit counseling (e.g., NFCC)"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "bankruptcy",
      "predicate": "HAS_IMPACT_ON_LENDER_ACCESS",
      "object": "Severely limits access for 7\u201310 years (Chapter 7) or 3\u20135 years (Chapter 13); deep subprime lenders may still approve but at high rates"
    },
    "canonical": {
      "subject": "bankruptcy",
      "predicate": "HAS_IMPACT_ON_LENDER_ACCESS",
      "object": "Severely limits access for 7\t10 years (Chapter 7) or 3\t5 years (Chapter 13); deep subprime lenders may still approve but at high rates"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "Gemini",
    "original": {
      "subject": "credit scores",
      "predicate": "HAS_FICO_VS_BUREAU_SCORES_DIFFERENCE",
      "object": "FICO is a proprietary model used by lenders; Equifax/TransUnion produce their own scores (e.g., VantageScore) but FICO is the industry standard"
    },
    "canonical": {
      "subject": "credit scores",
      "predicate": "HAS_FICO_VS_BUREAU_SCORES_DIFFERENCE",
      "object": "FICO is a proprietary model used by lenders; Equifax/TransUnion produce their own scores (e.g., VantageScore) but FICO is the industry standard"
    },
    "match_confidence": "LOW"
  }
]

[GLM] canonicalized 30 triples:
[
  {
    "model": "GLM",
    "original": {
      "subject": "580",
      "predicate": "HAS_RISK_TIER",
      "object": "subprime"
    },
    "canonical": {
      "subject": "580",
      "predicate": "RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL",
      "object": "subprime"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "700",
      "predicate": "HAS_INTEREST_RATE",
      "object": "8.31%"
    },
    "canonical": {
      "subject": "700",
      "predicate": "INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE",
      "object": "8.31%"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "500",
      "predicate": "HAS_APPROVAL_ODDS",
      "object": "29%"
    },
    "canonical": {
      "subject": "500",
      "predicate": "APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD",
      "object": "29%"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "620",
      "predicate": "HAS_MAXIMUM_DEBT_TO_INCOME_RATIO",
      "object": "42%"
    },
    "canonical": {
      "subject": "620",
      "predicate": "MAX_DTI_PERMITTED_AS_MONTHLY_DEBT_BURDEN_CEILING",
      "object": "42%"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "740",
      "predicate": "HAS_LOAN_TERM",
      "object": "60 to 84 months"
    },
    "canonical": {
      "subject": "740",
      "predicate": "LOAN_TERM_GRANTED_AS_MAXIMUM_REPAYMENT_WINDOW_OFFERED",
      "object": "60 to 84 months"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "500",
      "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
      "object": "15.4%"
    },
    "canonical": {
      "subject": "500",
      "predicate": "DOWN_PAYMENT_REQUIRED_AS_UPFRONT_BORROWER_CASH_CONTRIBUTION",
      "object": "15.4%"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "660",
      "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
      "object": "2.63x"
    },
    "canonical": {
      "subject": "660",
      "predicate": "CREDIT_LIMIT_MULTIPLIER_APPLIED_AS_INCOME_BASED_BORROWING_CEILING_FACTOR",
      "object": "2.63x"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "400",
      "predicate": "HAS_DEFAULT_PROBABILITY",
      "object": "28.7%"
    },
    "canonical": {
      "subject": "400",
      "predicate": "DEFAULT_PROBABILITY_RECORDED_AS_HISTORICAL_NONREPAYMENT_RATE",
      "object": "28.7%"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "580",
      "predicate": "HAS_LENDER_POOL",
      "object": "subprime banks"
    },
    "canonical": {
      "subject": "580",
      "predicate": "LENDER_POOL_ACCESSIBLE_AS_AVAILABLE_INSTITUTION_CATEGORY_FOR_THIS_SCORE",
      "object": "subprime banks"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "619 to 620",
      "predicate": "HAS_RISK_TIER_TRANSITION",
      "object": "from subprime to near prime"
    },
    "canonical": {
      "subject": "619 to 620",
      "predicate": "TIER_PROGRESSION_UPGRADES_INTO_NEXT_RISK_CLASSIFICATION_BAND",
      "object": "from subprime to near prime"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "850",
      "predicate": "HAS_APPROVAL_ODDS",
      "object": "99%"
    },
    "canonical": {
      "subject": "850",
      "predicate": "APPROVAL_ODDS_ESTIMATED_AS_LENDER_ACCEPTANCE_LIKELIHOOD",
      "object": "99%"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "740",
      "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
      "object": "4.3%"
    },
    "canonical": {
      "subject": "740",
      "predicate": "DOWN_PAYMENT_REQUIRED_AS_UPFRONT_BORROWER_CASH_CONTRIBUTION",
      "object": "4.3%"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "580",
      "predicate": "HAS_DEFAULT_PROBABILITY",
      "object": "11.3%"
    },
    "canonical": {
      "subject": "580",
      "predicate": "DEFAULT_PROBABILITY_RECORDED_AS_HISTORICAL_NONREPAYMENT_RATE",
      "object": "11.3%"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "300",
      "predicate": "HAS_RISK_CLASSIFICATION",
      "object": "deep subprime (highest-risk borrower)"
    },
    "canonical": {
      "subject": "300",
      "predicate": "RISK_TIER_CLASSIFIED_AS_BORROWER_DANGER_LEVEL",
      "object": "deep subprime (highest-risk borrower)"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "350",
      "predicate": "HAS_LENDER_POOL",
      "object": "specialty finance companies"
    },
    "canonical": {
      "subject": "350",
      "predicate": "LENDER_POOL_ACCESSIBLE_AS_AVAILABLE_INSTITUTION_CATEGORY_FOR_THIS_SCORE",
      "object": "specialty finance companies"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "800",
      "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
      "object": "5.13x"
    },
    "canonical": {
      "subject": "800",
      "predicate": "CREDIT_LIMIT_MULTIPLIER_APPLIED_AS_INCOME_BASED_BORROWING_CEILING_FACTOR",
      "object": "5.13x"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "850",
      "predicate": "HAS_MAXIMUM_DEBT_TO_INCOME_RATIO",
      "object": "52%"
    },
    "canonical": {
      "subject": "850",
      "predicate": "MAX_DTI_PERMITTED_AS_MONTHLY_DEBT_BURDEN_CEILING",
      "object": "52%"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "660",
      "predicate": "HAS_INTEREST_RATE",
      "object": "9.49%"
    },
    "canonical": {
      "subject": "660",
      "predicate": "INTEREST_RATE_CHARGED_AS_ANNUAL_BORROWING_COST_PERCENTAGE",
      "object": "9.49%"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "800",
      "predicate": "HAS_LOAN_TERM",
      "object": "84 months"
    },
    "canonical": {
      "subject": "800",
      "predicate": "LOAN_TERM_GRANTED_AS_MAXIMUM_REPAYMENT_WINDOW_OFFERED",
      "object": "84 months"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "580 to 660",
      "predicate": "HAS_RISK_TIER_UPGRADE_COUNT",
      "object": "2 (subprime \u2192 near prime \u2192 prime)"
    },
    "canonical": {
      "subject": "580 to 660",
      "predicate": "TIER_PROGRESSION_UPGRADES_INTO_NEXT_RISK_CLASSIFICATION_BAND",
      "object": "2 (subprime \u2192 near prime \u2192 prime)"
    },
    "match_confidence": "MEDIUM"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "mortgage",
      "predicate": "HAS_IDEAL_CREDIT_SCORE",
      "object": "620 or higher (near prime or above); 740+ is considered excellent for the best rates"
    },
    "canonical": {
      "subject": "mortgage",
      "predicate": "HAS_IDEAL_CREDIT_SCORE",
      "object": "620 or higher (near prime or above); 740+ is considered excellent for the best rates"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "credit score improvement",
      "predicate": "HAS_TIME_FROM_SUBPRIME_TO_PRIME",
      "object": "12 to 24 months (depends on individual actions like paying bills on time, reducing debt, and avoiding new credit applications)"
    },
    "canonical": {
      "subject": "credit score improvement",
      "predicate": "HAS_TIME_FROM_SUBPRIME_TO_PRIME",
      "object": "12 to 24 months (depends on individual actions like paying bills on time, reducing debt, and avoiding new credit applications)"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "credit bureaus",
      "predicate": "HAS_MOST_COMMONLY_USED_SCORE",
      "object": "FICO score (used by ~90% of lenders); Equifax, Experian, and TransUnion provide the underlying data"
    },
    "canonical": {
      "subject": "credit bureaus",
      "predicate": "HAS_MOST_COMMONLY_USED_SCORE",
      "object": "FICO score (used by ~90% of lenders); Equifax, Experian, and TransUnion provide the underlying data"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "missed payment",
      "predicate": "HAS_IMPACT_ON_CREDIT_SCORE",
      "object": "Can drop score by 50\u2013100+ points; impact lessens over time (typically 7 years) but remains on credit report"
    },
    "canonical": {
      "subject": "missed payment",
      "predicate": "HAS_IMPACT_ON_CREDIT_SCORE",
      "object": "Can drop score by 50\u2013100+ points; impact lessens over time (typically 7 years) but remains on credit report"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "U.S. adults",
      "predicate": "HAS_AVERAGE_CREDIT_SCORE",
      "object": "715 (as of 2023, per Experian)"
    },
    "canonical": {
      "subject": "U.S. adults",
      "predicate": "HAS_AVERAGE_CREDIT_SCORE",
      "object": "715 (as of 2023, per Experian)"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "interest rate negotiation",
      "predicate": "HAS_POSSIBILITY",
      "object": "Possible but limited; lenders may adjust rates for strong borrowers (e.g., super prime) or with collateral. Deep subprime borrowers have little leverage."
    },
    "canonical": {
      "subject": "interest rate negotiation",
      "predicate": "HAS_POSSIBILITY",
      "object": "Possible but limited; lenders may adjust rates for strong borrowers (e.g., super prime) or with collateral. Deep subprime borrowers have little leverage."
    },
    "match_confidence": "LOW"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "multiple credit cards",
      "predicate": "HAS_IMPACT_ON_CREDITWORTHINESS",
      "object": "Lowers score temporarily due to hard inquiries and reduced average account age; may signal risk to lenders"
    },
    "canonical": {
      "subject": "multiple credit cards",
      "predicate": "HAS_IMPACT_ON_CREDITWORTHINESS",
      "object": "Lowers score temporarily due to hard inquiries and reduced average account age; may signal risk to lenders"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "deep subprime borrowers",
      "predicate": "HAS_GOVERNMENT_PROGRAMS",
      "object": "FHA loans (3.5% down, 580+ score), VA loans (no minimum score), USDA loans, and nonprofit credit counseling (e.g., NFCC)"
    },
    "canonical": {
      "subject": "deep subprime borrowers",
      "predicate": "HAS_GOVERNMENT_PROGRAMS",
      "object": "FHA loans (3.5% down, 580+ score), VA loans (no minimum score), USDA loans, and nonprofit credit counseling (e.g., NFCC)"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "bankruptcy",
      "predicate": "HAS_IMPACT_ON_LENDER_ACCESS",
      "object": "Severely limits access for 7\u201310 years (Chapter 7) or 3\u20135 years (Chapter 13); deep subprime lenders may still approve but at high rates"
    },
    "canonical": {
      "subject": "bankruptcy",
      "predicate": "HAS_IMPACT_ON_LENDER_ACCESS",
      "object": "Severely limits access for 7\u201310 years (Chapter 7) or 3\u20135 years (Chapter 13); deep subprime lenders may still approve but at high rates"
    },
    "match_confidence": "LOW"
  },
  {
    "model": "GLM",
    "original": {
      "subject": "credit scores",
      "predicate": "HAS_FICO_VS_BUREAU_SCORES_DIFFERENCE",
      "object": "FICO is a proprietary model used by lenders; Equifax/TransUnion produce their own scores (e.g., VantageScore) but FICO is the industry standard"
    },
    "canonical": {
      "subject": "credit scores",
      "predicate": "HAS_FICO_VS_BUREAU_SCORES_DIFFERENCE",
      "object": "FICO is a proprietary model used by lenders; Equifax/TransUnion produce their own scores (e.g., VantageScore) but FICO is the industry standard"
    },
    "match_confidence": "LOW"
  }
]

[canonicalize_triples] total canonicalized across all models: 120
