```JSON
{
  "@context": [
    "https://auroralh2020.github.io/auroral-ontology-contexts/adapters/context.json",
    { 
     "rdfs": "http://www.w3.org/2000/01/rdf-schema#"
    },
    {
      "iid": { "@id": "rdfs:label" }
    }
  ],
  "oid": "1234",
  "iid": "mytemperature",
  "@type": "adp:Thermometer",
  "measurement": [
    {
      "value": 123,
      "type": "number",
      "timestamp": "2022-06-17T08:26:22Z",
      "property": "AmbientTemperature",
      "isMeasuredIn": "degreeCelsius"
    }
  ]
}
```
