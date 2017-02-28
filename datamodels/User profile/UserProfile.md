# User profile data model

## Description
A user.

## Data model

+ `id` : Entity's unique identifier. 

+ `type` : Entity type. It must be equal to `user`.

+ `id_disease` : Unique identifier related to user disease. 

+ `id_vehicle` : Unique identifier related to user vehicle.

+ `id_device` : Unique identifier related to user device.

+ `id_POI` : Unique identifier related to user POIs

+ `id_system_friends` : Unique identifier related to friends in the system

+ `name` : The name of user. 
	+ Attribute type: text
    + Normative References: [https://schema.org/name](https://schema.org/name)
    + Mandatory
	
+ `family name` : The last name of user
	+ Attribute type: text
    + Normative References: [https://schema.org/familyName](https://schema.org/familyName)
    + Mandatory

+ `gender`:The gender of user
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
	