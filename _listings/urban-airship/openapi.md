swagger: "2.0"
x-collection-name: Urban Airship
x-complete: 1
info:
  title: Urban Airship
  description: the-urban-airships-api-powers-mobile-applications-with-push-rich-push-inapp-purchases-and-subscription-services-
  version: v3
host: go.urbanairship.com
basePath: /api/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /device_tokens/count:
    get:
      summary: Get Device Tokens Count
      description: Gets the number of device tokens you have registered.
      operationId: device_tokens.count.get
      x-api-path-slug: device-tokenscount-get
      parameters:
      - in: query
        name: limit
        description: The total items to return
      - in: query
        name: page
        description: The page number
      responses:
        200:
          description: OK
      tags:
      - Device
      - Tokens
      - Count