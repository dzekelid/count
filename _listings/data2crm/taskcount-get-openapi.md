---
swagger: "2.0"
x-collection-name: Data2CRM
x-complete: 0
info:
  title: Data2CRM COUNT for Task
  description: Count all tasks from the system
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
  /email/count:
    get:
      summary: COUNT for Email
      description: Count all emails from the system
      operationId: getEmailCountCollection
      x-api-path-slug: emailcount-get
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
      - Emails
      - Count
  /event/count:
    get:
      summary: COUNT for Event
      description: Count all events from the system
      operationId: getEventCountCollection
      x-api-path-slug: eventcount-get
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
      - Events
      - Count
  /lead/count:
    get:
      summary: COUNT for Lead
      description: Count all leads from the system
      operationId: getLeadCountCollection
      x-api-path-slug: leadcount-get
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
      - Leads
      - Count
  /meeting/count:
    get:
      summary: COUNT for Meeting
      description: Count all meetings from the system
      operationId: getMeetingCountCollection
      x-api-path-slug: meetingcount-get
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
      - Meeting
      - Count
  /note/count:
    get:
      summary: COUNT for Note
      description: Count all notes from the system
      operationId: getNoteCountCollection
      x-api-path-slug: notecount-get
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
      - Note
      - Count
  /opportunity/count:
    get:
      summary: COUNT for Opportunity
      description: Count all opportunities from the system
      operationId: getOpportunityCountCollection
      x-api-path-slug: opportunitycount-get
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
      - Opportunities
      - Count
  /task/count:
    get:
      summary: COUNT for Task
      description: Count all tasks from the system
      operationId: getTaskCountCollection
      x-api-path-slug: taskcount-get
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
      - Tasks
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