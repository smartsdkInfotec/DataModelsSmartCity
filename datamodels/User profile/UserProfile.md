# User profile data model

## Description
This entity models a user. This model presents the relationships that a user could have with a disease, a vehicle, a device and  Smart POIs. 
In addition, this model considers the addresses of home and workplace of a user. The objective to consider these data is to save favorites routes and to determine in a quicker manner a route.

## Data model

+ `id` : Entity's unique identifier. 

+ `type` : Entity type. It must be equal to `user`.

+ `id_disease` : Unique identifier related to user disease. 

+ `id_vehicle` : Unique identifier related to user vehicle.

+ `id_device` : Unique identifier related to user device.

+ `id_POI` : Unique identifier related to user POIs

+ `name` : The name of user. 
	+ Attribute type: text
    + Normative References: [https://schema.org/name](https://schema.org/name)
    + Mandatory
	
+ `family name` : The last name of user
	+ Attribute type: text
    + Normative References: [https://schema.org/familyName](https://schema.org/familyName)
    + Mandatory

+ `gender`: The gender of user
	+ Attribute type: text
	+ Normative References: [https://schema.org/gender] (https://schema.org/gender)
	+ Optional

+ `birthDate`:The date of birth of user
	+ Attribute type: Date
	+ Normative References: [https://schema.org/birthDate] (https://schema.org/birthDate)
	+ Optional	

+ `homeaddress`: Civic address of a user´s home. 
	+ Normative References: [https://schema.org/address]
	+ Optional

+ `workaddress`: Civic address of the workplace user. 
	+ Normative References: https://schema.org/address
	+ Optional

+ `dateCreated` : Entity's creation timestamp
	 + Attribute type: DateTime
	 + Optional

+ `dateModified` : Last update timestamp of this entity
	+ Attribute type: DateTime
	+ Optional
	