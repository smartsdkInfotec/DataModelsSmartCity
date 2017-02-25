# Vehicle

## Description

A vehicle.

## Data Model

+ `id` : Entity's unique identifier. 

+ `type` : Entity type. It must be equal to `Vehicle`.

+ `name` : Name given to this vehicle. 
    + Normative References: [https://schema.org/name](https://schema.org/name)
    + Optional

+ `description` : Vehicle description. 
    + Normative References: [https://schema.org/description](https://schema.org/description)
    + Optional
    
+ `vehicleType` : Type of vehicle from the point of view of its structural characteristics.
This is different than the vehicle category (see below).
    + Attribute type: [Text](https://schema.org/Text)
    + Allowed Values: The following values defined by *VehicleTypeEnum* and *VehicleTypeEnum2*,
    [DATEX 2 version 2.3](http://www.datex2.eu/sites/www.datex2.eu/files/DATEXIISchema_2_2_2_1.zip):
        + (`bicycle`, `car`,  `motorcycle`,)
    + Mandatory

+ `location` : Vehicle's last known location represented by a GeoJSON Point. Such point may contain the vehicle's
*altitude* as the third component of the `coordinates` array. 
    + Attribute type: `geo:json`.
    + Normative References: [https://tools.ietf.org/html/rfc7946](https://tools.ietf.org/html/rfc7946)
    + Attribute metadata:
        + `timestamp`: Timestamp which captures when the vehicle was at that location.
        This value can also appear as a FIWARE [TimeInstant](https://github.com/telefonicaid/iotagent-node-lib/blob/develop/README.md#TimeInstant)
            + Type: [DateTime](http://schema.org/DateTime) or `ISO8601` (legacy).
            + Mandatory
    + Optional
    
+ `vehiclePlateIdentifier` : An identifier or code displayed on a vehicle registration plate attached to the vehicle used for official identification purposes.
The registration identifier is numeric or alphanumeric and is unique within the issuing authority's region.
    + Normative References: DATEX II `vehicleRegistrationPlateIdentifier`
    + Attribute Type: [Text](https://schema.org/Text)
    + Mandatory if `vehicleIdentificationNumber` is not defined. 
    
+ `dateModified` : Last update timestamp of this entity.
    + Attribute type: [DateTime](https://schema.org/DateTime)
    + Optional

+ `dateCreated` : Creation timestamp of this entity.
    + Attribute type: [DateTime](https://schema.org/DateTime)
    + Optional
    
## Example

    {
      "id": "vehicle:WasteManagement:1",
      "type": "Vehicle",
      "vehicleType": "car",
      "location": {
         "type": "Point",
         "coordinates": [ -3.164485591715449, 40.62785133667262 ]
      },
      "vehiclePlateIdentifier": "3456ABC"
    }
