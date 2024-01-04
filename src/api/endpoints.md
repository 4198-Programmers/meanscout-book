# Endpoints

Endpoints are the points in the API that the Meanscout client can interact through.

## /scouting
This endpoint is normally where all of the match data goes through. 
<br>~Currently the API will take in items via a hardcoded struct located in *csvstuff.rs*. In the near future this will just dynamically run through the data to eliminate the need to recompile after changing the data.~
The api currently dynamically parses the data and sorts it with no need of recompilation.

```admonish warning
Currently if you change the datapoints on the meanscout client, you may need to delete or move the contents of data.csv. This is because the new data will not fit into the sorted columns that were made before the change. This will be changed in a later version of the meanscout api.
```
