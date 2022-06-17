```JSON
{
  "@context": [
    "https://www.w3.org/2019/wot/td/v1",
    "https://w3c.github.io/wot-discovery/context/discovery-context.jsonld"
  ],
  "oid": "1234",
  "@type": "Thermometer",
  "pid": "room_temperature",
  "makesMeasurement": [
    {
        "value": 10,
        "isMeasuredIn": "degreeCelsius",
        "hasValueType": "number",
        "aboutProperty": "AmbientTemperature",
        "timestamp": "2022-06-17T08:26:22Z"
    }
  ]
}
```