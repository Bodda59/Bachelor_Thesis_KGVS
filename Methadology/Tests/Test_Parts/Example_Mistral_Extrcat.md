Extracted triples MISTRAL(JSON):
[
  {
    "subject": "350",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "22.1%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price that is paid upfront as a down payment for the credit score tier."
  },
  {
    "subject": "400",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "19.4%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price that is paid upfront as a down payment for the credit score tier."
  },
  {
    "subject": "373",
    "predicate": "HAS_DOWN_PAYMENT_PERCENTAGE",
    "object": "20.75%",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates the percentage of the total purchase price that is paid upfront as a down payment for the credit score tier."
  },
  {
    "subject": "350",
    "predicate": "REPRESENTS_CREDIT_SCORE_TIER",
    "object": "Poor (300-579)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Categorizes the credit score into a risk tier based on the provided value, extrapolated from common credit score ranges."
  },
  {
    "subject": "373",
    "predicate": "REPRESENTS_CREDIT_SCORE_TIER",
    "object": "Fair (580-669)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Categorizes the credit score into a risk tier based on the provided value, extrapolated from common credit score ranges."
  },
  {
    "subject": "400",
    "predicate": "REPRESENTS_CREDIT_SCORE_TIER",
    "object": "Fair (580-669)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Categorizes the credit score into a risk tier based on the provided value, extrapolated from common credit score ranges."
  },
  {
    "subject": "Poor (300-579)",
    "predicate": "HAS_HIGHER_DOWN_PAYMENT_THAN",
    "object": "Fair (580-669)",
    "is_verifiable": true,
    "verification_type": "ENTITY_ATTRIBUTE",
    "predicate_definition": "Indicates that one credit score tier requires a higher down payment percentage compared to another."
  }
]

Raw response from LLM: ```json
{"Subject":"350","Predicate":"has_down_payment","Object":"22.1%"}
{"Subject":"400","Predicate":"has_down_payment","Object":"19.4%"}
{"Subject":"373","Predicate":"has_down_payment","Object":"20.75%"}