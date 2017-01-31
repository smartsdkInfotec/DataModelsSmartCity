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

+ `treatment` : A possible treatment to address this condition, sign or symptom of user.
    + Attribute type: Text
	+ Normative References: [https://health-lifesci.schema.org/possibleTreatment](https://health-lifesci.schema.org/possibleTreatment)
    + Optional

+ `drug` : Specifying a drug or medicine used by user
    + Attribute type: Text
	+ Normative References: [https://health-lifesci.schema.org/drug](https://health-lifesci.schema.org/drug)
    + Optional

+ `riskfactor` : A modifiable or non-modifiable factor that increases the risk of user contracting this condition
    + Attribute type: Text
	+ Normative References: [https://health-lifesci.schema.org/riskFactor](https://health-lifesci.schema.org/riskFactor)
    + Optional
	
