```

{
    "@context": ["https://www.w3.org/2019/wot/td/v1",
                 "https://auroralh2020.github.io/auroral-ontology-contexts/core/services.json"],
    "@type": "Service",
    "title":"Tourism monitor",
    "description":"Person counter",
    "provider":"BOSONIT",
    "currentStatus":"Available",
    "modified":"2021-11-09T18:25:43.511Z",
    "hasDomain":"Mobility",
    "hasSubDomain":"Fly",
    "hasFunctionality":"Only read",
    "hasRequirement":"The date to read the persons",
    "serviceFree":true,
    "numberOfDownload": 1,
    "versionOfService":"1.4",
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
