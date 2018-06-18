---
swagger: "2.0"
x-collection-name: Google Play
x-complete: 0
info:
  title: Google Play Get Video Country
  version: 1.0.0
  description: |-
    Get a StoreInfo given its video id and country.

    See _Authentication and Authorization rules_ and
    _Get methods rules_ for more information about this method.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /enterprises/{enterpriseId}/serviceAccount:
    get:
      summary: Return Service Account
      description: |-
        Returns a service account and credentials. The service account can be bound to the enterprise by calling setAccount. The service account is unique to this enterprise and EMM, and will be deleted if the enterprise is unbound. The credentials contain private key data and are not stored server-side.

        This method can only be called after calling Enterprises.Enroll or Enterprises.CompleteSignup, and before Enterprises.SetAccount; at other times it will return an error.

        Subsequent calls after the first will generate a new, unique set of credentials, and invalidate the previously generated credentials.

        Once the service account is bound to the enterprise, it can be managed using the serviceAccountKeys resource.
      operationId: androidenterprise.enterprises.getServiceAccount
      x-api-path-slug: enterprisesenterpriseidserviceaccount-get
      parameters:
      - in: path
        name: enterpriseId
        description: The ID of the enterprise
      - in: query
        name: keyType
        description: The type of credential to return with the service account
      responses:
        200:
          description: OK
      tags:
      - Account
  /v1/accounts/{accountId}/storeInfos/{videoId}/country/{country}:
    get:
      summary: Get Video Country
      description: |-
        Get a StoreInfo given its video id and country.

        See _Authentication and Authorization rules_ and
        _Get methods rules_ for more information about this method.
      operationId: playmoviespartner.accounts.storeInfos.country.get
      x-api-path-slug: v1accountsaccountidstoreinfosvideoidcountrycountry-get
      parameters:
      - in: path
        name: accountId
        description: REQUIRED
      - in: path
        name: country
        description: REQUIRED
      - in: path
        name: videoId
        description: REQUIRED
      responses:
        200:
          description: OK
      tags:
      - Country
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