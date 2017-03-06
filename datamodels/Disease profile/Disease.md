# Disease data model

## Description
This entity models the health condition of a user, including properties such as pathology, symptom and riskfactor. This information could be useful to determine the best route to follow to reach a destination, taking into account the user health conditions. We use this model in Smart City App to propose an ideal route for the user, avoiding high levels of pollution, floods or pollen, etc., allowing for instance, to obtain the preferred routes for people with respiratory diseases.

We consider to use this model to 
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

+ `riskfactor` : A modifiable or non-modifiable factor that increases the risk of user contracting this condition.
    + Attribute type: Text
	+ Normative References: [https://health-lifesci.schema.org/riskFactor](https://health-lifesci.schema.org/riskFactor)
    + Optional
	
