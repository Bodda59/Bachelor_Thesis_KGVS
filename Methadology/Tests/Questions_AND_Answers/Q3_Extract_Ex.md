
============================================================
  Running step: extract_triples
============================================================

Raw response from LLM: ```json
{"Subject":"300","Predicate":"has_down_payment","Object":"22.1%"}
{"Subject":"400","Predicate":"has_down_payment","Object":"19.4%"}
{"Subject":"350","Predicate":"has_down_payment","Object":"Not provided"}

{"Subject":"500","Predicate":"has_down_payment","Object":"15.4%"}
{"Subject":"800","Predicate":"has_down_payment","Object":"2.8%"}
{"Subject":"633","Predicate":"has_down_payment","Object":"10.6%"}

{"Subject":"600","Predicate":"has_down_payment","Object":"Not provided"}
{"Subject":"700","Predicate":"has_down_payment","Object":"6.3%"}
{"Subject":"650","Predicate":"has_down_payment","Object":"Not provided"}

{"Subject":"300","Predicate":"has_risk_tier","Object":"deep subprime"}
{"Subject":"580","Predicate":"has_risk_tier","Object":"subprime"}
{"Subject":"579","Predicate":"has_risk_tier","Object":"deep subprime"}

{"Subject":"620","Predicate":"has_risk_tier","Object":"near prime"}
{"Subject":"740","Predicate":"has_risk_tier","Object":"super prime"}
{"Subject":"633","Predicate":"has_risk_tier","Object":"near prime"}
```

Extracted triples GPT(JSON):
[
  {
    "subject": "300",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "22.1%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of down payment associated with the subject."
  },
  {
    "subject": "400",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "19.4%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of down payment associated with the subject."
  },
  {
    "subject": "350",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that the percentage of down payment associated with the subject is not specified."
  },
  {
    "subject": "500",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "15.4%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of down payment associated with the subject."
  },
  {
    "subject": "800",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "2.8%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of down payment associated with the subject."
  },
  {
    "subject": "633",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "10.6%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of down payment associated with the subject."
  },
  {
    "subject": "600",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that the percentage of down payment associated with the subject is not specified."
  },
  {
    "subject": "700",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "6.3%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of down payment associated with the subject."
  },
  {
    "subject": "650",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that the percentage of down payment associated with the subject is not specified."
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

Extracted triples Mistral(JSON):
[
  {
    "subject": "300",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "22.1%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price paid upfront for a loan or purchase associated with this credit score."
  },
  {
    "subject": "400",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "19.4%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price paid upfront for a loan or purchase associated with this credit score."
  },
  {
    "subject": "350",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that the down payment percentage for this credit score is not available or not disclosed."
  },
  {
    "subject": "500",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "15.4%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price paid upfront for a loan or purchase associated with this credit score."
  },
  {
    "subject": "800",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "2.8%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price paid upfront for a loan or purchase associated with this credit score."
  },
  {
    "subject": "633",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "10.6%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price paid upfront for a loan or purchase associated with this credit score."
  },
  {
    "subject": "600",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that the down payment percentage for this credit score is not available or not disclosed."
  },
  {
    "subject": "700",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "6.3%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price paid upfront for a loan or purchase associated with this credit score."
  },
  {
    "subject": "650",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that the down payment percentage for this credit score is not available or not disclosed."
  },
  {
    "subject": "300",
    "predicate": "HAS_RISK_TIER",
    "object": "deep subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Classifies the credit score into a risk category based on lending risk assessments."
  },
  {
    "subject": "580",
    "predicate": "HAS_RISK_TIER",
    "object": "subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Classifies the credit score into a risk category based on lending risk assessments."
  },
  {
    "subject": "579",
    "predicate": "HAS_RISK_TIER",
    "object": "deep subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Classifies the credit score into a risk category based on lending risk assessments."
  },
  {
    "subject": "620",
    "predicate": "HAS_RISK_TIER",
    "object": "near prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Classifies the credit score into a risk category based on lending risk assessments."
  },
  {
    "subject": "740",
    "predicate": "HAS_RISK_TIER",
    "object": "super prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Classifies the credit score into a risk category based on lending risk assessments."
  },
  {
    "subject": "633",
    "predicate": "HAS_RISK_TIER",
    "object": "near prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Classifies the credit score into a risk category based on lending risk assessments."
  },
  {
    "subject": "300",
    "predicate": "IS_ASSOCIATED_WITH_HIGHER_DOWN_PAYMENT",
    "object": "True",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that a lower credit score is associated with a higher down payment percentage."
  },
  {
    "subject": "400",
    "predicate": "IS_ASSOCIATED_WITH_HIGHER_DOWN_PAYMENT",
    "object": "True",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that a lower credit score is associated with a higher down payment percentage."
  },
  {
    "subject": "500",
    "predicate": "IS_ASSOCIATED_WITH_HIGHER_DOWN_PAYMENT",
    "object": "True",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that a lower credit score is associated with a higher down payment percentage."
  },
  {
    "subject": "700",
    "predicate": "IS_ASSOCIATED_WITH_LOWER_DOWN_PAYMENT",
    "object": "True",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that a higher credit score is associated with a lower down payment percentage."
  },
  {
    "subject": "800",
    "predicate": "IS_ASSOCIATED_WITH_LOWER_DOWN_PAYMENT",
    "object": "True",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that a higher credit score is associated with a lower down payment percentage."
  },
  {
    "subject": "633",
    "predicate": "IS_ASSOCIATED_WITH_MODERATE_DOWN_PAYMENT",
    "object": "True",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that a mid-range credit score is associated with a moderate down payment percentage."
  },
  {
    "subject": "deep subprime",
    "predicate": "HAS_HIGHER_LENDING_RISK",
    "object": "True",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that this risk tier is associated with a higher likelihood of default or lending risk."
  },
  {
    "subject": "subprime",
    "predicate": "HAS_HIGHER_LENDING_RISK",
    "object": "True",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that this risk tier is associated with a higher likelihood of default or lending risk."
  },
  {
    "subject": "near prime",
    "predicate": "HAS_MODERATE_LENDING_RISK",
    "object": "True",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that this risk tier is associated with a moderate likelihood of default or lending risk."
  },
  {
    "subject": "super prime",
    "predicate": "HAS_LOWEST_LENDING_RISK",
    "object": "True",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that this risk tier is associated with the lowest likelihood of default or lending risk."
  }
]

Extracted triples LLAMA(JSON):
[
  {
    "subject": "300",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "22.1%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The down payment percentage for a given credit score"
  },
  {
    "subject": "400",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "19.4%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The down payment percentage for a given credit score"
  },
  {
    "subject": "350",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The down payment percentage for a given credit score"
  },
  {
    "subject": "500",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "15.4%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The down payment percentage for a given credit score"
  },
  {
    "subject": "800",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "2.8%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The down payment percentage for a given credit score"
  },
  {
    "subject": "633",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "10.6%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The down payment percentage for a given credit score"
  },
  {
    "subject": "600",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The down payment percentage for a given credit score"
  },
  {
    "subject": "700",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "6.3%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The down payment percentage for a given credit score"
  },
  {
    "subject": "650",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The down payment percentage for a given credit score"
  },
  {
    "subject": "300",
    "predicate": "HAS_RISK_TIER",
    "object": "deep subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The risk tier associated with a given credit score"
  },
  {
    "subject": "580",
    "predicate": "HAS_RISK_TIER",
    "object": "subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The risk tier associated with a given credit score"
  },
  {
    "subject": "579",
    "predicate": "HAS_RISK_TIER",
    "object": "deep subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The risk tier associated with a given credit score"
  },
  {
    "subject": "620",
    "predicate": "HAS_RISK_TIER",
    "object": "near prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The risk tier associated with a given credit score"
  },
  {
    "subject": "740",
    "predicate": "HAS_RISK_TIER",
    "object": "super prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The risk tier associated with a given credit score"
  },
  {
    "subject": "633",
    "predicate": "HAS_RISK_TIER",
    "object": "near prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The risk tier associated with a given credit score"
  }
]

Extracted triples GLM(JSON):
[
  {
    "subject": "300",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "22.1%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The percentage of the total purchase price paid upfront associated with this credit score."
  },
  {
    "subject": "400",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "19.4%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The percentage of the total purchase price paid upfront associated with this credit score."
  },
  {
    "subject": "350",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The percentage of the total purchase price paid upfront associated with this credit score."
  },
  {
    "subject": "500",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "15.4%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The percentage of the total purchase price paid upfront associated with this credit score."
  },
  {
    "subject": "800",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "2.8%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The percentage of the total purchase price paid upfront associated with this credit score."
  },
  {
    "subject": "633",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "10.6%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The percentage of the total purchase price paid upfront associated with this credit score."
  },
  {
    "subject": "600",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The percentage of the total purchase price paid upfront associated with this credit score."
  },
  {
    "subject": "700",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "6.3%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The percentage of the total purchase price paid upfront associated with this credit score."
  },
  {
    "subject": "650",
    "predicate": "HAS_DOWN_PAYMENT",
    "object": "Not provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The percentage of the total purchase price paid upfront associated with this credit score."
  },
  {
    "subject": "300",
    "predicate": "HAS_RISK_TIER",
    "object": "deep subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The credit risk category assigned to a specific credit score."
  },
  {
    "subject": "580",
    "predicate": "HAS_RISK_TIER",
    "object": "subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The credit risk category assigned to a specific credit score."
  },
  {
    "subject": "579",
    "predicate": "HAS_RISK_TIER",
    "object": "deep subprime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The credit risk category assigned to a specific credit score."
  },
  {
    "subject": "620",
    "predicate": "HAS_RISK_TIER",
    "object": "near prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The credit risk category assigned to a specific credit score."
  },
  {
    "subject": "740",
    "predicate": "HAS_RISK_TIER",
    "object": "super prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The credit risk category assigned to a specific credit score."
  },
  {
    "subject": "633",
    "predicate": "HAS_RISK_TIER",
    "object": "near prime",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The credit risk category assigned to a specific credit score."
  }
]
