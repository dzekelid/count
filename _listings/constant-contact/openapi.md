---
swagger: "2.0"
x-collection-name: Constant Contact
x-complete: 1
info:
  title: Constant Contact
  description: make-constant-contacts-leading-email-and-event-marketing-services-accessible-directly-from-your-app-
  version: 1.0.0
host: api.constantcontact.com
basePath: /ws/customers/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{username}/settings/emailaddresses:
    get:
      summary: List Account Email Addresses
      description: List Account Email Addresses
      operationId: list-account-email-addresses
      x-api-path-slug: usernamesettingsemailaddresses-get
      parameters:
      - in: path
        name: username
      responses:
        200:
          description: OK
      tags:
      - List
      - Account
      - Email
      - Resses
---