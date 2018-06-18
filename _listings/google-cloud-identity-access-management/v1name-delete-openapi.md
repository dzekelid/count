---
swagger: "2.0"
x-collection-name: Google Cloud Identity Access Management
x-complete: 0
info:
  title: Google Cloud Identity & Access Management API Delete Service Account Key
  description: Deletes a ServiceAccountKey.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: iam.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{name}:
    delete:
      summary: Delete Service Account Key
      description: Deletes a ServiceAccountKey.
      operationId: iam.projects.serviceAccounts.keys.delete
      x-api-path-slug: v1name-delete
      parameters:
      - in: path
        name: name
        description: The resource name of the service account key in the following
          format:`projects/{PROJECT_ID}/serviceAccounts/{SERVICE_ACCOUNT_EMAIL}/keys/{key}`
      responses:
        200:
          description: OK
      tags:
      - Service Account Key
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