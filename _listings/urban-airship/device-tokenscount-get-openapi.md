---
swagger: "2.0"
x-collection-name: Urban Airship
x-complete: 0
info:
  title: Urban Airship Get Device Tokens Count
  description: Gets the number of device tokens you have registered.
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---