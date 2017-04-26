# User profile data model

## Description
This entity models a user. In addition, this model considers the addresses of home and workplace of a user. The model considers these data due to that these could be used to save favorites places.

## Examples of use

	{
		"id": "user:1",
		"type": "user",  
		"name": "Iker",  
		"family name": "Smith", 
		"gender": "Smith",
		"birthDate": {
			"year":"1988",
			"month":"april",
			"day":"8"
		}
		"homeaddress": {
			"addressCountry": "Mexico",
			"addressRegion": "Ciudad de México",
			"addressLocality": "Coyoacán",
			"streetAddress": "Puente de Piedra 150",
			"postalCode": "14090"
		},
		"dateCreated": "2017-01-02T09:25:55.00Z",
		"dateModified": "2017-02-02T011:13:55.00Z"
	}