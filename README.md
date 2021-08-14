# eventor-api-openapi-spec

[![Travis build status](https://travis-ci.com/mikaello/eventor-api-openapi-spec.svg?branch=main&status=passed)](https://travis-ci.com/github/mikaello/eventor-api-openapi-spec)

OpenAPI spec / Swagger for the Eventor API: [openapi.yml](./openapi.yml).

You can browse the [Swagger UI](https://mikaello.github.io/eventor-api-openapi-spec) for this spec, but it will not work because of CORS. You can use it to browse and create cURL commands that you can execute in your own terminal. Or you could import the OpenAPI spec into Postman and make your calls from there.

**What is Eventor?** Eventor is the event system for [orienteering](https://en.wikipedia.org/wiki/Orienteering) races in different countries, so if you want to arrange an orienteering event, you will probably register it in your local Eventor system to make other people see it and for them to register to your event (and where you can upload results after the event is done).

## Usage of the Eventor API

To use the Eventor API, you need an API key.

The different Eventor websites are:

- [Norwegian Eventor](https://eventor.orientering.no/)
- [Swedish Eventor](https://eventor.orientering.se/)
- [Australian Eventor](https://eventor.orienteering.asn.au/)
- [International Eventor](https://eventor.orienteering.org/)

Add `/api/documentation` to either of the URLs to get the documentation for that particular Eventor website (the documentation is also included in the OpenAPI specification).
