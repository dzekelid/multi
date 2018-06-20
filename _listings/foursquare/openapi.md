---
swagger: "2.0"
x-collection-name: Foursquare
x-complete: 1
info:
  title: Foursquare
  description: checkin-explore-your-city-and-connect-people-and-places-bapi-v2-b
  version: 1.0.0
host: api.foursquare.com
basePath: /v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /multi:
    get:
      summary: Get Multi
      description: /pages/{PAGE_ID}/venues
      operationId: pagespage-idvenues
      x-api-path-slug: multi-get
      parameters:
      - in: query
        name: requests
        description: A comma-delimited list of API requests
      - in: query
        name: v
        description: All requests now accept a v=YYYYMMDD param, which indicates that
          the client is up to date as of the specified date
      responses:
        200:
          description: OK
      tags:
      - Multi
---