---
swagger: "2.0"
x-collection-name: Dyn
x-complete: 0
info:
  title: Dyn Retrieve Count of Email SPAM Complaints
  version: 1.0.0
  description: Retrieving a total count of Email complaints
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  opens/count:
    get:
      summary: Email Open Count
      description: Returns total number of opens for the specified account for the
        specified date range. Including a date range is highly recommended.
      operationId: getOpensCount
      x-api-path-slug: openscount-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: emailaddress
        description: Email address of recipient for filtering
      - in: query
        name: endtime
        description: Required
      - in: query
        name: sender
        description: u00a0Email address of sender for filtering
      - in: query
        name: starttime
        description: Required
      - in: query
        name: '[X-HeaderName]'
        description: Name of searchable custom X-header
      responses:
        "":
          description: ""
        apps:
          description: app_allow
        devices:
          description: device_link
        members:
          description: member_invite
        passwords:
          description: tfa_enable
        sharing:
          description: shmodel_create
        team_admin_actions:
          description: sf_external_accept_allow
        200:
          description: OK
      tags:
      - .Email
      - Open
      - Count
  reports/bounces/count:
    get:
      summary: Retrieve Count of Email Bounces
      description: Retrieving a total count of Email bounces using the API requires
        specific syntax for the REST API.
      operationId: getReportsBouncesCount
      x-api-path-slug: reportsbouncescount-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: endtime
        description: Required
      - in: query
        name: sender
        description: Email address of sender for filtering
      - in: query
        name: starttime
        description: Required
      - in: query
        name: '[X-HeaderName]'
        description: Name of searchable custom X-header
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Count
      - of
      - Email
      - Bounces
  reports/clicks/count:
    get:
      summary: Retrieve Count of Email Links Clicked
      description: Retrieving a total of Email links clicked
      operationId: getReportsClicksCount
      x-api-path-slug: reportsclickscount-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: domainu00a0
        description: Domain of the recipient, such as &#8220;gmail
      - in: query
        name: emailaddress
        description: Email address of recipient for filteringu0010
      - in: query
        name: endtime
        description: Required
      - in: query
        name: sender
        description: Email address of sender for filteringu0010
      - in: query
        name: starttime
        description: Required
      - in: query
        name: '[X-HeaderName]'
        description: Name of searchable custom X-header
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Count
      - of
      - Email
      - Links
      - Clicked
  reports/clicks/count/unique:
    get:
      summary: Retrieve Count of Email Links Clicked
      description: Retrieving a total of Email links clicked
      operationId: getReportsClicksCountUnique
      x-api-path-slug: reportsclickscountunique-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: domainu00a0
        description: Domain of the recipient, such as &#8220;gmail
      - in: query
        name: emailaddress
        description: Email address of recipient for filteringu0010
      - in: query
        name: endtime
        description: Required
      - in: query
        name: sender
        description: Email address of sender for filteringu0010
      - in: query
        name: starttime
        description: Required
      - in: query
        name: '[X-HeaderName]'
        description: Name of searchable custom X-header
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Count
      - of
      - Email
      - Links
      - Clicked
  reports/complaints/count:
    get:
      summary: Retrieve Count of Email SPAM Complaints
      description: Retrieving a total count of Email complaints
      operationId: getReportsComplaintsCount
      x-api-path-slug: reportscomplaintscount-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: endtime
        description: Required
      - in: query
        name: starttime
        description: Required
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Count
      - of
      - Email
      - SPAM
      - Complaints
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