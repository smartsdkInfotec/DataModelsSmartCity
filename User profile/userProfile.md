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

+ `username` : The username of user 
    + Normative References: [https://schema.org/name](https://schema.org/name)
    + Mandatory
	
+ `password` : The password, PIN, or access code
    + Normative References: [https://schema.org/accessCode](https://schema.org/accessCode)
    + Mandatory
	
+ `email` : The email account of user
    + Normative References: [https://schema.org/email](https://schema.org/email)
    + Mandatory

+ `name` : The name of user. 
    + Normative References: [https://schema.org/name](https://schema.org/name)
    + Mandatory
	
+ `family names` : The last name of user
    + Normative References: [https://schema.org/familyName](https://schema.org/familyName)
    + Mandatory
	
+ `gender` : The gender of user
    + Normative References: [https://schema.org/gender](https://schema.org/gender)
    + Optional

+ `homeAddress` : Civic address where the user lives.
	+ Attribute type: Text
    + Normative References: [https://schema.org/address](https://schema.org/address)
    + Optional	

+ `homecity` : A city or town where the user lives.
	+ Attribute type: Text
    + Normative References: [https://schema.org/City](https://schema.org/City)
    + Optional	

+ `homestate` : A state or province of a country where the user lives.
	+ Attribute type: Text
    + Normative References: [https://schema.org/State](https://schema.org/State)
    + Optional	
	
+ `homecountry` : A country where the user lives.
	+ Attribute type: Text
    + Normative References: [https://schema.org/Country](https://schema.org/Country)
    + Optional	
	
+ `homeLocation` : The location of the house of a user represented by a GeoJSON geometry.
	+ Attribute type: geo:json
    + Normative References: [https://tools.ietf.org/html/rfc7946](https://tools.ietf.org/html/rfc7946)
    + Optional	

+ `workAddress` : Civic address where the user works.
	+ Attribute type: Text
    + Normative References: [https://schema.org/address](https://schema.org/address)
    + Optional		

+ `workcity` : A city or town where the user works.
	+ Attribute type: Text
    + Normative References: [https://schema.org/City](https://schema.org/City)
    + Optional	

+ `workstate` : A state or province of a country where the user works.
	+ Attribute type: Text
    + Normative References: [https://schema.org/State](https://schema.org/State)
    + Optional	
		
+ `workcountry` : A country where the user works.
	+ Attribute type: Text
    + Normative References: [https://schema.org/Country](https://schema.org/Country)
    + Optional	

+ `worklocation` : The location of the work of a user represented by a GeoJSON geometry..
	+ Attribute type: geo:json.
    + Normative References: [https://tools.ietf.org/html/rfc7946](https://tools.ietf.org/html/rfc7946)
    + Optional	

	