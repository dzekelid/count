---
name: Fire Browse Beta API
x-slug: fire-browse-beta-api
description: A simple and elegant way to explore cancer data. Sitting above one of
  the deepest and most integratively characterized open cancer datasets in the world.
  Backed by a powerful computational infrastructure, application programming interface
  (API), graphical tools and online reports. With over 80K sample aliquots from 11,000+
  cancer patients, spanning 38 unique disease cohorts.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Count
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/fire-browse-beta-api/apis.md
specificationVersion: "0.14"
apis:
- name: Fire Browse Beta API Retrieve sample counts.
  x-api-slug: fire-browse-beta-api
  description: |-
    Returns the aliquot counts for each disease cohort, per sample
    type and data type.  The sample type designation of "Tumor"
    may be used to aggregate the count of all tumor aliquots into
    a single number per disease and data type. See the SampleTypes
    function for a complete description of sample types.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1//Metadata/Counts
  tags: Metadata,Counts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/fire-browse-beta-api/metadatacounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/fire-browse-beta-api/metadatacounts-get-openapi.md
- name: Fire Browse Beta API
  x-api-slug: fire-browse-beta-api
  description: A simple and elegant way to explore cancer data. Sitting above one
    of the deepest and most integratively characterized open cancer datasets in the
    world. Backed by a powerful computational infrastructure, application programming
    interface (API), graphical tools and online reports. With over 80K sample aliquots
    from 11,000+ cancer patients, spanning 38 unique disease cohorts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/firebrowse.png
  humanURL: http://firebrowse.org
  baseURL: https://firebrowse.org//api/v1
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/fire-browse-beta-api/openapi.md
x-common:
- type: x-website
  url: http://firebrowse.org
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---