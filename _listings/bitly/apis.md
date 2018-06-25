---
name: Bitly
x-slug: bitly
description: Get the most out of your social and online marketing efforts. Own, understand
  and activate your best audience through the power of the link with Bitly Enterprise.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1503-bitly.jpg
x-kinRank: "8"
x-alexaRank: "737"
tags: Count
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/bitly/apis.md
specificationVersion: "0.14"
apis:
- name: Bitly Domains API Get Link Countries
  x-api-slug: bitly-domains-api
  description: Returns metrics about the countries referring click traffic to a single
    bitly link.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1503-bitly.jpg
  humanURL: http://bitly.com
  baseURL: https://api-ssl.bitly.com////v3/link/countries
  tags: Link,Countries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/bitly/v3linkcountries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/bitly/v3linkcountries-get-openapi.md
- name: Bitly Domains API
  x-api-slug: bitly-domains-api
  description: Get the most out of your social and online marketing efforts. Own,
    understand and activate your best audience through the power of the link with
    Bitly Enterprise.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1503-bitly.jpg
  humanURL: http://bitly.com
  baseURL: https://api-ssl.bitly.com//
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/bitly/openapi.md
- name: Bitly Link Metrics API Link Clicks by Country
  x-api-slug: bitly-link-metrics-api
  description: Returns metrics about the countries referring click traffic to a single
    Bitlink.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1503-bitly.jpg
  humanURL: http://bitly.com
  baseURL: https://api-ssl.bitly.com//v3//link/countries
  tags: Link,Countries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/bitly/linkcountries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/bitly/linkcountries-get-openapi.md
- name: Bitly Link Metrics API Users Who Encoded Link
  x-api-slug: bitly-link-metrics-api
  description: Returns users who have encoded this link (optionally only those in
    the requesting users social graph), sorted by the number of clicks on each encoding
    users link.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1503-bitly.jpg
  humanURL: http://bitly.com
  baseURL: https://api-ssl.bitly.com//v3//link/encoders_by_count
  tags: Link,Encoders,By,Count
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/bitly/linkencoders-by-count-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/bitly/linkencoders-by-count-get-openapi.md
- name: Bitly Link Metrics API Number of Encoders
  x-api-slug: bitly-link-metrics-api
  description: Returns the number of users who have shortened (encoded) a single Bitlink.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1503-bitly.jpg
  humanURL: http://bitly.com
  baseURL: https://api-ssl.bitly.com//v3//link/encoders_count
  tags: Link,Encoders,Count
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/bitly/linkencoders-count-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/bitly/linkencoders-count-get-openapi.md
- name: Bitly Link Metrics API
  x-api-slug: bitly-link-metrics-api
  description: Get the most out of your social and online marketing efforts. Own,
    understand and activate your best audience through the power of the link with
    Bitly Enterprise.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1503-bitly.jpg
  humanURL: http://bitly.com
  baseURL: https://api-ssl.bitly.com//v3
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/bitly/openapi.md
- name: Bitly Organization Metric API Organization Shorten Counts
  x-api-slug: bitly-organization-metric-api
  description: Returns the number of Bitlinks created by your organization or by other
    Bitly users that point to your domains.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1503-bitly.jpg
  humanURL: http://bitly.com
  baseURL: https://api-ssl.bitly.com//v3//v3/organization/shorten_counts
  tags: Organization,Shorten,Counts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/bitly/v3organizationshorten-counts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/bitly/v3organizationshorten-counts-get-openapi.md
- name: Bitly Organization Metric API
  x-api-slug: bitly-organization-metric-api
  description: Get the most out of your social and online marketing efforts. Own,
    understand and activate your best audience through the power of the link with
    Bitly Enterprise.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1503-bitly.jpg
  humanURL: http://bitly.com
  baseURL: https://api-ssl.bitly.com//v3
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/bitly/openapi.md
- name: Bitly User Metrics API User Countries
  x-api-slug: bitly-user-metrics-api
  description: Returns aggregate metrics about the countries referring click traffic
    to all of the authenticated users Bitlinks.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1503-bitly.jpg
  humanURL: http://bitly.com
  baseURL: https://api-ssl.bitly.com//v3//v3/user/countries
  tags: User,Countries
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/bitly/v3usercountries-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/bitly/v3usercountries-get-openapi.md
- name: Bitly User Metrics API User Shorten Counts
  x-api-slug: bitly-user-metrics-api
  description: Returns the number of Bitlinks created in a given time period by the
    authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1503-bitly.jpg
  humanURL: http://bitly.com
  baseURL: https://api-ssl.bitly.com//v3//v3/user/shorten_counts
  tags: User,Shorten,Counts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/bitly/v3usershorten-counts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/bitly/v3usershorten-counts-get-openapi.md
- name: Bitly User Metrics API
  x-api-slug: bitly-user-metrics-api
  description: Get the most out of your social and online marketing efforts. Own,
    understand and activate your best audience through the power of the link with
    Bitly Enterprise.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1503-bitly.jpg
  humanURL: http://bitly.com
  baseURL: https://api-ssl.bitly.com//v3
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/bitly/openapi.md
x-common:
- type: x--net-library
  url: http://code.google.com/p/bitly-dot-net
- type: x-application-management
  url: http://dev.bitly.com/my_apps.html
- type: x-base
  url: http://api.bitly.com
- type: x-best-practices
  url: http://dev.bitly.com/best_practices.html
- type: x-blog
  url: http://word.bitly.com/
- type: x-blog-rss
  url: http://word.bitly.com/rss
- type: x-crunchbase
  url: http://www.crunchbase.com/company/bit-ly
- type: x-crunchbase
  url: https://crunchbase.com/organization/hootsuite
- type: x-crunchbase
  url: https://crunchbase.com/organization/bitly
- type: x-developer
  url: http://data.info.yorku.ca/
- type: x-email
  url: media@hootsuite.com
- type: x-email
  url: legal@hootsuite.com
- type: x-email
  url: privacy@hootsuite.com
- type: x-email
  url: hootsuite-dpa@hootsuite.com
- type: x-email
  url: security@hootsuite.com
- type: x-email
  url: app.directory@hootsuite.com
- type: x-email
  url: apis@hootsuite.com
- type: x-email
  url: partnersupport@hootsuite.com
- type: x-email
  url: partners@bitly.com
- type: x-email
  url: press@bitly.com
- type: x-email
  url: office@bitly.com
- type: x-email
  url: support@bitly.com
- type: x-email
  url: api@bitly.com
- type: x-forum
  url: http://dev.bitly.com/api_discussion_group.html
- type: x-github
  url: https://github.com/bitly
- type: x-java-library
  url: https://github.com/stackmagic/bitly-api-client
- type: x-javascript-library
  url: https://npmjs.org/package/node-bitlyapi
- type: x-partners
  url: https://bitly.com/pages/partners
- type: x-php-library
  url: http://github.com/Falicon/BitlyPHP
- type: x-privacy
  url: https://bitly.com/pages/privacy
- type: x-python-library
  url: http://github.com/bitly/bitly-api-python
- type: x-ruby-library
  url: http://github.com/nas/url_shortener
- type: x-sdks-io
  url: https://sdks.io/SDK/View/bitly-13
- type: x-support
  url: http://support.bitly.com/
- type: x-temboo-pdk
  url: https://live.temboo.com/library/Library/Bitly/
- type: x-terms-of-service
  url: https://bitly.com/pages/terms-of-service
- type: x-twitter
  url: https://twitter.com/Bitly
- type: x-twitter
  url: https://twitter.com/hootsuite
- type: x-website
  url: http://bitly.com
- type: x-website
  url: http://dev.bitly.com/data_apis.html
- type: x-website
  url: http://bit.ly/1j56kms
- type: x-website
  url: http://hootsuite.com
- type: x-website
  url: http://bit.ly
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---