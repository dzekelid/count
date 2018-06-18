---
name: Google Doubleclick
x-slug: google-doubleclick
description: The Ad Exchange Buyer REST API allows your Real-Time Bidding application
  to access and update account information and to submit creatives. The API also allows
  an application (whether it does static bidding or real-time bidding) to discover
  direct deals that sellers make available.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Count
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-doubleclick/apis.md
specificationVersion: "0.14"
apis:
- name: Google Doubleclick API Get Accounts
  x-api-slug: google-doubleclick-api
  description: Retrieves the authenticated user's list of accounts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///accounts
  tags: Advertising,Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-doubleclick/accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-doubleclick/accounts-get-openapi.md
- name: Google Doubleclick API Get Account
  x-api-slug: google-doubleclick-api
  description: Gets one account by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///accounts/{id}
  tags: Advertising,Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-doubleclick/accountsid-get-openapi.md
- name: Google Doubleclick API Update Account
  x-api-slug: google-doubleclick-api
  description: Updates an existing account. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///accounts/{id}
  tags: Advertising,Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-doubleclick/accountsid-patch-openapi.md
- name: Google Doubleclick API Update Account
  x-api-slug: google-doubleclick-api
  description: Updates an existing account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///accounts/{id}
  tags: Advertising,Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-doubleclick/accountsid-put-openapi.md
- name: Google Doubleclick API Get Account
  x-api-slug: google-doubleclick-api
  description: Get information about the selected Ad Exchange account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///accounts/{accountId}
  tags: Advertising,Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-doubleclick/accountsaccountid-get-openapi.md
- name: Google Doubleclick API Get Accounts
  x-api-slug: google-doubleclick-api
  description: Retrieves the list of accounts, possibly filtered. This method supports
    paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/accounts
  tags: Advertising,Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-doubleclick/userprofilesprofileidaccounts-get-openapi.md
- name: Google Doubleclick API Update Account
  x-api-slug: google-doubleclick-api
  description: Updates an existing account. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/accounts
  tags: Advertising,Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-doubleclick/userprofilesprofileidaccounts-patch-openapi.md
- name: Google Doubleclick API Update Account
  x-api-slug: google-doubleclick-api
  description: Updates an existing account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/accounts
  tags: Advertising,Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-doubleclick/userprofilesprofileidaccounts-put-openapi.md
- name: Google Doubleclick API Get Account
  x-api-slug: google-doubleclick-api
  description: Gets one account by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/accounts/{id}
  tags: Advertising,Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-doubleclick/userprofilesprofileidaccountsid-get-openapi.md
- name: Google Doubleclick API Get Countries
  x-api-slug: google-doubleclick-api
  description: Retrieves a list of countries.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/countries
  tags: Advertising,Country
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-doubleclick/userprofilesprofileidcountries-get-openapi.md
- name: Google Doubleclick API Get Country
  x-api-slug: google-doubleclick-api
  description: Gets one country by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/countries/{dartId}
  tags: Advertising,Country
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-doubleclick/userprofilesprofileidcountriesdartid-get-openapi.md
- name: Google Doubleclick API Get Subaccounts
  x-api-slug: google-doubleclick-api
  description: Gets a list of subaccounts, possibly filtered. This method supports
    paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/subaccounts
  tags: Advertising,Subaccount
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-doubleclick/userprofilesprofileidsubaccounts-get-openapi.md
- name: Google Doubleclick API Update Subaccount
  x-api-slug: google-doubleclick-api
  description: Updates an existing subaccount. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/subaccounts
  tags: Advertising,Subaccount
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-doubleclick/userprofilesprofileidsubaccounts-patch-openapi.md
- name: Google Doubleclick API Insert Subaccount
  x-api-slug: google-doubleclick-api
  description: Inserts a new subaccount.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/subaccounts
  tags: Advertising,Subaccount
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-doubleclick/userprofilesprofileidsubaccounts-post-openapi.md
- name: Google Doubleclick API Update Subaccount
  x-api-slug: google-doubleclick-api
  description: Updates an existing subaccount.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/subaccounts
  tags: Advertising,Subaccount
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-doubleclick/userprofilesprofileidsubaccounts-put-openapi.md
- name: Google Doubleclick API Get Subaccount
  x-api-slug: google-doubleclick-api
  description: Gets one subaccount by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/subaccounts/{id}
  tags: Advertising,Subaccount
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-doubleclick/userprofilesprofileidsubaccountsid-get-openapi.md
- name: Google Doubleclick API
  x-api-slug: google-doubleclick-api
  description: The Ad Exchange Buyer REST API allows your Real-Time Bidding application
    to access and update account information and to submit creatives. The API also
    allows an application (whether it does static bidding or real-time bidding) to
    discover direct deals that sellers make available.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/google-doubleclick/openapi.md
x-common:
- type: x-authentication
  url: https://developers.google.com/ad-exchange/buyer-rest/auth-guide
- type: x-blog
  url: http://googleadsdeveloper.blogspot.com/search/label/ad_exchange
- type: x-blog-rss
  url: http://googleadsdeveloper.blogspot.com/feeds/posts/default?alt=rss
- type: x-developer
  url: https://developers.google.com/ad-exchange/buyer-rest/
- type: x-forum
  url: https://groups.google.com/forum/#!forum/google-doubleclick-ad-exchange-buyer-api
- type: x-getting-started
  url: https://developers.google.com/ad-exchange/buyer-rest/start
- type: x-support
  url: https://developers.google.com/ad-exchange/buyer-rest/community/
- type: x-website
  url: https://www.doubleclickbygoogle.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---