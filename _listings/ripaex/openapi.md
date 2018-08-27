swagger: "2.0"
x-collection-name: RipaEx
x-complete: 1
info:
  title: RIPA Node Documentation
  description: this-is-a-documentation-for-ripanodehttpsgithub-comripaexripanode-built-with-swagger-ui-to-make-testing-a-breeze--if-you-find-any-issues-come-over-to-ripaexripanodetestapihttpsgithub-comripaexripanodetestapi-to-open-an-issue-or-even-better-send-a-pr-that-fixes-the-issue-the-community-ssl-public-api-used-as-test-host-is-provided-from-ripaex-iohttpswww-ripaex-io-
  version: 1.0.0
host: api.ripaex.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/accounts/count:
    get:
      summary: Accounts Count
      description: Get the count of accounts.
      operationId: accounts.count
      x-api-path-slug: apiaccountscount-get
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Accounts
      - Count
  /api/delegates/count:
    get:
      summary: Delegates Count
      description: Get the count of delegates.
      operationId: delegates.count
      x-api-path-slug: apidelegatescount-get
      parameters:
      - in: query
        name: address
        description: A valid RIPA Address
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Delegates
      - Count