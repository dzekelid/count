---
swagger: "2.0"
x-collection-name: BMC Software
x-complete: 1
info:
  title: BMC Software Merged API
  version: 1.0.0
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
  /v1/account/mobile-devices/:accountDeviceId:
    delete:
      summary: Delete Account Mobile Device
      description: Deletes a device from an account
      operationId: delete-account-mobile-device
      x-api-path-slug: v1accountmobiledevicesaccountdeviceid-delete
      parameters:
      - in: query
        name: |-
          accountDeviceId
          The account device ID to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Account
  /v1/account/mobile-devices:
    get:
      summary: Get All Account Mobile Devices
      description: Gets all of the devices for an account
      operationId: get-all-account-mobile-devices
      x-api-path-slug: v1accountmobiledevices-get
      responses:
        200:
          description: OK
      tags:
      - Account
  /v1/account/sources/:lastModified?:
    get:
      summary: Get all source information
      description: Gets all source (host + data stream) information
      operationId: get-all-source-information
      x-api-path-slug: v1accountsourceslastmodified-get
      responses:
        200:
          description: OK
      tags:
      - Account
  /v1/account/sources:
    put:
      summary: Set source metadata
      description: Sets one or more source metadata
      operationId: set-source-metadata
      x-api-path-slug: v1accountsources-put
      responses:
        200:
          description: OK
      tags:
      - Account
---