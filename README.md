# match-district
District match UI

Figure out the user's US Congressional district, first by looking it up by ZIP code, and if that's inconclusive, looking it up by street address.

Running this code requires a Mapzen API key and a Knack application ID, which should be in a config.js file like this:
```
var config = {
    MAPZEN_API_KEY: "your_mapzen_api_key_here"
    KNACK_APPLICATION_ID: "your_knack_application_id_here"
}
```
