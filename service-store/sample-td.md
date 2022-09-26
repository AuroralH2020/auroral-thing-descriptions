```

{
    "@context": ["https://www.w3.org/2019/wot/td/v1",
                 "https://auroralh2020.github.io/auroral-ontology-contexts/core/services.json"],
    "id": "urn:dev:ops:32473-WoTLamp-1234",
    "title":"Tourism monitor",
    "description":"Person counter",
    "provider":"BOSONIT",
    "status":"Available",
    "modified":"2021-11-09T18:25:43.511Z",
    "domain":"Mobility",
    "subdomain":"Fly",
    "functionalities":"Only read",
    "requirements":"The date to read the persons",
    "is_free":true,
    "downloaded": 1,
    "version":"1.4",
    "language":"spa",
    "place":"Spain",
    "securityDefinitions": { "nosec_sc": { "scheme": "nosec" }},
    "security": "nosec_sc ",
    "properties": {
        "status" : {
            "type": "string",
            "forms": [{"href": "http://rur.tourism.com/itisveryimportant/birds"}]
        }
    }
}
```
