# Disease data model

## Description
This entity models the health condition of a user, including properties such as pathology, symptom and riskfactor. This information could be useful to determine the best route to follow to reach a destination, taking into account the user health conditions. We use this model in Smart City App to propose an ideal route for the user, avoiding high levels of pollution, floods or pollen, etc., allowing for instance, to obtain the preferred routes for people with respiratory diseases.


## Examples of use
	{
		"id": "disease:asthma",
		"type": "disease", 
		"pathology": "Mild Intermittent Asthma",
		"symptom": "cough, wheeze, chest tightness or difficulty breathing less than twice a week.", 
		"PhysicalActivity": "Do not interfere with normal activities",
		"possibleComplication": "Nighttime symptoms less than twice a month"
		"dateCreated": "2017-01-02T09:25:55.00Z",
		"dateModified": "2017-02-02T011:13:55.00Z"
	}  

## Use it with a real service
T.B.D

## Open Issues
T.B.D