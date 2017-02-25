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
    + Normative References: [https://schema.org/name](https://schema.org/name)
    + Mandatory
	
+ `family name` : The last name of user
    + Normative References: [https://schema.org/familyName](https://schema.org/familyName)
    + Mandatory

+ `homeLocation` : The location of the house of a user represented by a GeoJSON geometry.
	+ Attribute type: geo:json
    + Normative References: [https://tools.ietf.org/html/rfc7946](https://tools.ietf.org/html/rfc7946)
    + Optional	

+ `worklocation` : The location of the work of a user represented by a GeoJSON geometry..
	+ Attribute type: geo:json.
    + Normative References: [https://tools.ietf.org/html/rfc7946](https://tools.ietf.org/html/rfc7946)
    + Optional	

+ `dateCreated` : Entity's creation timestamp
	 + Attribute type: DateTime
	 + Optional

+ `dateModified` : Last update timestamp of this entity
	+ Attribute type: DateTime
	+ Optional
	