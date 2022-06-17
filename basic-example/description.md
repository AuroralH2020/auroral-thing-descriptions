# Thermometer example

This is a basic example to describe a Thermometer sensor to illustrate how to use the Thing Descriptions.

It will present a Thing Description that recreates the following API.

BASE URI: www.mydata.example.com/api

GET /object/1234/property/room_temperature

**See td.md**

## Mapping example

The device with *OID 1234* of *type Thermometer* receives a request to read its *property room_temperature*.

The device makesMeasurement of 1 property which returns the value 10. This value is annotated with 4 additional tags:

* isMeasuredIn: Unit of measurement of phisical property measured. Available options in adapters ontology.
* hasValueType: Data type. Number, string, array, boolean, object.
* aboutProperty: Phisical property the sensor is reading. Available options in adapters ontology.
* timestamp: Date of event occurence

**See mapping.md**