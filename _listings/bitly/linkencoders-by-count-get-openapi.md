---
swagger: "2.0"
x-collection-name: Bitly
x-complete: 0
info:
  title: Bitly Link Metrics API Users Who Encoded Link
  description: Returns users who have encoded this link (optionally only those in
    the requesting users social graph), sorted by the number of clicks on each encoding
    users link.
  termsOfService: http://dev.bitly.com/best_practices.html
  version: v3
host: api-ssl.bitly.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /link/encoders_by_count:
    get:
      summary: Users Who Encoded Link
      description: Returns users who have encoded this link (optionally only those
        in the requesting users social graph), sorted by the number of clicks on each
        encoding users link.
      operationId: usersWhoEncodedLink
      x-api-path-slug: linkencoders-by-count-get
      parameters:
      - in: query
        name: expand_user
        description: include display names of encoders
      - in: query
        name: limit
        description: integer in the range 1:100 that specifies the number of records
          to return (default:10)
      - in: query
        name: link
        description: a Bitlink
      - in: query
        name: my_network
        description: restrict to my network
      - in: query
        name: subaccounts
        description: restrict to this enterprise account and its subaccounts
      responses:
        200:
          description: OK
      tags:
      - Link
      - Encoders
      - By
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