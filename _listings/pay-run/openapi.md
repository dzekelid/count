---
swagger: "2.0"
x-collection-name: Pay Run
x-complete: 1
info:
  title: Pay Run.IO
  description: open-scableable-transparent-payroll-api-
  version: 17.18.6.206
host: api.test.payrun.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Schemas/BankAccount.xsd:
    get:
      summary: Get the BankAccount schema
      description: Returns the BankAccount schema object
      operationId: GetBankAccountSchema
      x-api-path-slug: schemasbankaccount-xsd-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - BankAccount
      - Schema
  /Templates/bankaccount:
    get:
      summary: Gets the bank account template
      description: Return the bank account data object template
      operationId: GetBankAccountTemplate
      x-api-path-slug: templatesbankaccount-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      responses:
        200:
          description: OK
      tags:
      - Bank
      - Account
      - Template
---