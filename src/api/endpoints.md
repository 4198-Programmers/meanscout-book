# Endpoints

Endpoints are the points in the API that the Meanscout client can interact through.

```admonish warning
Endpoints may change
```

## /scouting
This endpoint is normally where all of the match data goes through. Currently the API will take in items via a hardcoded struct located in *csvstuff.rs*. In the near future this will just dynamically run through the data to eliminate the need to recompile after changing the data.

