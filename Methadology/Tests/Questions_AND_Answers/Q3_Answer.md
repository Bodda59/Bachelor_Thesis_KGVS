
============================================================
  Running step: extract_triples
============================================================
Here are the answers in the requested structured format:

### Down Payments:
```json
{"Subject":"300","Predicate":"down payment","Object":"22.1%"}
{"Subject":"400","Predicate":"down payment","Object":"19.4%"}
{"Subject":"350","Predicate":"down payment","Object":"Not provided in the dataset"}
{"Subject":"500","Predicate":"down payment","Object":"15.4%"}
{"Subject":"800","Predicate":"down payment","Object":"2.8%"}
{"Subject":"633","Predicate":"down payment","Object":"Not explicitly provided (falls in near prime tier, likely between 10.6% and 9.58%)"}
{"Subject":"600","Predicate":"down payment","Object":"Not provided in the dataset"}
{"Subject":"700","Predicate":"down payment","Object":"6.3%"}
{"Subject":"650","Predicate":"down payment","Object":"Not provided in the dataset (falls in near prime tier, likely close to 9.58%)"}
```

### Risk Tiers:
```json
{"Subject":"300","Predicate":"risk tier","Object":"deep subprime"}
{"Subject":"580","Predicate":"risk tier","Object":"subprime"}
{"Subject":"579","Predicate":"risk tier","Object":"deep subprime"}
{"Subject":"620","Predicate":"risk tier","Object":"near prime"}
{"Subject":"740","Predicate":"risk tier","Object":"super prime"}
{"Subject":"633","Predicate":"risk tier","Object":"near prime"}
```

Extracted triples GPT (JSON):
[
  {
    "subject": "300",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "22.1%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage down payment associated with the subject."
  },
  {
    "subject": "400",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "19.4%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage down payment associated with the subject."
  },
  {
    "subject": "350",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not provided in the dataset",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage down payment associated with the subject."
  },
  {
    "subject": "500",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "15.4%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage down payment associated with the subject."
  },
  {
    "subject": "800",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "2.8%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage down payment associated with the subject."
  },
  {
    "subject": "633",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not explicitly provided (falls in near prime tier, likely between 10.6% and 9.58%)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage down payment associated with the subject."
  },
  {
    "subject": "600",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not provided in the dataset",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage down payment associated with the subject."
  },
  {
    "subject": "700",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "6.3%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage down payment associated with the subject."
  },
  {
    "subject": "650",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not provided in the dataset (falls in near prime tier, likely close to 9.58%)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage down payment associated with the subject."
  },
  {
    "subject": "300",
    "predicate": "HAS_RISK_TIER",
    "object": "deep subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the risk tier classification associated with the subject."
  },
  {
    "subject": "580",
    "predicate": "HAS_RISK_TIER",
    "object": "subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the risk tier classification associated with the subject."
  },
  {
    "subject": "579",
    "predicate": "HAS_RISK_TIER",
    "object": "deep subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the risk tier classification associated with the subject."
  },
  {
    "subject": "620",
    "predicate": "HAS_RISK_TIER",
    "object": "near prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the risk tier classification associated with the subject."
  },
  {
    "subject": "740",
    "predicate": "HAS_RISK_TIER",
    "object": "super prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the risk tier classification associated with the subject."
  },
  {
    "subject": "633",
    "predicate": "HAS_RISK_TIER",
    "object": "near prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the risk tier classification associated with the subject."
  }
]

Extracted triples Mistral (JSON):
[
  {
    "subject": "300",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "22.1%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price required as a down payment for a credit score of 300."
  },
  {
    "subject": "400",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "19.4%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price required as a down payment for a credit score of 400."
  },
  {
    "subject": "350",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "Not provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that the down payment percentage for a credit score of 350 is not explicitly mentioned in the dataset."
  },
  {
    "subject": "500",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "15.4%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price required as a down payment for a credit score of 500."
  },
  {
    "subject": "800",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "2.8%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price required as a down payment for a credit score of 800."
  },
  {
    "subject": "633",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "10.1% (estimated)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Estimates the down payment percentage for a credit score of 633, likely between 10.6% and 9.58% based on near prime tier values."
  },
  {
    "subject": "600",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "Not provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that the down payment percentage for a credit score of 600 is not explicitly mentioned in the dataset."
  },
  {
    "subject": "700",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "6.3%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price required as a down payment for a credit score of 700."
  },
  {
    "subject": "650",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "9.58% (estimated)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Estimates the down payment percentage for a credit score of 650, likely close to the near prime tier value."
  },
  {
    "subject": "300",
    "predicate": "HAS_RISK_TIER",
    "object": "Deep Subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Classifies a credit score of 300 into the deep subprime risk tier."
  },
  {
    "subject": "580",
    "predicate": "HAS_RISK_TIER",
    "object": "Subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Classifies a credit score of 580 into the subprime risk tier."
  },
  {
    "subject": "579",
    "predicate": "HAS_RISK_TIER",
    "object": "Deep Subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Classifies a credit score of 579 into the deep subprime risk tier."
  },
  {
    "subject": "620",
    "predicate": "HAS_RISK_TIER",
    "object": "Near Prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Classifies a credit score of 620 into the near prime risk tier."
  },
  {
    "subject": "740",
    "predicate": "HAS_RISK_TIER",
    "object": "Super Prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Classifies a credit score of 740 into the super prime risk tier."
  },
  {
    "subject": "633",
    "predicate": "HAS_RISK_TIER",
    "object": "Near Prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Classifies a credit score of 633 into the near prime risk tier."
  },
  {
    "subject": "Deep Subprime",
    "predicate": "HAS_DOWN_PAYMENT_RANGE",
    "object": "19.4% - 22.1%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the range of down payment percentages associated with the deep subprime risk tier."
  },
  {
    "subject": "Subprime",
    "predicate": "HAS_DOWN_PAYMENT_RANGE",
    "object": "15.4% (estimated)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Estimates the down payment percentage associated with the subprime risk tier."
  },
  {
    "subject": "Near Prime",
    "predicate": "HAS_DOWN_PAYMENT_RANGE",
    "object": "9.58% - 10.6% (estimated)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Estimates the range of down payment percentages associated with the near prime risk tier."
  },
  {
    "subject": "Super Prime",
    "predicate": "HAS_DOWN_PAYMENT_RANGE",
    "object": "2.8% - 6.3%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the range of down payment percentages associated with the super prime risk tier."
  }
]

Extracted triples LLAMA (JSON):
[
  {
    "subject": "300",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "22.1%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The down payment percentage associated with a specific credit score."
  },
  {
    "subject": "400",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "19.4%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The down payment percentage associated with a specific credit score."
  },
  {
    "subject": "350",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The down payment percentage associated with a specific credit score."
  },
  {
    "subject": "500",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "15.4%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The down payment percentage associated with a specific credit score."
  },
  {
    "subject": "800",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "2.8%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The down payment percentage associated with a specific credit score."
  },
  {
    "subject": "633",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "between 10.6% and 9.58%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The down payment percentage associated with a specific credit score."
  },
  {
    "subject": "600",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The down payment percentage associated with a specific credit score."
  },
  {
    "subject": "700",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "6.3%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The down payment percentage associated with a specific credit score."
  },
  {
    "subject": "650",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "close to 9.58%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The down payment percentage associated with a specific credit score."
  },
  {
    "subject": "300",
    "predicate": "HAS_RISK_TIER",
    "object": "deep subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The risk tier associated with a specific credit score."
  },
  {
    "subject": "580",
    "predicate": "HAS_RISK_TIER",
    "object": "subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The risk tier associated with a specific credit score."
  },
  {
    "subject": "579",
    "predicate": "HAS_RISK_TIER",
    "object": "deep subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The risk tier associated with a specific credit score."
  },
  {
    "subject": "620",
    "predicate": "HAS_RISK_TIER",
    "object": "near prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The risk tier associated with a specific credit score."
  },
  {
    "subject": "740",
    "predicate": "HAS_RISK_TIER",
    "object": "super prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The risk tier associated with a specific credit score."
  },
  {
    "subject": "633",
    "predicate": "HAS_RISK_TIER",
    "object": "near prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The risk tier associated with a specific credit score."
  }
]

Extracted triples GLM (JSON):
[
  {
    "subject": "300",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "22.1%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the purchase price paid upfront associated with a specific credit score."
  },
  {
    "subject": "400",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "19.4%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the purchase price paid upfront associated with a specific credit score."
  },
  {
    "subject": "350",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "Not provided in the dataset",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the purchase price paid upfront associated with a specific credit score."
  },
  {
    "subject": "500",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "15.4%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the purchase price paid upfront associated with a specific credit score."
  },
  {
    "subject": "800",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "2.8%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the purchase price paid upfront associated with a specific credit score."
  },
  {
    "subject": "633",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "Not explicitly provided (falls in near prime tier, likely between 10.6% and 9.58%)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the purchase price paid upfront associated with a specific credit score."
  },
  {
    "subject": "600",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "Not provided in the dataset",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the purchase price paid upfront associated with a specific credit score."
  },
  {
    "subject": "700",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "6.3%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the purchase price paid upfront associated with a specific credit score."
  },
  {
    "subject": "650",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "Not provided in the dataset (falls in near prime tier, likely close to 9.58%)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the purchase price paid upfront associated with a specific credit score."
  },
  {
    "subject": "300",
    "predicate": "HAS_RISK_TIER",
    "object": "deep subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the credit risk classification assigned to a specific credit score."
  },
  {
    "subject": "580",
    "predicate": "HAS_RISK_TIER",
    "object": "subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the credit risk classification assigned to a specific credit score."
  },
  {
    "subject": "579",
    "predicate": "HAS_RISK_TIER",
    "object": "deep subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the credit risk classification assigned to a specific credit score."
  },
  {
    "subject": "620",
    "predicate": "HAS_RISK_TIER",
    "object": "near prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the credit risk classification assigned to a specific credit score."
  },
  {
    "subject": "740",
    "predicate": "HAS_RISK_TIER",
    "object": "super prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the credit risk classification assigned to a specific credit score."
  },
  {
    "subject": "633",
    "predicate": "HAS_RISK_TIER",
    "object": "near prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the credit risk classification assigned to a specific credit score."
  }
]

Extracted triples Gemini (JSON):
[
  {
    "subject": "300",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "22.1%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price paid upfront."
  },
  {
    "subject": "400",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "19.4%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price paid upfront."
  },
  {
    "subject": "350",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not provided in the dataset",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price paid upfront."
  },
  {
    "subject": "500",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "15.4%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price paid upfront."
  },
  {
    "subject": "800",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "2.8%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price paid upfront."
  },
  {
    "subject": "633",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not explicitly provided (falls in near prime tier, likely between 10.6% and 9.58%)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price paid upfront."
  },
  {
    "subject": "600",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not provided in the dataset",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price paid upfront."
  },
  {
    "subject": "700",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "6.3%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price paid upfront."
  },
  {
    "subject": "650",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not provided in the dataset (falls in near prime tier, likely close to 9.58%)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price paid upfront."
  },
  {
    "subject": "300",
    "predicate": "BELONGS_TO_RISK_TIER",
    "object": "deep subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_RELATION",
    "predicate_definition": "Indicates the risk category to which a subject belongs."
  },
  {
    "subject": "580",
    "predicate": "BELONGS_TO_RISK_TIER",
    "object": "subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_RELATION",
    "predicate_definition": "Indicates the risk category to which a subject belongs."
  },
  {
    "subject": "579",
    "predicate": "BELONGS_TO_RISK_TIER",
    "object": "deep subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_RELATION",
    "predicate_definition": "Indicates the risk category to which a subject belongs."
  },
  {
    "subject": "620",
    "predicate": "BELONGS_TO_RISK_TIER",
    "object": "near prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_RELATION",
    "predicate_definition": "Indicates the risk category to which a subject belongs."
  },
  {
    "subject": "740",
    "predicate": "BELONGS_TO_RISK_TIER",
    "object": "super prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_RELATION",
    "predicate_definition": "Indicates the risk category to which a subject belongs."
  },
  {
    "subject": "633",
    "predicate": "BELONGS_TO_RISK_TIER",
    "object": "near prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_RELATION",
    "predicate_definition": "Indicates the risk category to which a subject belongs."
  }
]
