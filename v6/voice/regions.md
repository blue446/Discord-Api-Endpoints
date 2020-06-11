This endpoint is called to find the best server Discord should put you on.
https://best.discord.media/region
return for e.g 
``us-west``
``us-south``
``us-east`` etc
also when you start a call it calls this endpoint: https://discord.com/api/v6/voice/regions
this return all servers for some reason...
```json
[
    {
        "id": "us-west",
        "name": "US West",
        "vip": false,
        "custom": false,
        "deprecated": false,
        "optimal": true
    },
    {
        "id": "us-east",
        "name": "US East",
        "vip": false,
        "custom": false,
        "deprecated": false,
        "optimal": false
    },
    {
        "id": "us-central",
        "name": "US Central",
        "vip": false,
        "custom": false,
        "deprecated": false,
        "optimal": false
    },
    {
        "id": "us-south",
        "name": "US South",
        "vip": false,
        "custom": false,
        "deprecated": false,
        "optimal": false
    },
    {
        "id": "singapore",
        "name": "Singapore",
        "vip": false,
        "custom": false,
        "deprecated": false,
        "optimal": false
    },
    {
        "id": "southafrica",
        "name": "South Africa",
        "vip": false,
        "custom": false,
        "deprecated": false,
        "optimal": false
    },
    {
        "id": "sydney",
        "name": "Sydney",
        "vip": false,
        "custom": false,
        "deprecated": false,
        "optimal": false
    },
    {
        "id": "europe",
        "name": "Europe",
        "vip": false,
        "custom": false,
        "deprecated": false,
        "optimal": false
    },
    {
        "id": "brazil",
        "name": "Brazil",
        "vip": false,
        "custom": false,
        "deprecated": false,
        "optimal": false
    },
    {
        "id": "hongkong",
        "name": "Hong Kong",
        "vip": false,
        "custom": false,
        "deprecated": false,
        "optimal": false
    },
    {
        "id": "russia",
        "name": "Russia",
        "vip": false,
        "custom": false,
        "deprecated": false,
        "optimal": false
    },
    {
        "id": "japan",
        "name": "Japan",
        "vip": false,
        "custom": false,
        "deprecated": false,
        "optimal": false
    },
    {
        "id": "india",
        "name": "India",
        "vip": false,
        "custom": false,
        "deprecated": false,
        "optimal": false
    },
    {
        "id": "dubai",
        "name": "Dubai",
        "vip": false,
        "custom": false,
        "deprecated": true,
        "optimal": false
    },
    {
        "id": "amsterdam",
        "name": "Amsterdam",
        "vip": false,
        "custom": false,
        "deprecated": true,
        "optimal": false
    },
    {
        "id": "london",
        "name": "London",
        "vip": false,
        "custom": false,
        "deprecated": true,
        "optimal": false
    },
    {
        "id": "frankfurt",
        "name": "Frankfurt",
        "vip": false,
        "custom": false,
        "deprecated": true,
        "optimal": false
    },
    {
        "id": "eu-central",
        "name": "Central Europe",
        "vip": false,
        "custom": false,
        "deprecated": true,
        "optimal": false
    },
    {
        "id": "eu-west",
        "name": "Western Europe",
        "vip": false,
        "custom": false,
        "deprecated": true,
        "optimal": false
    }
]
```
