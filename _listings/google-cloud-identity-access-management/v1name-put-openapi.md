---
swagger: "2.0"
x-collection-name: Google Cloud Identity Access Management
x-complete: 0
info:
  title: Google Cloud Identity & Access Management API Update Service Account Key
  description: |-
    Updates a ServiceAccount.

    Currently, only the following fields are updatable:
    `display_name` .
    The `etag` is mandatory.
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
    get:
      summary: Get Service Account Key
      description: |-
        Gets the ServiceAccountKey
        by key id.
      operationId: iam.projects.serviceAccounts.keys.get
      x-api-path-slug: v1name-get
      parameters:
      - in: path
        name: name
        description: The resource name of the service account key in the following
          format:`projects/{PROJECT_ID}/serviceAccounts/{SERVICE_ACCOUNT_EMAIL}/keys/{key}`
      - in: query
        name: publicKeyType
        description: The output format of the public key requested
      responses:
        200:
          description: OK
      tags:
      - Service Account Key
    put:
      summary: Update Service Account Key
      description: |-
        Updates a ServiceAccount.

        Currently, only the following fields are updatable:
        `display_name` .
        The `etag` is mandatory.
      operationId: iam.projects.serviceAccounts.update
      x-api-path-slug: v1name-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: The resource name of the service account in the following format:`projects/{PROJECT_ID}/serviceAccounts/{SERVICE_ACCOUNT_EMAIL}`
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