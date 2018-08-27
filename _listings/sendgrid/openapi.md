swagger: "2.0"
x-collection-name: SendGrid
x-complete: 1
info:
  title: SendGrid
  version: 1.0.0
host: api.sendgrid.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /contactdb/recipients/billable_count:
    get:
      summary: Get Contactdb Recipients Billable Count
      description: |-
        **This endpoint allows you to retrieve the number of Marketing Campaigns recipients that you will be billed for.**

        You are billed for marketing campaigns based on the highest number of recipients you have had in your account at one time. This endpoint will allow you to know the current billable count value.

        The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.
      operationId: contactdb.recipients.billable_count.get
      x-api-path-slug: contactdbrecipientsbillable-count-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Contactdb
      - Recipients
      - Billable
      - Count
  /contactdb/recipients/count:
    get:
      summary: Get Contactdb Recipients Count
      description: |-
        **This endpoint allows you to retrieve the total number of Marketing Campaigns recipients.**

        The contactdb is a database of your contacts for [SendGrid Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html).
      operationId: contactdb.recipients.count.get
      x-api-path-slug: contactdbrecipientscount-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Contactdb
      - Recipients
      - Count