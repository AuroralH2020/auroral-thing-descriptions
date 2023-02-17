```JSON
 {
  "@context": [
    "https://www.w3.org/2019/wot/td/v1",
    { 
     "adp": "https://auroral.iot.linkeddata.es/def/adapters#",
     "om": "http://www.ontology-of-units-of-measure.org/resource/om-2/",
     "geo": "http://www.w3.org/2003/01/geo/wgs84_pos#"
    }
  ],
  "security": [
    "nosec_sc"
  ],
  "securityDefinitions": {
    "nosec_sc": {
      "scheme": "nosec"
    }
  },
  "geo:location": {
    	"geo:lat": "48.1516",
	    "geo:long": "17.1674"
  },
  "title": "MyRoomTemperature",
  "adapterId": "thermometer-Id-In-My-Infrastructure",
  "@type": "adp:Thermometer",
  "description": "Room temperature sensor",
  "properties": {
    "room_temperature": {
      "title": "room_temperature",
      "description": "temperature in the room",
      "@type": "adp:AmbientTemperature",
      "unit": "om:degree_Celsius",
      "readOnly": true,
      "type": "number",
      "forms": [
        {
          "op": "readproperty",
          "href": "www.mydata.example.com/api/object/1234/property/room_temperature"
        }
      ]
    }
  }
}

