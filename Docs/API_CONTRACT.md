# SAARTHI API Contract

## POST /match

### Request

{
  "category": "SC",
  "location": "Bihar",
  "age": 27,
  "gender": "Male",
  "business_type": "Manufacturing",
  "income": 300000,
  "funding_required": 500000
}

### Response

{
  "schemes": [
    {
      "id": 1,
      "name": "Example Scheme",
      "match_score": 94,
      "eligible": true,
      "match_reasons": [
        "Category matched",
        "Location matched",
        "Business type matched"
      ]
    }
  ]
}