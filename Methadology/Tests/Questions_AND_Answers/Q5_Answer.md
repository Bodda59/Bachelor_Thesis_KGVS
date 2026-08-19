
============================================================
  Running step: extract_triples
============================================================
Here are the answers in the requested structured format:

### **Credit Limit Multiplier**
```json
{"Subject":"300","Predicate":"credit limit multiplier","Object":"0.31x"}
{"Subject":"400","Predicate":"credit limit multiplier","Object":"0.54x"}
{"Subject":"360","Predicate":"credit limit multiplier","Object":"Not explicitly provided in the dataset (assumed to follow the trend between 350 and 400, but no exact value given)"}

{"Subject":"500","Predicate":"credit limit multiplier","Object":"1.06x"}
{"Subject":"620","Predicate":"credit limit multiplier","Object":"2.07x"}
{"Subject":"580","Predicate":"credit limit multiplier","Object":"1.61x"}

{"Subject":"700","Predicate":"credit limit multiplier","Object":"3.19x"}
{"Subject":"800","Predicate":"credit limit multiplier","Object":"5.13x"}
{"Subject":"740","Predicate":"credit limit multiplier","Object":"3.99x"}
```

### **Max Debt-to-Income Ratio**
```json
{"Subject":"300","Predicate":"max debt-to-income ratio","Object":"28%"}
{"Subject":"350","Predicate":"max debt-to-income ratio","Object":"29%"}
{"Subject":"320","Predicate":"max debt-to-income ratio","Object":"Not explicitly provided in the dataset (assumed to follow the trend between 300 and 350, but no exact value given)"}

{"Subject":"400","Predicate":"max debt-to-income ratio","Object":"31%"}
{"Subject":"500","Predicate":"max debt-to-income ratio","Object":"35%"}
{"Subject":"450","Predicate":"max debt-to-income ratio","Object":"33%"}

{"Subject":"620","Predicate":"max debt-to-income ratio","Object":"42%"}
{"Subject":"660","Predicate":"max debt-to-income ratio","Object":"44%"}
{"Subject":"640","Predicate":"max debt-to-income ratio","Object":"Not explicitly provided in the dataset (assumed to follow the trend between 620 and 660, but no exact value given)"}
```
Gemini extractor failed: 503 UNAVAILABLE. {'error': {'code': 503, 'message': 'This model is currently experiencing high demand. Spikes in demand are usually temporary. Please try again later.', 'status': 'UNAVAILABLE'}}

Extracted triples GPT (JSON):
[
  {
    "subject": "300",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "0.31x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the multiplier used to calculate the credit limit for the given score."
  },
  {
    "subject": "400",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "0.54x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the multiplier used to calculate the credit limit for the given score."
  },
  {
    "subject": "360",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "Not explicitly provided in the dataset (assumed to follow the trend between 350 and 400, but no exact value given)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the multiplier used to calculate the credit limit for the given score."
  },
  {
    "subject": "500",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "1.06x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the multiplier used to calculate the credit limit for the given score."
  },
  {
    "subject": "620",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "2.07x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the multiplier used to calculate the credit limit for the given score."
  },
  {
    "subject": "580",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "1.61x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the multiplier used to calculate the credit limit for the given score."
  },
  {
    "subject": "700",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "3.19x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the multiplier used to calculate the credit limit for the given score."
  },
  {
    "subject": "800",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "5.13x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the multiplier used to calculate the credit limit for the given score."
  },
  {
    "subject": "740",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "3.99x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the multiplier used to calculate the credit limit for the given score."
  },
  {
    "subject": "300",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "28%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the maximum allowed debt-to-income ratio for the given score."
  },
  {
    "subject": "350",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "29%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the maximum allowed debt-to-income ratio for the given score."
  },
  {
    "subject": "320",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "Not explicitly provided in the dataset (assumed to follow the trend between 300 and 350, but no exact value given)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the maximum allowed debt-to-income ratio for the given score."
  },
  {
    "subject": "400",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "31%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the maximum allowed debt-to-income ratio for the given score."
  },
  {
    "subject": "500",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "35%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the maximum allowed debt-to-income ratio for the given score."
  },
  {
    "subject": "450",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "33%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the maximum allowed debt-to-income ratio for the given score."
  },
  {
    "subject": "620",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "42%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the maximum allowed debt-to-income ratio for the given score."
  },
  {
    "subject": "660",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "44%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the maximum allowed debt-to-income ratio for the given score."
  },
  {
    "subject": "640",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "Not explicitly provided in the dataset (assumed to follow the trend between 620 and 660, but no exact value given)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the maximum allowed debt-to-income ratio for the given score."
  }
]

Extracted triples Mistral (JSON):
[
  {
    "subject": "300",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "0.31x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the credit limit multiplier associated with a credit score of 300."
  },
  {
    "subject": "400",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "0.54x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the credit limit multiplier associated with a credit score of 400."
  },
  {
    "subject": "360",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "Not explicitly provided (estimated based on trend)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that the credit limit multiplier for a credit score of 360 is not explicitly provided but is estimated based on trends."
  },
  {
    "subject": "500",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "1.06x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the credit limit multiplier associated with a credit score of 500."
  },
  {
    "subject": "620",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "2.07x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the credit limit multiplier associated with a credit score of 620."
  },
  {
    "subject": "580",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "1.61x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the credit limit multiplier associated with a credit score of 580."
  },
  {
    "subject": "700",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "3.19x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the credit limit multiplier associated with a credit score of 700."
  },
  {
    "subject": "800",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "5.13x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the credit limit multiplier associated with a credit score of 800."
  },
  {
    "subject": "740",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "3.99x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the credit limit multiplier associated with a credit score of 740."
  },
  {
    "subject": "300",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "28%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the maximum debt-to-income ratio associated with a credit score of 300."
  },
  {
    "subject": "350",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "29%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the maximum debt-to-income ratio associated with a credit score of 350."
  },
  {
    "subject": "320",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "Not explicitly provided (estimated based on trend)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that the maximum debt-to-income ratio for a credit score of 320 is not explicitly provided but is estimated based on trends."
  },
  {
    "subject": "400",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "31%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the maximum debt-to-income ratio associated with a credit score of 400."
  },
  {
    "subject": "500",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "35%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the maximum debt-to-income ratio associated with a credit score of 500."
  },
  {
    "subject": "450",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "33%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the maximum debt-to-income ratio associated with a credit score of 450."
  },
  {
    "subject": "620",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "42%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the maximum debt-to-income ratio associated with a credit score of 620."
  },
  {
    "subject": "660",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "44%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the maximum debt-to-income ratio associated with a credit score of 660."
  },
  {
    "subject": "640",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "Not explicitly provided (estimated based on trend)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that the maximum debt-to-income ratio for a credit score of 640 is not explicitly provided but is estimated based on trends."
  }
]

Extracted triples LLAMA (JSON):
[
  {
    "subject": "300",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "0.31x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The credit limit multiplier for a given credit score."
  },
  {
    "subject": "400",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "0.54x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The credit limit multiplier for a given credit score."
  },
  {
    "subject": "360",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "Not explicitly provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The credit limit multiplier for a given credit score."
  },
  {
    "subject": "500",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "1.06x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The credit limit multiplier for a given credit score."
  },
  {
    "subject": "620",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "2.07x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The credit limit multiplier for a given credit score."
  },
  {
    "subject": "580",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "1.61x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The credit limit multiplier for a given credit score."
  },
  {
    "subject": "700",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "3.19x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The credit limit multiplier for a given credit score."
  },
  {
    "subject": "800",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "5.13x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The credit limit multiplier for a given credit score."
  },
  {
    "subject": "740",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "3.99x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The credit limit multiplier for a given credit score."
  },
  {
    "subject": "300",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "28%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The maximum debt-to-income ratio for a given credit score."
  },
  {
    "subject": "350",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "29%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The maximum debt-to-income ratio for a given credit score."
  },
  {
    "subject": "320",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "Not explicitly provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The maximum debt-to-income ratio for a given credit score."
  },
  {
    "subject": "400",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "31%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The maximum debt-to-income ratio for a given credit score."
  },
  {
    "subject": "500",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "35%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The maximum debt-to-income ratio for a given credit score."
  },
  {
    "subject": "450",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "33%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The maximum debt-to-income ratio for a given credit score."
  },
  {
    "subject": "620",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "42%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The maximum debt-to-income ratio for a given credit score."
  },
  {
    "subject": "660",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "44%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The maximum debt-to-income ratio for a given credit score."
  },
  {
    "subject": "640",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "Not explicitly provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The maximum debt-to-income ratio for a given credit score."
  }
]

Extracted triples GLM (JSON):
[
  {
    "subject": "300",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "0.31x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The factor by which a base amount is multiplied to determine the credit limit for this entity."
  },
  {
    "subject": "400",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "0.54x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The factor by which a base amount is multiplied to determine the credit limit for this entity."
  },
  {
    "subject": "360",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "Not explicitly provided in the dataset (assumed to follow the trend between 350 and 400, but no exact value given)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The factor by which a base amount is multiplied to determine the credit limit for this entity."
  },
  {
    "subject": "500",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "1.06x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The factor by which a base amount is multiplied to determine the credit limit for this entity."
  },
  {
    "subject": "620",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "2.07x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The factor by which a base amount is multiplied to determine the credit limit for this entity."
  },
  {
    "subject": "580",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "1.61x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The factor by which a base amount is multiplied to determine the credit limit for this entity."
  },
  {
    "subject": "700",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "3.19x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The factor by which a base amount is multiplied to determine the credit limit for this entity."
  },
  {
    "subject": "800",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "5.13x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The factor by which a base amount is multiplied to determine the credit limit for this entity."
  },
  {
    "subject": "740",
    "predicate": "HAS_CREDIT_LIMIT_MULTIPLIER",
    "object": "3.99x",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The factor by which a base amount is multiplied to determine the credit limit for this entity."
  },
  {
    "subject": "300",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "28%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The maximum percentage of gross monthly income that can go towards debt payments for this entity."
  },
  {
    "subject": "350",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "29%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The maximum percentage of gross monthly income that can go towards debt payments for this entity."
  },
  {
    "subject": "320",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "Not explicitly provided in the dataset (assumed to follow the trend between 300 and 350, but no exact value given)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The maximum percentage of gross monthly income that can go towards debt payments for this entity."
  },
  {
    "subject": "400",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "31%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The maximum percentage of gross monthly income that can go towards debt payments for this entity."
  },
  {
    "subject": "500",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "35%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The maximum percentage of gross monthly income that can go towards debt payments for this entity."
  },
  {
    "subject": "450",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "33%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The maximum percentage of gross monthly income that can go towards debt payments for this entity."
  },
  {
    "subject": "620",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "42%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The maximum percentage of gross monthly income that can go towards debt payments for this entity."
  },
  {
    "subject": "660",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "44%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The maximum percentage of gross monthly income that can go towards debt payments for this entity."
  },
  {
    "subject": "640",
    "predicate": "HAS_MAX_DEBT_TO_INCOME_RATIO",
    "object": "Not explicitly provided in the dataset (assumed to follow the trend between 620 and 660, but no exact value given)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The maximum percentage of gross monthly income that can go towards debt payments for this entity."
  }
]

Extracted triples Gemini (JSON):
[]
