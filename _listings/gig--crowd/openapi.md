swagger: "2.0"
x-collection-name: GIG & CROWD
x-complete: 1
info:
  title: GIG & Crowd
  version: 1.0.0
host: gigandcrowd.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/message/count/{userId}:
    get:
      summary: Get Message Count Userid
      description: Get message count userid.
      operationId: getApiV1MessageCountUser
      x-api-path-slug: apiv1messagecountuserid-get
      parameters:
      - in: header
        name: Authorization
      - in: path
        name: userId
      responses:
        200:
          description: OK
      tags:
      - Message
      - Count
      - Userid
  /api/v1/country/{query}:
    get:
      summary: Get Country Query
      description: Get country query.
      operationId: getApiV1CountryQuery
      x-api-path-slug: apiv1countryquery-get
      parameters:
      - in: path
        name: query
      responses:
        200:
          description: OK
      tags:
      - Country
      - Query