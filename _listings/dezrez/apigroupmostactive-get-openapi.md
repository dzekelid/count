---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Return the Groups with the most viewings between a given date range,
    ordered by viewing Count
  version: 1.0.0
  description: Return the groups with the most viewings between a given date range,
    ordered by viewing count.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/chat/unreadsummary:
    get:
      summary: Get a count of unread chat messages for the negotiator plus a list
        of corresponding message id's which are unread.
      description: Get a count of unread chat messages for the negotiator plus a list
        of corresponding message id's which are unread..
      operationId: Chat_UnreadSummary
      x-api-path-slug: apichatunreadsummary-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Count
      - Of
      - Unread
      - Chat
      - Messagesthe
      - Negotiator
      - Plus
      - List
      - Of
      - Corresponding
      - Message
      - Ids
      - Which
      - Are
      - Unread
  /api/documentgeneration/outstandingprintbagcount:
    get:
      summary: Outstanding Print Bag Count.
      description: Outstanding print bag count..
      operationId: DocumentGeneration_OutstandingPrintBagCount
      x-api-path-slug: apidocumentgenerationoutstandingprintbagcount-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Outstanding
      - Print
      - Bag
      - Count
  /api/group/updateprimarygroupmember:
    put:
      summary: Return the Groups with appointments between a given date range, ordered
        by appointments Count
      description: Return the groups with appointments between a given date range,
        ordered by appointments count.
      operationId: Group_UpdatePrimaryGroupMemberByfilter
      x-api-path-slug: apigroupupdateprimarygroupmember-put
      parameters:
      - in: body
        name: filter
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Return
      - Groups
      - Appointments
      - Between
      - Given
      - Date
      - Range
      - ""
      - Ordered
      - By
      - Appointments
      - Count
  /api/group/mostactive:
    get:
      summary: Return the Groups with the most viewings between a given date range,
        ordered by viewing Count
      description: Return the groups with the most viewings between a given date range,
        ordered by viewing count.
      operationId: Group_MostActiveBypageSizeByfilter.rangeFromByfilter.rangeToByfilter.branchIdByfilter.roleTypes
      x-api-path-slug: apigroupmostactive-get
      parameters:
      - in: query
        name: filter.branchId
      - in: query
        name: filter.rangeFrom
      - in: query
        name: filter.rangeTo
      - in: query
        name: filter.roleTypes
      - in: query
        name: pageSize
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Return
      - Groups
      - Most
      - Viewings
      - Between
      - Given
      - Date
      - Range
      - ""
      - Ordered
      - By
      - Viewing
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