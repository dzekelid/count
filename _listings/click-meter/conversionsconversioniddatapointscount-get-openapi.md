---
swagger: "2.0"
x-collection-name: Click Meter
x-complete: 0
info:
  title: Click Meter Retrieve a count of datapoints connected to this conversion
  description: Retrieve a count of datapoints connected to this conversion.
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
  /account/guests/{guestId}/permissions/count:
    get:
      summary: Retrieve count of the permissions for a guest
      description: Retrieve count of the permissions for a guest.
      operationId: getAccountGuestsGuestPermissionsCount
      x-api-path-slug: accountguestsguestidpermissionscount-get
      parameters:
      - in: query
        name: entityId
        description: Optional id of the datapoint/group entity to filter by
      - in: query
        name: entityType
        description: Can be datapoint or group
      - in: path
        name: guestId
        description: Id of the guest
      - in: query
        name: type
        description: Can be w or r
      responses:
        200:
          description: OK
      tags:
      - Account
      - Guests
      - GuestId
      - Permissions
      - Count
  /conversions/count:
    get:
      summary: Retrieve a count of conversions
      description: Retrieve a count of conversions.
      operationId: getConversionsCount
      x-api-path-slug: conversionscount-get
      parameters:
      - in: query
        name: createdAfter
        description: Exclude conversions created before this date (YYYYMMDD)
      - in: query
        name: createdBefore
        description: Exclude conversions created after this date (YYYYMMDD)
      - in: query
        name: status
        description: Status of conversion (deleted/active)
      - in: query
        name: textSearch
        description: Filter fields by this pattern
      responses:
        200:
          description: OK
      tags:
      - Conversions
      - Count
  /conversions/{conversionId}/datapoints/count:
    get:
      summary: Retrieve a count of datapoints connected to this conversion
      description: Retrieve a count of datapoints connected to this conversion.
      operationId: getConversionsConversionDatapointsCount
      x-api-path-slug: conversionsconversioniddatapointscount-get
      parameters:
      - in: path
        name: conversionId
        description: Id of the conversion
      - in: query
        name: createdAfter
        description: Exclude datapoints created before this date (YYYYMMDD)
      - in: query
        name: createdBefore
        description: Exclude datapoints created after this date (YYYYMMDD)
      - in: query
        name: status
        description: Status of datapoint (deleted/active/paused/spam)
      - in: query
        name: tags
        description: Filter by this tag name
      - in: query
        name: textSearch
        description: Filter fields by this pattern
      - in: query
        name: type
        description: Type of datapoint (tl/tp)
      responses:
        200:
          description: OK
      tags:
      - Conversions
      - ConversionId
      - Datapoints
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