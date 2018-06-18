---
swagger: "2.0"
x-collection-name: Google Content API for Shopping
x-complete: 0
info:
  title: Google Content API for Shopping API Update Account
  description: 'Updates a Merchant Center account. This method can only be called
    for accounts to which the managing account has access: either the managing account
    itself or sub-accounts if the managing account is a multi-client account.'
  contact:
    name: Google
    url: https://google.com
  version: v2
host: www.googleapis.com
basePath: /content/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts/batch:
    post:
      summary: Account Batch
      description: Retrieves, inserts, updates, and deletes multiple Merchant Center
        (sub-)accounts in a single request.
      operationId: content.accounts.custombatch
      x-api-path-slug: accountsbatch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      responses:
        200:
          description: OK
      tags:
      - Account
      - Batch
  /accountshipping/batch:
    post:
      summary: Account Batches
      description: Retrieves and updates the shipping settings of multiple accounts
        in a single request.
      operationId: content.accountshipping.custombatch
      x-api-path-slug: accountshippingbatch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      responses:
        200:
          description: OK
      tags:
      - Account
      - Batches
  /accountstatuses/batch:
    post:
      summary: Account Status Batch
      description: Retrieves account batch status.
      operationId: content.accountstatuses.custombatch
      x-api-path-slug: accountstatusesbatch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Account
      - Status
      - Batch
  /accounttax/batch:
    post:
      summary: Account Taxes
      description: Retrieves and updates tax settings of multiple accounts in a single
        request.
      operationId: content.accounttax.custombatch
      x-api-path-slug: accounttaxbatch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      responses:
        200:
          description: OK
      tags:
      - Account
      - Taxes
  /{merchantId}/accounts:
    get:
      summary: Get Accounts
      description: Lists the sub-accounts in your Merchant Center account. This method
        can only be called for multi-client accounts.
      operationId: content.accounts.list
      x-api-path-slug: merchantidaccounts-get
      parameters:
      - in: query
        name: maxResults
        description: The maximum number of accounts to return in the response, used
          for paging
      - in: path
        name: merchantId
        description: The ID of the managing account
      - in: query
        name: pageToken
        description: The token returned by the previous request
      responses:
        200:
          description: OK
      tags:
      - Accounts
    post:
      summary: Create Accounts
      description: Creates a Merchant Center sub-account. This method can only be
        called for multi-client accounts.
      operationId: content.accounts.insert
      x-api-path-slug: merchantidaccounts-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      - in: path
        name: merchantId
        description: The ID of the managing account
      responses:
        200:
          description: OK
      tags:
      - Accounts
  /{merchantId}/accounts/{accountId}:
    delete:
      summary: Delete Account
      description: Deletes a Merchant Center sub-account. This method can only be
        called for multi-client accounts.
      operationId: content.accounts.delete
      x-api-path-slug: merchantidaccountsaccountid-delete
      parameters:
      - in: path
        name: accountId
        description: The ID of the account
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      - in: path
        name: merchantId
        description: The ID of the managing account
      responses:
        200:
          description: OK
      tags:
      - Account
    get:
      summary: Get Account
      description: 'Retrieves a Merchant Center account. This method can only be called
        for accounts to which the managing account has access: either the managing
        account itself or sub-accounts if the managing account is a multi-client account.'
      operationId: content.accounts.get
      x-api-path-slug: merchantidaccountsaccountid-get
      parameters:
      - in: path
        name: accountId
        description: The ID of the account
      - in: path
        name: merchantId
        description: The ID of the managing account
      responses:
        200:
          description: OK
      tags:
      - Account
    patch:
      summary: Update Account
      description: 'Updates a Merchant Center account. This method can only be called
        for accounts to which the managing account has access: either the managing
        account itself or sub-accounts if the managing account is a multi-client account.
        This method supports patch semantics.'
      operationId: content.accounts.patch
      x-api-path-slug: merchantidaccountsaccountid-patch
      parameters:
      - in: path
        name: accountId
        description: The ID of the account
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      - in: path
        name: merchantId
        description: The ID of the managing account
      responses:
        200:
          description: OK
      tags:
      - Account
    put:
      summary: Update Account
      description: 'Updates a Merchant Center account. This method can only be called
        for accounts to which the managing account has access: either the managing
        account itself or sub-accounts if the managing account is a multi-client account.'
      operationId: content.accounts.update
      x-api-path-slug: merchantidaccountsaccountid-put
      parameters:
      - in: path
        name: accountId
        description: The ID of the account
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: dryRun
        description: Flag to run the request in dry-run mode
      - in: path
        name: merchantId
        description: The ID of the managing account
      responses:
        200:
          description: OK
      tags:
      - Account
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