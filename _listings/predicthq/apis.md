---
name: PredictHQ
x-slug: predicthq
description: Event visibility yields higher returns & reduces operational costs. PredictHQ
  is the worlds largest source of intelligent event data making businesses smarter.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28211-developer-predicthq-com.jpg
x-kinRank: "7"
x-alexaRank: "428389"
tags: Count
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/predicthq/apis.md
specificationVersion: "0.14"
apis:
- name: PredictHQ Retrieve Account Details
  x-api-slug: predicthq
  description: If you need your account details for whatever reason, it's really easy
    to get them.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28211-developer-predicthq-com.jpg
  humanURL: http://www.predicthq.com/
  baseURL: https://api.predicthq.com////v1/accounts/self/
  tags: Accounts,Self
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/predicthq/v1accountsself-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/predicthq/v1accountsself-get-openapi.md
- name: PredictHQ Retrieve Events Count
  x-api-slug: predicthq
  description: This endpoint accepts the same parameters as the ones described in
    Retrieve All Events and can be used to get aggregated counts of all matching events
    that are available to your account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28211-developer-predicthq-com.jpg
  humanURL: http://www.predicthq.com/
  baseURL: https://api.predicthq.com////v1/events/count/
  tags: Events,Count
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/predicthq/v1eventscount-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/predicthq/v1eventscount-get-openapi.md
- name: PredictHQ
  x-api-slug: predicthq
  description: Event visibility yields higher returns & reduces operational costs.
    PredictHQ is the worlds largest source of intelligent event data making businesses
    smarter.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28211-developer-predicthq-com.jpg
  humanURL: http://www.predicthq.com/
  baseURL: https://api.predicthq.com//
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/predicthq/openapi.md
x-common:
- type: x-website
  url: http://www.predicthq.com/
- type: x-crunchbase
  url: https://crunchbase.com/organization/predicthq
- type: x-email
  url: support@predicthq.com
- type: x-email
  url: 8Bsupport@predicthq.com
- type: x-email
  url: notices@predicthq.com
- type: x-github
  url: https://github.com/predicthq
- type: x-twitter
  url: https://twitter.com/PredictHQ
- type: x-website
  url: https://developer.predicthq.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---