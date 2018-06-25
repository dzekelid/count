---
name: Google Play
x-slug: google-play
description: 'The Google Play Developer API allows you to perform a number of publishing
  and app-management tasks. It includes two components: The Subscriptions and In-App
  Purchases API lets you manage in-app purchases and subscriptions. The Publishing
  API lets you upload and publish apps, and perform other publishing-related tasks.'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Count
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-play/apis.md
specificationVersion: "0.14"
apis:
- name: Google Play Return Service Account
  x-api-slug: google-play
  description: |-
    Returns a service account and credentials. The service account can be bound to the enterprise by calling setAccount. The service account is unique to this enterprise and EMM, and will be deleted if the enterprise is unbound. The credentials contain private key data and are not stored server-side.

    This method can only be called after calling Enterprises.Enroll or Enterprises.CompleteSignup, and before Enterprises.SetAccount; at other times it will return an error.

    Subsequent calls after the first will generate a new, unique set of credentials, and invalidate the previously generated credentials.

    Once the service account is bound to the enterprise, it can be managed using the serviceAccountKeys resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https://///enterprises/{enterpriseId}/serviceAccount
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-play/enterprisesenterpriseidserviceaccount-get-openapi.md
- name: Google Play Get Video Country
  x-api-slug: google-play
  description: |-
    Get a StoreInfo given its video id and country.

    See _Authentication and Authorization rules_ and
    _Get methods rules_ for more information about this method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https://///v1/accounts/{accountId}/storeInfos/{videoId}/country/{country}
  tags: Country
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-play/v1accountsaccountidstoreinfosvideoidcountrycountry-get-openapi.md
- name: Google Play
  x-api-slug: google-play
  description: 'The Google Play Developer API allows you to perform a number of publishing
    and app-management tasks. It includes two components: The Subscriptions and In-App
    Purchases API lets you manage in-app purchases and subscriptions. The Publishing
    API lets you upload and publish apps, and perform other publishing-related tasks.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-play.png
  humanURL: https://play.google.com/store
  baseURL: https:///
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-play/openapi.md
x-common:
- type: x-blog
  url: https://blog.google/products/google-play/
- type: x-blog-rss
  url: https://blog.google/products/google-play/rss
- type: x-developer
  url: https://developers.google.com/android-publisher/
- type: x-facebook
  url: https://www.facebook.com/GooglePlay
- type: x-getting-started
  url: https://developers.google.com/android-publisher/getting_started
- type: x-twitter
  url: https://twitter.com/GooglePlay
- type: x-website
  url: https://play.google.com/store
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---