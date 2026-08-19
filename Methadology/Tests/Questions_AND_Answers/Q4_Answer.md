
============================================================
  Running step: extract_triples
============================================================
Here are the answers in the requested structured format:

### Loan Terms
```json
{"Subject":"500","Predicate":"loan term","Object":"12 to 24"}
{"Subject":"580","Predicate":"loan term","Object":"36"}
{"Subject":"540","Predicate":"loan term","Object":"12 to 24"}

{"Subject":"620","Predicate":"loan term","Object":"36 to 48"}
{"Subject":"660","Predicate":"loan term","Object":"48 to 60"}
{"Subject":"640","Predicate":"loan term","Object":"36 to 48"}

{"Subject":"660","Predicate":"loan term","Object":"48 to 60"}
{"Subject":"700","Predicate":"loan term","Object":"60"}
{"Subject":"685","Predicate":"loan term","Object":"48 to 60"}

{"Subject":"740","Predicate":"loan term","Object":"60 to 84"}
{"Subject":"800","Predicate":"loan term","Object":"84"}
{"Subject":"753","Predicate":"loan term","Object":"60 to 84"}
```

### Default Probabilities
```json
{"Subject":"300","Predicate":"default probability","Object":"38.5%"}
{"Subject":"400","Predicate":"default probability","Object":"28.7%"}
{"Subject":"350","Predicate":"default probability","Object":"Not explicitly provided (falls between 38.5% and 28.7%)"}

{"Subject":"500","Predicate":"default probability","Object":"18.6%"}
{"Subject":"620","Predicate":"default probability","Object":"8.5%"}
{"Subject":"560","Predicate":"default probability","Object":"Not explicitly provided (falls between 18.6% and 11.3%)"}

{"Subject":"700","Predicate":"default probability","Object":"3.3%"}
{"Subject":"800","Predicate":"default probability","Object":"0.7%"}
{"Subject":"733","Predicate":"default probability","Object":"Not explicitly provided (falls between 3.3% and 1.8%)"}
```
Gemini extractor failed: 503 UNAVAILABLE. {'error': {'code': 503, 'message': 'This model is currently experiencing high demand. Spikes in demand are usually temporary. Please try again later.', 'status': 'UNAVAILABLE'}}

Extracted triples GPT (JSON):
[
  {
    "subject": "500",
    "predicate": "HAS_LOAN_TERM",
    "object": "12 to 24",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "This relationship indicates the range of months for loan terms associated with the subject entity."
  },
  {
    "subject": "580",
    "predicate": "HAS_LOAN_TERM",
    "object": "36",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "This relationship indicates the number of months for loan terms associated with the subject entity."
  },
  {
    "subject": "540",
    "predicate": "HAS_LOAN_TERM",
    "object": "12 to 24",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "This relationship indicates the range of months for loan terms associated with the subject entity."
  },
  {
    "subject": "620",
    "predicate": "HAS_LOAN_TERM",
    "object": "36 to 48",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "This relationship indicates the range of months for loan terms associated with the subject entity."
  },
  {
    "subject": "660",
    "predicate": "HAS_LOAN_TERM",
    "object": "48 to 60",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "This relationship indicates the range of months for loan terms associated with the subject entity."
  },
  {
    "subject": "640",
    "predicate": "HAS_LOAN_TERM",
    "object": "36 to 48",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "This relationship indicates the range of months for loan terms associated with the subject entity."
  },
  {
    "subject": "660",
    "predicate": "HAS_LOAN_TERM",
    "object": "48 to 60",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "This relationship indicates the range of months for loan terms associated with the subject entity."
  },
  {
    "subject": "700",
    "predicate": "HAS_LOAN_TERM",
    "object": "60",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "This relationship indicates the number of months for loan terms associated with the subject entity."
  },
  {
    "subject": "685",
    "predicate": "HAS_LOAN_TERM",
    "object": "48 to 60",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "This relationship indicates the range of months for loan terms associated with the subject entity."
  },
  {
    "subject": "740",
    "predicate": "HAS_LOAN_TERM",
    "object": "60 to 84",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "This relationship indicates the range of months for loan terms associated with the subject entity."
  },
  {
    "subject": "800",
    "predicate": "HAS_LOAN_TERM",
    "object": "84",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "This relationship indicates the number of months for loan terms associated with the subject entity."
  },
  {
    "subject": "753",
    "predicate": "HAS_LOAN_TERM",
    "object": "60 to 84",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "This relationship indicates the range of months for loan terms associated with the subject entity."
  },
  {
    "subject": "300",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "38.5%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "This relationship indicates the default probability value associated with the subject entity."
  },
  {
    "subject": "400",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "28.7%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "This relationship indicates the default probability value associated with the subject entity."
  },
  {
    "subject": "350",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "Not explicitly provided (falls between 38.5% and 28.7%)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "This relationship indicates an extrapolated default probability range for the subject entity based on adjacent values."
  },
  {
    "subject": "500",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "18.6%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "This relationship indicates the default probability value associated with the subject entity."
  },
  {
    "subject": "620",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "8.5%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "This relationship indicates the default probability value associated with the subject entity."
  },
  {
    "subject": "560",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "Not explicitly provided (falls between 18.6% and 11.3%)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "This relationship indicates an extrapolated default probability range for the subject entity based on adjacent values."
  },
  {
    "subject": "700",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "3.3%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "This relationship indicates the default probability value associated with the subject entity."
  },
  {
    "subject": "800",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "0.7%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "This relationship indicates the default probability value associated with the subject entity."
  },
  {
    "subject": "733",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "Not explicitly provided (falls between 3.3% and 1.8%)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "This relationship indicates an extrapolated default probability range for the subject entity based on adjacent values."
  }
]

Extracted triples Mistral (JSON):
[
  {
    "subject": "Credit Score of 500",
    "predicate": "HAS_LOAN_TERM_MONTHS",
    "object": "12 to 24",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the range of loan term lengths (in months) available for a borrower with this credit score."
  },
  {
    "subject": "Credit Score of 580",
    "predicate": "HAS_LOAN_TERM_MONTHS",
    "object": "36",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the loan term length (in months) available for a borrower with this credit score."
  },
  {
    "subject": "Credit Score of 540",
    "predicate": "HAS_LOAN_TERM_MONTHS",
    "object": "12 to 24",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the range of loan term lengths (in months) available for a borrower with this credit score."
  },
  {
    "subject": "Credit Score of 620",
    "predicate": "HAS_LOAN_TERM_MONTHS",
    "object": "36 to 48",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the range of loan term lengths (in months) available for a borrower with this credit score."
  },
  {
    "subject": "Credit Score of 660",
    "predicate": "HAS_LOAN_TERM_MONTHS",
    "object": "48 to 60",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the range of loan term lengths (in months) available for a borrower with this credit score."
  },
  {
    "subject": "Credit Score of 640",
    "predicate": "HAS_LOAN_TERM_MONTHS",
    "object": "36 to 48",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the range of loan term lengths (in months) available for a borrower with this credit score."
  },
  {
    "subject": "Credit Score of 700",
    "predicate": "HAS_LOAN_TERM_MONTHS",
    "object": "60",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the loan term length (in months) available for a borrower with this credit score."
  },
  {
    "subject": "Credit Score of 685",
    "predicate": "HAS_LOAN_TERM_MONTHS",
    "object": "48 to 60",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the range of loan term lengths (in months) available for a borrower with this credit score."
  },
  {
    "subject": "Credit Score of 740",
    "predicate": "HAS_LOAN_TERM_MONTHS",
    "object": "60 to 84",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the range of loan term lengths (in months) available for a borrower with this credit score."
  },
  {
    "subject": "Credit Score of 800",
    "predicate": "HAS_LOAN_TERM_MONTHS",
    "object": "84",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the loan term length (in months) available for a borrower with this credit score."
  },
  {
    "subject": "Credit Score of 753",
    "predicate": "HAS_LOAN_TERM_MONTHS",
    "object": "60 to 84",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the range of loan term lengths (in months) available for a borrower with this credit score."
  },
  {
    "subject": "Credit Score of 300",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "38.5%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the estimated probability of loan default for a borrower with this credit score."
  },
  {
    "subject": "Credit Score of 400",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "28.7%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the estimated probability of loan default for a borrower with this credit score."
  },
  {
    "subject": "Credit Score of 350",
    "predicate": "HAS_ESTIMATED_DEFAULT_PROBABILITY",
    "object": "33.6%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the estimated probability of loan default for a borrower with this credit score, derived from interpolation."
  },
  {
    "subject": "Credit Score of 500",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "18.6%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the estimated probability of loan default for a borrower with this credit score."
  },
  {
    "subject": "Credit Score of 620",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "8.5%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the estimated probability of loan default for a borrower with this credit score."
  },
  {
    "subject": "Credit Score of 560",
    "predicate": "HAS_ESTIMATED_DEFAULT_PROBABILITY",
    "object": "14.95%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the estimated probability of loan default for a borrower with this credit score, derived from interpolation."
  },
  {
    "subject": "Credit Score of 700",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "3.3%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the estimated probability of loan default for a borrower with this credit score."
  },
  {
    "subject": "Credit Score of 800",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "0.7%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the estimated probability of loan default for a borrower with this credit score."
  },
  {
    "subject": "Credit Score of 733",
    "predicate": "HAS_ESTIMATED_DEFAULT_PROBABILITY",
    "object": "2.55%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the estimated probability of loan default for a borrower with this credit score, derived from interpolation."
  }
]

Extracted triples LLAMA (JSON):
[
  {
    "subject": "500",
    "predicate": "HAS_LOAN_TERM",
    "object": "12 to 24",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The loan term available for a given credit score"
  },
  {
    "subject": "580",
    "predicate": "HAS_LOAN_TERM",
    "object": "36",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The loan term available for a given credit score"
  },
  {
    "subject": "540",
    "predicate": "HAS_LOAN_TERM",
    "object": "12 to 24",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The loan term available for a given credit score"
  },
  {
    "subject": "620",
    "predicate": "HAS_LOAN_TERM",
    "object": "36 to 48",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The loan term available for a given credit score"
  },
  {
    "subject": "660",
    "predicate": "HAS_LOAN_TERM",
    "object": "48 to 60",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The loan term available for a given credit score"
  },
  {
    "subject": "640",
    "predicate": "HAS_LOAN_TERM",
    "object": "36 to 48",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The loan term available for a given credit score"
  },
  {
    "subject": "660",
    "predicate": "HAS_LOAN_TERM",
    "object": "48 to 60",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The loan term available for a given credit score"
  },
  {
    "subject": "700",
    "predicate": "HAS_LOAN_TERM",
    "object": "60",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The loan term available for a given credit score"
  },
  {
    "subject": "685",
    "predicate": "HAS_LOAN_TERM",
    "object": "48 to 60",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The loan term available for a given credit score"
  },
  {
    "subject": "740",
    "predicate": "HAS_LOAN_TERM",
    "object": "60 to 84",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The loan term available for a given credit score"
  },
  {
    "subject": "800",
    "predicate": "HAS_LOAN_TERM",
    "object": "84",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The loan term available for a given credit score"
  },
  {
    "subject": "753",
    "predicate": "HAS_LOAN_TERM",
    "object": "60 to 84",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The loan term available for a given credit score"
  },
  {
    "subject": "300",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "38.5%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The probability of default for a given credit score"
  },
  {
    "subject": "400",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "28.7%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The probability of default for a given credit score"
  },
  {
    "subject": "350",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "Not explicitly provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The probability of default for a given credit score, which may be estimated or extrapolated"
  },
  {
    "subject": "500",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "18.6%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The probability of default for a given credit score"
  },
  {
    "subject": "620",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "8.5%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The probability of default for a given credit score"
  },
  {
    "subject": "560",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "Not explicitly provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The probability of default for a given credit score, which may be estimated or extrapolated"
  },
  {
    "subject": "700",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "3.3%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The probability of default for a given credit score"
  },
  {
    "subject": "800",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "0.7%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The probability of default for a given credit score"
  },
  {
    "subject": "733",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "Not explicitly provided",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The probability of default for a given credit score, which may be estimated or extrapolated"
  }
]

Extracted triples GLM (JSON):
[
  {
    "subject": "500",
    "predicate": "HAS_LOAN_TERM",
    "object": "12 to 24",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The duration or range of duration (in months) available for a loan based on the credit score."
  },
  {
    "subject": "580",
    "predicate": "HAS_LOAN_TERM",
    "object": "36",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The duration or range of duration (in months) available for a loan based on the credit score."
  },
  {
    "subject": "540",
    "predicate": "HAS_LOAN_TERM",
    "object": "12 to 24",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The duration or range of duration (in months) available for a loan based on the credit score."
  },
  {
    "subject": "620",
    "predicate": "HAS_LOAN_TERM",
    "object": "36 to 48",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The duration or range of duration (in months) available for a loan based on the credit score."
  },
  {
    "subject": "660",
    "predicate": "HAS_LOAN_TERM",
    "object": "48 to 60",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The duration or range of duration (in months) available for a loan based on the credit score."
  },
  {
    "subject": "640",
    "predicate": "HAS_LOAN_TERM",
    "object": "36 to 48",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The duration or range of duration (in months) available for a loan based on the credit score."
  },
  {
    "subject": "700",
    "predicate": "HAS_LOAN_TERM",
    "object": "60",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The duration or range of duration (in months) available for a loan based on the credit score."
  },
  {
    "subject": "685",
    "predicate": "HAS_LOAN_TERM",
    "object": "48 to 60",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The duration or range of duration (in months) available for a loan based on the credit score."
  },
  {
    "subject": "740",
    "predicate": "HAS_LOAN_TERM",
    "object": "60 to 84",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The duration or range of duration (in months) available for a loan based on the credit score."
  },
  {
    "subject": "800",
    "predicate": "HAS_LOAN_TERM",
    "object": "84",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The duration or range of duration (in months) available for a loan based on the credit score."
  },
  {
    "subject": "753",
    "predicate": "HAS_LOAN_TERM",
    "object": "60 to 84",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The duration or range of duration (in months) available for a loan based on the credit score."
  },
  {
    "subject": "300",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "38.5%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The likelihood or estimated likelihood of default associated with a specific credit score."
  },
  {
    "subject": "400",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "28.7%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The likelihood or estimated likelihood of default associated with a specific credit score."
  },
  {
    "subject": "350",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "Not explicitly provided (falls between 38.5% and 28.7%)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The likelihood or estimated likelihood of default associated with a specific credit score."
  },
  {
    "subject": "500",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "18.6%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The likelihood or estimated likelihood of default associated with a specific credit score."
  },
  {
    "subject": "620",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "8.5%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The likelihood or estimated likelihood of default associated with a specific credit score."
  },
  {
    "subject": "560",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "Not explicitly provided (falls between 18.6% and 11.3%)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The likelihood or estimated likelihood of default associated with a specific credit score."
  },
  {
    "subject": "700",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "3.3%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The likelihood or estimated likelihood of default associated with a specific credit score."
  },
  {
    "subject": "800",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "0.7%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The likelihood or estimated likelihood of default associated with a specific credit score."
  },
  {
    "subject": "733",
    "predicate": "HAS_DEFAULT_PROBABILITY",
    "object": "Not explicitly provided (falls between 3.3% and 1.8%)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "The likelihood or estimated likelihood of default associated with a specific credit score."
  }
]

Extracted triples Gemini (JSON):
[]
