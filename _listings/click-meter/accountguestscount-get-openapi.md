---
swagger: "2.0"
x-collection-name: Click Meter
x-complete: 0
info:
  title: Click Meter Retrieve count of guests
  description: Retrieve count of guests.
  contact:
    name: Api Support
    url: http://www.clickmeter.com/api
    email: api@clickmeter.com
  version: v2
host: apiv2.clickmeter.com:80
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account/guests/count:
    get:
      summary: Retrieve count of guests
      description: Retrieve count of guests.
      operationId: getAccountGuestsCount
      x-api-path-slug: accountguestscount-get
      parameters:
      - in: query
        name: textSearch
        description: Filter fields by this pattern
      responses:
        200:
          description: OK
      tags:
      - Account
      - Guests
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