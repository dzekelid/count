---
swagger: "2.0"
x-collection-name: 3scale
x-complete: 1
info:
  title: 3Scale Billing API
  description: the-api-for-managing-3scale-billing
  termsOfService: http://www.3scale.net/terms-and-conditions/
  contact:
    name: 3Scale
    url: https://support.3scale.net/
  version: "1"
host: su1.3scale.net
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/accounts/{account_id}/invoices.xml:
    get:
      summary: Invoice List by Account
      description: Invoice list by account.
      operationId: finance
      x-api-path-slug: apiaccountsaccount-idinvoices-xml-get
      parameters:
      - in: path
        name: account_id
        description: id of the account
      - in: query
        name: month
        description: Filter the invoice by month
      - in: query
        name: page
        description: Page in the paginated list
      - in: query
        name: per_page
        description: Number of results per page
      - in: query
        name: provider_key
        description: Your api key with 3scale
      - in: query
        name: state
        description: Filter the invoice by state
      responses:
        200:
          description: OK
      tags:
      - Invoice
      - List
      - By
      - Account
  /api/accounts/{account_id}/invoices/{id}.xml:
    get:
      summary: Invoice by Account
      description: Invoice by account.
      operationId: finance
      x-api-path-slug: apiaccountsaccount-idinvoicesid-xml-get
      parameters:
      - in: path
        name: account_id
        description: id of the account
      - in: path
        name: id
        description: id of the invoice
      - in: query
        name: provider_key
        description: Your api key with 3scale
      responses:
        200:
          description: OK
      tags:
      - Invoice
      - By
      - Account
---