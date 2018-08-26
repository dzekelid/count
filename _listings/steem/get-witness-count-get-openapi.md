---
swagger: "2.0"
x-collection-name: Steem
x-complete: 0
info:
  title: Steem get_witness_count
  description: get_witness_count
  version: 1.0.0
host: api.steemjs.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /get_witness_count:
    get:
      summary: get_witness_count
      description: get_witness_count
      operationId: get-witness-count
      x-api-path-slug: get-witness-count-get
      responses:
        200:
          description: OK
      tags:
      - Get
      - Witness
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