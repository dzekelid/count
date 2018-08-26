---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 0
info:
  title: Google Doubleclick API Insert Subaccount
  version: 1.0.0
  description: Inserts a new subaccount.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts:
    get:
      summary: Get Accounts
      description: Retrieves the authenticated user's list of accounts.
      operationId: adexchangebuyer.accounts.list
      x-api-path-slug: accounts-get
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Account
  /accounts/{id}:
    get:
      summary: Get Account
      description: Gets one account by ID.
      operationId: adexchangebuyer.accounts.get
      x-api-path-slug: accountsid-get
      parameters:
      - in: path
        name: id
        description: The account id
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Account
    patch:
      summary: Update Account
      description: Updates an existing account. This method supports patch semantics.
      operationId: adexchangebuyer.accounts.patch
      x-api-path-slug: accountsid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: confirmUnsafeAccountChange
        description: Confirmation for erasing bidder and cookie matching urls
      - in: path
        name: id
        description: The account id
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Account
    put:
      summary: Update Account
      description: Updates an existing account.
      operationId: adexchangebuyer.accounts.update
      x-api-path-slug: accountsid-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: confirmUnsafeAccountChange
        description: Confirmation for erasing bidder and cookie matching urls
      - in: path
        name: id
        description: The account id
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Account
  /accounts/{accountId}:
    get:
      summary: Get Account
      description: Get information about the selected Ad Exchange account.
      operationId: adexchangeseller.accounts.get
      x-api-path-slug: accountsaccountid-get
      parameters:
      - in: path
        name: accountId
        description: Account to get information about
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Account
  /userprofiles/{profileId}/accounts:
    get:
      summary: Get Accounts
      description: Retrieves the list of accounts, possibly filtered. This method
        supports paging.
      operationId: dfareporting.accounts.list
      x-api-path-slug: userprofilesprofileidaccounts-get
      parameters:
      - in: query
        name: active
        description: Select only active accounts
      - in: query
        name: ids
        description: Select only accounts with these IDs
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: pageToken
        description: Value of the nextPageToken from the previous result page
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: query
        name: searchString
        description: Allows searching for objects by name or ID
      - in: query
        name: sortField
        description: Field by which to sort the list
      - in: query
        name: sortOrder
        description: Order of sorted results, default is ASCENDING
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Account
    patch:
      summary: Update Account
      description: Updates an existing account. This method supports patch semantics.
      operationId: dfareporting.accounts.patch
      x-api-path-slug: userprofilesprofileidaccounts-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: id
        description: Account ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Account
    put:
      summary: Update Account
      description: Updates an existing account.
      operationId: dfareporting.accounts.update
      x-api-path-slug: userprofilesprofileidaccounts-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Account
  /userprofiles/{profileId}/accounts/{id}:
    get:
      summary: Get Account
      description: Gets one account by ID.
      operationId: dfareporting.accounts.get
      x-api-path-slug: userprofilesprofileidaccountsid-get
      parameters:
      - in: path
        name: id
        description: Account ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Account
  /userprofiles/{profileId}/countries:
    get:
      summary: Get Countries
      description: Retrieves a list of countries.
      operationId: dfareporting.countries.list
      x-api-path-slug: userprofilesprofileidcountries-get
      parameters:
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Country
  /userprofiles/{profileId}/countries/{dartId}:
    get:
      summary: Get Country
      description: Gets one country by ID.
      operationId: dfareporting.countries.get
      x-api-path-slug: userprofilesprofileidcountriesdartid-get
      parameters:
      - in: path
        name: dartId
        description: Country DART ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Country
  /userprofiles/{profileId}/subaccounts:
    get:
      summary: Get Subaccounts
      description: Gets a list of subaccounts, possibly filtered. This method supports
        paging.
      operationId: dfareporting.subaccounts.list
      x-api-path-slug: userprofilesprofileidsubaccounts-get
      parameters:
      - in: query
        name: ids
        description: Select only subaccounts with these IDs
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: pageToken
        description: Value of the nextPageToken from the previous result page
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: query
        name: searchString
        description: Allows searching for objects by name or ID
      - in: query
        name: sortField
        description: Field by which to sort the list
      - in: query
        name: sortOrder
        description: Order of sorted results, default is ASCENDING
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Subaccount
    patch:
      summary: Update Subaccount
      description: Updates an existing subaccount. This method supports patch semantics.
      operationId: dfareporting.subaccounts.patch
      x-api-path-slug: userprofilesprofileidsubaccounts-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: id
        description: Subaccount ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Subaccount
    post:
      summary: Insert Subaccount
      description: Inserts a new subaccount.
      operationId: dfareporting.subaccounts.insert
      x-api-path-slug: userprofilesprofileidsubaccounts-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Subaccount
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