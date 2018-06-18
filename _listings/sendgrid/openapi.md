---
swagger: "2.0"
x-collection-name: SendGrid
x-complete: 1
info:
  title: SendGrid
  description: the-sendgrid-web-api-v3-documentation--this-is-the-entirety-of-the-documented-v3-endpoints--we-have-updated-all-the-descriptions-parameters-requests-and-responses--authentication-every-endpoint-requires-authentication-in-the-form-of-an-authorization-header-authorization-bearer-api-key
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
  /user/account:
    get:
      summary: Get User Account
      description: |-
        **This endpoint allows you to retrieve your user account details.**

        Your user's account information includes the user's account type and reputation.

        Keeping your user profile up to date is important. This will help SendGrid to verify who you are as well as contact you should we need to.

        For more information about your user profile:

        * [SendGrid Account Settings](https://sendgrid.com/docs/User_Guide/Settings/account.html)
      operationId: user.account.get
      x-api-path-slug: useraccount-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - User
      - Account
---