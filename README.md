POKEDEX

Build a Pokedex API server. A frontend application would make requests to our endpoints to get information about different pokemon.

The requirements for the app are:

1. Users can search for Pokemon by name or type
2. The endpoint is GET /pokemon
3. The search options for either name or type are provided in query string parameters.
4. When searching by name, users are searching for whether the Pokemon's name includes a specified string. The search should be case insensitive.
5. When searching by type, users must specify one of the valid types.
6. The API responds with an array of full pokedex entries for the search results
7. Users can request a list of all the valid types of Pokemon.
8. The endpoint is GET /types
9. Both endpoints are public and only respond when given a valid Authorization header with a Bearer API token value.
10. Both endpoints should have general security in place.
