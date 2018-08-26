---
name: PayRun.io
x-slug: payrun-io
description: An open, scalable, transparent and HMRC accredited payroll API. Put the
  power of payroll into your application today.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
x-kinRank: "7"
x-alexaRank: "0"
tags: Count
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/payrun-io/apis.md
specificationVersion: "0.14"
apis:
- name: Pay Run.IO Get the BankAccount schema
  x-api-slug: pay-run-io
  description: Returns the BankAccount schema object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Schemas/BankAccount.xsd
  tags: BankAccount,Schema
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/payrun-io/schemasbankaccount-xsd-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/payrun-io/schemasbankaccount-xsd-get-openapi.md
- name: Pay Run.IO Gets the bank account template
  x-api-slug: pay-run-io
  description: Return the bank account data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/bankaccount
  tags: Bank,Account,Template
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/payrun-io/templatesbankaccount-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/payrun-io/templatesbankaccount-get-openapi.md
- name: Pay Run.IO
  x-api-slug: pay-run-io
  description: An open, scalable, transparent and HMRC accredited payroll API. Put
    the power of payroll into your application today.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/payrun-io/openapi.md
x-common:
- type: x-website
  url: http://www.payrun.io
- type: x-documentation
  url: https://developer.payrun.io/docs/home/index.html
- type: x-email
  url: support@payrun.io
- type: x-email
  url: info@payrun.io
- type: x-twitter
  url: https://twitter.com/PayRun_io
- type: x-website
  url: http://api.test.payrun.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---