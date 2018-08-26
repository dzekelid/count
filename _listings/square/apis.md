---
name: Square
x-slug: square
description: Square helps millions of sellers run their business- from secure credit
  card processing to point of sale solutions. Get paid faster with Square and sign
  up today!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
x-kinRank: "9"
x-alexaRank: "2433"
tags: Count
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/square/apis.md
specificationVersion: "0.14"
apis:
- name: Square Connect API Provides non-confidential details for all of a location's
    associated bank accounts. This endpoint does not provide full bank account numbers,
    and there is no way to obtain a full bank account number with the Connect API.
  x-api-slug: square-connect-api
  description: Provides non-confidential details for all of a location's associated
    bank accounts. This endpoint does not provide full bank account numbers, and there
    is no way to obtain a full bank account number with the Connect API.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/{location_id}/bank-accounts
  tags: Provides,Non-confidential,Details,Of,Locations,Associated,Bank,Accounts,,This,Endpoint,Does,Not,Provide,Full,Bank,Account,Numbers,,There,Is,No,Way,To,Obtain,Full,Bank,Account,Number,Connect
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/square/v1location-idbankaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/square/v1location-idbankaccounts-get-openapi.md
- name: Square Connect API Provides non-confidential details for a merchant's associated
    bank account. This endpoint does not provide full bank account numbers, and there
    is no way to obtain a full bank account number with the Connect API.
  x-api-slug: square-connect-api
  description: Provides non-confidential details for a merchant's associated bank
    account. This endpoint does not provide full bank account numbers, and there is
    no way to obtain a full bank account number with the Connect API.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/{location_id}/bank-accounts/{bank_account_id}
  tags: Provides,Non-confidential,Detailsa,Merchants,Associated,Bank,Account,,This,Endpoint,Does,Not,Provide,Full,Bank,Account,Numbers,,There,Is,No,Way,To,Obtain,Full,Bank,Account,Number,Connect
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/square/v1location-idbankaccountsbank-account-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/square/v1location-idbankaccountsbank-account-id-get-openapi.md
- name: Square Connect API Lists all of a location's discounts.
  x-api-slug: square-connect-api
  description: Lists all of a location's discounts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/{location_id}/discounts
  tags: Lists,,Of,Locations,Discounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/square/v1location-iddiscounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/square/v1location-iddiscounts-get-openapi.md
- name: Square Connect API Creates a discount.
  x-api-slug: square-connect-api
  description: Creates a discount.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/{location_id}/discounts
  tags: Creates,Discount
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/square/v1location-iddiscounts-post-openapi.md
- name: Square Connect API Deletes an existing discount.
  x-api-slug: square-connect-api
  description: Deletes an existing discount.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/{location_id}/discounts/{discount_id}
  tags: S,Existing,Discount
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/square/v1location-iddiscountsdiscount-id-delete-openapi.md
- name: Square Connect API Modifies the details of an existing discount.
  x-api-slug: square-connect-api
  description: Modifies the details of an existing discount.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/{location_id}/discounts/{discount_id}
  tags: Modifies,Details,Of,Existing,Discount
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/square/v1location-iddiscountsdiscount-id-put-openapi.md
- name: Square Connect API Provides summary information for all deposits and withdrawals
    initiated by Square to a merchant's bank account during a date range. Date ranges
    cannot exceed one year in length.
  x-api-slug: square-connect-api
  description: Provides summary information for all deposits and withdrawals initiated
    by Square to a merchant's bank account during a date range. Date ranges cannot
    exceed one year in length.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/{location_id}/settlements
  tags: Provides,Summary,Information,Deposits,Withdrawals,Initiated,By,Square,To,Merchants,Bank,Account,During,Date,Range,,Date,Ranges,Cannot,Exceed,Year,In,Length
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/square/v1location-idsettlements-get-openapi.md
- name: Square Connect API
  x-api-slug: square-connect-api
  description: Square helps millions of sellers run their business- from secure credit
    card processing to point of sale solutions. Get paid faster with Square and sign
    up today!
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com//
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/square/openapi.md
x-common:
- type: x-website
  url: http://square.com
- type: x-base
  url: https://connect.squareup.com
- type: x-crunchbase
  url: http://www.crunchbase.com/company/square
- type: x-crunchbase
  url: https://crunchbase.com/organization/square
- type: x-developer
  url: https://connect.squareup.com/
- type: x-email
  url: press@squareup.com
- type: x-email
  url: security@squareup.com
- type: x-email
  url: lawenforcement@squareup.com
- type: x-email
  url: redemption@squareup.com
- type: x-email
  url: privacy@squareup.com
- type: x-email
  url: community@squareup.com
- type: x-email
  url: noreply@messaging.squareup.com
- type: x-email
  url: ir@squareup.com
- type: x-email
  url: takedowns@squareup.com
- type: x-github
  url: https://github.com/square
- type: x-linkedin
  url: https://www.linkedin.com/company/square--/
- type: x-twitter
  url: https://twitter.com/Square
- type: x-website
  url: http://squareup.com
- type: x-website
  url: https://squareup.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---