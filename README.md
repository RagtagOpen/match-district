# match-district
District match UI

Figure out the user's US Congressional district, first by looking it up by ZIP code, and if that's inconclusive, looking it up by street address.

Running this code requires a Google API key and a Knack application ID, which should be in a config.js file like this:
```
var config = {
    GOOGLE_API_KEY: "your_google_api_key_here"
    KNACK_APPLICATION_ID: "your_knack_application_id_here"
}
```

Then, from the root dir of your local repo,
```
python -mSimpleHTTPServer
```
and go to localhost:8000
