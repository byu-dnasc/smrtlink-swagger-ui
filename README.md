# smrtlink_swagger_ui

UI for browsing SMRT Link web services API specification

## usage
To access the UI, follow these instructions:

1. download/clone this repository.
2. navigate to said repository and run `python -m http.server`.
3. visit http://localhost:8000/index.html (make sure the browser doesn't try to change "http" to "https").

Note that you cannot 'Try it out'. The Swagger UI functionality for making API calls is nonfunctional since it cannot access the server as configured in this repository.

## note on URL formation

To form a URL, use `http://localhost:9091` as the prefix. The SMRT Link uses a different endpoint since it goes through the API gateway.

## citation
I followed [these instructions](https://github.com/swagger-api/swagger-ui/blob/v5.4.2/docs/usage/installation.md#plain-old-htmlcssjs-standalone) in the Swagger UI docs to create this repository.
