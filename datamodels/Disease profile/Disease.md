# Disease data model

## Description
A disease.

## Data model

+ `id` : Entity's unique identifier. 

+ `type` : Entity type. It must be equal to `disease`.

+ `pathology` : Illness physical or mental of user
    + Attribute type: Text
	+ Normative References: [https://health-lifesci.schema.org/Pathology](https://health-lifesci.schema.org/Pathology)
    + Optional

+ `symptom` : A sign or symptom of user condition.
    + Attribute type: Text
	+ Normative References: [http://health-lifesci.schema.org/signOrSymptom](http://health-lifesci.schema.org/signOrSymptom)
    + Optional

+ `riskfactor` : A modifiable or non-modifiable factor that increases the risk of user contracting this condition
    + Attribute type: Text
	+ Normative References: [https://health-lifesci.schema.org/riskFactor](https://health-lifesci.schema.org/riskFactor)
    + Optional
	
