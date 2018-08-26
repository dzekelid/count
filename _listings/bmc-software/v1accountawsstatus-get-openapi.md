---
swagger: "2.0"
x-collection-name: BMC Software
x-complete: 0
info:
  title: BMC Software API Get AWS Integration Status
  version: 1.0.0
  description: Gets AWS status
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account:
    get:
      summary: Account Resource
      description: Information about the authorized account.
      operationId: information-about-the-authorized-account
      x-api-path-slug: account-get
      responses:
        200:
          description: OK
      tags:
      - Account
  /v1/account/aws/status:
    get:
      summary: Get AWS Integration Status
      description: Gets AWS status
      operationId: get-aws-integration-status
      x-api-path-slug: v1accountawsstatus-get
      responses:
        200:
          description: OK
      tags:
      - Account
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