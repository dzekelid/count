swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 1
info:
  title: plentymarkets REST-API
  description: the-plentymarkets-rest-api-expands-the-functionality-of-the-plentymarkets-cms-and-allows-access-to-resources-i-e--data-records-via-unique-uri-paths
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/payments/methods/hbci:
    get:
      summary: Returns the HBCI-Account count
      description: Returns the hbci-account count.
      operationId: getRestPaymentsMethodsHbci
      x-api-path-slug: restpaymentsmethodshbci-get
      responses:
        200:
          description: OK
      tags:
      - Returns
      - HBCI-Account
      - Count