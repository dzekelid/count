---
name: Jumpseller
x-slug: jumpseller
description: We founded Jumpseller.com in 2009 in Europe  we called it Vendder back
  then  and released our first version of the Jumpseller product in September 2010.
  After releasing the product we quickly grew to thousands of customers. In November
  2010, we recei...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
x-kinRank: "7"
x-alexaRank: "153745"
tags: Count
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/apis.md
specificationVersion: "0.14"
apis:
- name: Jumpseller Get Countries
  x-api-slug: jumpseller
  description: Retrieve all countries..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//countries.json
  tags: Countries,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/countries-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/countries-json-get-openapi.md
- name: Jumpseller Get Countries Country Code
  x-api-slug: jumpseller
  description: Retrieve a single country information..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//countries/{country_code}.json
  tags: Countries,Country,Code,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/countriescountry-code-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/countriescountry-code-json-get-openapi.md
- name: Jumpseller Get Countries Country Code Regions
  x-api-slug: jumpseller
  description: Retrieve all regions from a single country..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//countries/{country_code}/regions.json
  tags: Countries,Country,Code,Regions,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/countriescountry-coderegions-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/countriescountry-coderegions-json-get-openapi.md
- name: Jumpseller Get Countries Country Code Regions Region Code
  x-api-slug: jumpseller
  description: Retrieve a single region information object..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//countries/{country_code}/regions/{region_code}.json
  tags: Countries,Country,Code,Regions,Region,Code,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/countriescountry-coderegionsregion-code-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/countriescountry-coderegionsregion-code-json-get-openapi.md
- name: Jumpseller Get Products Category Category Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/category/{category_id}/count.json
  tags: Products,Category,Category,Id,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/productscategorycategory-idcount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/productscategorycategory-idcount-json-get-openapi.md
- name: Jumpseller Get Products Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/count.json
  tags: Products,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/productscount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/productscount-json-get-openapi.md
- name: Jumpseller Get Products Status Status Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/status/{status}/count.json
  tags: Products,Status,Status,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/productsstatusstatuscount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/productsstatusstatuscount-json-get-openapi.md
- name: Jumpseller Get Products Fields Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/fields/count.json
  tags: Products,Id,Fields,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/productsidfieldscount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/productsidfieldscount-json-get-openapi.md
- name: Jumpseller Get Products Images Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/images/count.json
  tags: Products,Id,Images,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/productsidimagescount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/productsidimagescount-json-get-openapi.md
- name: Jumpseller Get Products Options Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/count.json
  tags: Products,Id,Options,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/productsidoptionscount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/productsidoptionscount-json-get-openapi.md
- name: Jumpseller Get Products Options Option Values Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/options/{option_id}/values/count.json
  tags: Products,Id,Options,Option,Id,Values,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/productsidoptionsoption-idvaluescount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/productsidoptionsoption-idvaluescount-json-get-openapi.md
- name: Jumpseller Get Products Variants Count
  x-api-slug: jumpseller
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1//products/{id}/variants/count.json
  tags: Products,Id,Variants,Count,Json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/productsidvariantscount-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/productsidvariantscount-json-get-openapi.md
- name: Jumpseller
  x-api-slug: jumpseller
  description: We founded Jumpseller.com in 2009 in Europe  we called it Vendder back
    then  and released our first version of the Jumpseller product in September 2010.
    After releasing the product we quickly grew to thousands of customers. In November
    2010, we recei...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28432-jumpseller-api.jpg
  humanURL: http://jumpseller.com
  baseURL: https://api.jumpseller.com//v1
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/jumpseller/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/vendder
- type: x-email
  url: info@jumpseller.com
- type: x-email
  url: support@jumpseller.com
- type: x-twitter
  url: https://twitter.com/Jumpseller
- type: x-website
  url: http://jumpseller.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---