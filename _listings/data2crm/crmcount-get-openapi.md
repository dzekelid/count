---
swagger: "2.0"
x-collection-name: Data2CRM
x-complete: 0
info:
  title: Data2CRM COUNT for Crm
  description: Count all CRMs from the system
  version: "1"
host: api.data2crm.com:80
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account/count:
    get:
      summary: COUNT for Account
      description: Count all accounts from the system
      operationId: getAccountCountCollection
      x-api-path-slug: accountcount-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Accounts
      - Count
  /attachment/count:
    get:
      summary: COUNT for Attachment
      description: Count all attachments from the system
      operationId: getAttachmentCountCollection
      x-api-path-slug: attachmentcount-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Attachments
      - Count
  /call/count:
    get:
      summary: COUNT for Call
      description: Count all calls from the system
      operationId: getCallCountCollection
      x-api-path-slug: callcount-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Calls
      - Count
  /contact/count:
    get:
      summary: COUNT for Contact
      description: Count all contacts from the system
      operationId: getContactCountCollection
      x-api-path-slug: contactcount-get
      parameters:
      - in: header
        name: X-API2CRM-CRMKEY
        description: CRM Key
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Count
  /crm/count:
    get:
      summary: COUNT for Crm
      description: Count all CRMs from the system
      operationId: getCrmCountCollection
      x-api-path-slug: crmcount-get
      parameters:
      - in: header
        name: X-API2CRM-USERKEY
        description: User Key
      responses:
        200:
          description: OK
      tags:
      - Crm
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