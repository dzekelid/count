---
swagger: "2.0"
x-collection-name: Square
x-complete: 1
info:
  title: Square Connect
  description: client-library-for-accessing-the-square-connect-apis
  termsOfService: https://connect.squareup.com/tos
  contact:
    name: Square Developer Platform
    url: https://squareup.com/developers
    email: developers@squareup.com
  version: "2.0"
host: connect.squareup.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/{location_id}/bank-accounts:
    get:
      summary: Provides non-confidential details for all of a location's associated
        bank accounts. This endpoint does not provide full bank account numbers, and
        there is no way to obtain a full bank account number with the Connect API.
      description: Provides non-confidential details for all of a location's associated
        bank accounts. This endpoint does not provide full bank account numbers, and
        there is no way to obtain a full bank account number with the Connect API.
      operationId: ListBankAccounts
      x-api-path-slug: v1location-idbankaccounts-get
      parameters:
      - in: path
        name: location_id
        description: The ID of the location to list bank accounts for
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Non-confidential
      - Details
      - Of
      - Locations
      - Associated
      - Bank
      - Accounts
      - ""
      - This
      - Endpoint
      - Does
      - Not
      - Provide
      - Full
      - Bank
      - Account
      - Numbers
      - ""
      - There
      - Is
      - "No"
      - Way
      - To
      - Obtain
      - Full
      - Bank
      - Account
      - Number
      - Connect
  /v1/{location_id}/bank-accounts/{bank_account_id}:
    get:
      summary: Provides non-confidential details for a merchant's associated bank
        account. This endpoint does not provide full bank account numbers, and there
        is no way to obtain a full bank account number with the Connect API.
      description: Provides non-confidential details for a merchant's associated bank
        account. This endpoint does not provide full bank account numbers, and there
        is no way to obtain a full bank account number with the Connect API.
      operationId: RetrieveBankAccount
      x-api-path-slug: v1location-idbankaccountsbank-account-id-get
      parameters:
      - in: path
        name: bank_account_id
        description: The bank accounts Square-issued ID
      - in: path
        name: location_id
        description: The ID of the bank accounts associated location
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Non-confidential
      - Detailsa
      - Merchants
      - Associated
      - Bank
      - Account
      - ""
      - This
      - Endpoint
      - Does
      - Not
      - Provide
      - Full
      - Bank
      - Account
      - Numbers
      - ""
      - There
      - Is
      - "No"
      - Way
      - To
      - Obtain
      - Full
      - Bank
      - Account
      - Number
      - Connect
  /v1/{location_id}/discounts:
    get:
      summary: Lists all of a location's discounts.
      description: Lists all of a location's discounts.
      operationId: ListDiscounts
      x-api-path-slug: v1location-iddiscounts-get
      parameters:
      - in: path
        name: location_id
        description: The ID of the location to list categories for
      responses:
        200:
          description: OK
      tags:
      - Lists
      - ""
      - Of
      - Locations
      - Discounts
    post:
      summary: Creates a discount.
      description: Creates a discount.
      operationId: CreateDiscount
      x-api-path-slug: v1location-iddiscounts-post
      parameters:
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: location_id
        description: The ID of the location to create an item for
      responses:
        200:
          description: OK
      tags:
      - Creates
      - Discount
  /v1/{location_id}/discounts/{discount_id}:
    delete:
      summary: Deletes an existing discount.
      description: Deletes an existing discount.
      operationId: DeleteDiscount
      x-api-path-slug: v1location-iddiscountsdiscount-id-delete
      parameters:
      - in: path
        name: discount_id
        description: The ID of the discount to delete
      - in: path
        name: location_id
        description: The ID of the items associated location
      responses:
        200:
          description: OK
      tags:
      - S
      - Existing
      - Discount
    put:
      summary: Modifies the details of an existing discount.
      description: Modifies the details of an existing discount.
      operationId: UpdateDiscount
      x-api-path-slug: v1location-iddiscountsdiscount-id-put
      parameters:
      - in: body
        name: body
        description: An object containing the fields to POST for the request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: discount_id
        description: The ID of the discount to edit
      - in: path
        name: location_id
        description: The ID of the categorys associated location
      responses:
        200:
          description: OK
      tags:
      - Modifies
      - Details
      - Of
      - Existing
      - Discount
  /v1/{location_id}/settlements:
    get:
      summary: Provides summary information for all deposits and withdrawals initiated
        by Square to a merchant's bank account during a date range. Date ranges cannot
        exceed one year in length.
      description: Provides summary information for all deposits and withdrawals initiated
        by Square to a merchant's bank account during a date range. Date ranges cannot
        exceed one year in length.
      operationId: ListSettlements
      x-api-path-slug: v1location-idsettlements-get
      parameters:
      - in: query
        name: batch_token
        description: A pagination cursor to retrieve the next set of results for youroriginal
          query to the endpoint
      - in: query
        name: begin_time
        description: The beginning of the requested reporting period, in ISO 8601
          format
      - in: query
        name: end_time
        description: The end of the requested reporting period, in ISO 8601 format
      - in: query
        name: limit
        description: The maximum number of payments to return in a single response
      - in: path
        name: location_id
        description: The ID of the location to list settlements for
      - in: query
        name: order
        description: TThe order in which payments are listed in the response
      - in: query
        name: status
        description: Provide this parameter to retrieve only settlements with a particular
          status (SENT or FAILED)
      responses:
        200:
          description: OK
      tags:
      - Provides
      - Summary
      - Information
      - Deposits
      - Withdrawals
      - Initiated
      - By
      - Square
      - To
      - Merchants
      - Bank
      - Account
      - During
      - Date
      - Range
      - ""
      - Date
      - Ranges
      - Cannot
      - Exceed
      - Year
      - In
      - Length
---