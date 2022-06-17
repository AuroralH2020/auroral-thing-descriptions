```JSON
{
  "title": "MyRoomTemperature",
  "@context": [
    "https://www.w3.org/2019/wot/td/v1",
    "https://w3c.github.io/wot-discovery/context/discovery-context.jsonld"
  ],
  "security": [
    "nosec_sc"
  ],
  "securityDefinitions": {
    "nosec_sc": {
      "scheme": "nosec"
    }
  },
  "oid": "1234",
  "adapterId": "thermometerIdInMyInfrastructure",
  "@type":
    "Thermometer",
  "located_in": {
    "location_type": "Building",
    "location_id": "http://dbpedia.org/building/example",
    "label": "Office with temperature sensor"
  },
  "description": "Room temperature sensor",
  "properties": {
    "room_temperature": {
      "title": "room_temperature",
      "monitors": "AmbientTemperature",
      "measures": "degreeCelsius",
      "readOnly": true,
      "type": "number",
      "forms": [
        {
          "op": [
            "readproperty"
          ],
          "href": "www.mydata.example.com/api/object/1234/property/room_temperature"
        }
      ]
    }
  }
}