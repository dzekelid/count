---
name: Plivo
x-slug: plivo
description: 'Voice & SMS API Platform: Plivo enables businesses and developers to
  tap into powerful Voice and SMS capabilities without carrier lock-in.'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
x-kinRank: "8"
x-alexaRank: "130970"
tags: Count
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/plivo/apis.md
specificationVersion: "0.14"
apis:
- name: Codenvy Account API Get Account
  x-api-slug: codenvy-account-api
  description: This API call returns a JSON with all user membership in a single or
    multiple accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//account
  tags: Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/plivo/account-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/plivo/account-get-openapi.md
- name: Codenvy Account API Post Account
  x-api-slug: codenvy-account-api
  description: Create a new account
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//account
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/plivo/account-post-openapi.md
- name: Codenvy Account API Get Account Find
  x-api-slug: codenvy-account-api
  description: Get account information by its name. JSON with account details is returned.
    This API call requires system/admin or system/manager role.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//account/find
  tags: Account,Find
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/plivo/accountfind-get-openapi.md
- name: Codenvy Account API Get Account Memberships
  x-api-slug: codenvy-account-api
  description: ID of a user should be specified as a query parameter. JSON with membership
    details is returned. For this API call system/admin or system/manager role is
    required
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//account/memberships
  tags: Account,Memberships
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/plivo/accountmemberships-get-openapi.md
- name: Codenvy Account API Post Account Subscriptions
  x-api-slug: codenvy-account-api
  description: 'Add a new subscription to an account. JSON with subscription details
    is sent. Roles: account/owner, system/admin.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//account/subscriptions
  tags: Account,Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/plivo/accountsubscriptions-post-openapi.md
- name: Codenvy Account API Delete Account Subscriptions Subscriptionid
  x-api-slug: codenvy-account-api
  description: 'Remove subscription from account. Roles: account/owner, system/admin.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//account/subscriptions/{subscriptionId}
  tags: Account,Subscriptions,SubscriptionId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/plivo/accountsubscriptionssubscriptionid-delete-openapi.md
- name: Codenvy Account API Get Account Subscriptions Subscriptionid
  x-api-slug: codenvy-account-api
  description: Get information on a particular subscription by its unique ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//account/subscriptions/{subscriptionId}
  tags: Account,Subscriptions,SubscriptionId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/plivo/accountsubscriptionssubscriptionid-get-openapi.md
- name: Codenvy Account API Get Account Accountid Subscriptions
  x-api-slug: codenvy-account-api
  description: Get information on account subscriptions. This API call requires account/owner,
    account/member, system/admin or system/manager role.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//account/{accountId}/subscriptions
  tags: Account,AccountId,Subscriptions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/plivo/accountaccountidsubscriptions-get-openapi.md
- name: Codenvy Account API Delete Account
  x-api-slug: codenvy-account-api
  description: Remove subscription from account. JSON with subscription details is
    sent. Can be performed only by system/admin.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//account/{id}
  tags: Account,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/plivo/accountid-delete-openapi.md
- name: Codenvy Account API Get Account
  x-api-slug: codenvy-account-api
  description: Get account information by its ID. JSON with account details is returned.
    This API call requires account/owner, system/admin or system/manager role.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//account/{id}
  tags: Account,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/plivo/accountid-get-openapi.md
- name: Codenvy Account API Post Account
  x-api-slug: codenvy-account-api
  description: Update account. This API call requires account/owner role.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//account/{id}
  tags: Account,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/plivo/accountid-post-openapi.md
- name: Codenvy Account API Delete Account Attribute
  x-api-slug: codenvy-account-api
  description: Remove attribute from an account. Attribute name is used as a quary
    parameter. For this API request account/owner, system/admin or system/manager
    role is required
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//account/{id}/attribute
  tags: Account,Id,Attribute
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/plivo/accountidattribute-delete-openapi.md
- name: Codenvy Account API Get Account Members
  x-api-slug: codenvy-account-api
  description: Get all members for a specific account. This API call requires account/owner,
    system/admin or system/manager role.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//account/{id}/members
  tags: Account,Id,Members
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/plivo/accountidmembers-get-openapi.md
- name: Codenvy Account API Post Account Members
  x-api-slug: codenvy-account-api
  description: Add a new user to an account. This user will have account/member role.
    This API call requires account/owner, system/admin or system/manager role.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//account/{id}/members
  tags: Account,Id,Members
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/plivo/accountidmembers-post-openapi.md
- name: Codenvy Account API Delete Account Members User
  x-api-slug: codenvy-account-api
  description: Remove user from a specific account. This API call requires account/owner,
    system/admin or system/manager role.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//account/{id}/members/{userid}
  tags: Account,Id,Members,Userid
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/plivo/accountidmembersuserid-delete-openapi.md
- name: Codenvy Account API Get Account Resources
  x-api-slug: codenvy-account-api
  description: 'Returns used resources, provided by subscriptions. Roles: account/owner,
    account/member, system/manager, system/admin.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//account/{id}/resources
  tags: Account,Id,Resources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/plivo/accountidresources-get-openapi.md
- name: Codenvy Account API Post Account Resources
  x-api-slug: codenvy-account-api
  description: 'Redistributes resources between workspaces. Roles: account/owner,
    system/manager, system/admin.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api//account/{id}/resources
  tags: Account,Id,Resources
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/plivo/accountidresources-post-openapi.md
- name: Codenvy Account API
  x-api-slug: codenvy-account-api
  description: 'Voice & SMS API Platform: Plivo enables businesses and developers
    to tap into powerful Voice and SMS capabilities without carrier lock-in.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1113-plivo.jpg
  humanURL: http:///account
  baseURL: :///account/https://codenvy.com/api
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/plivo/openapi.md
x-common:
- type: x--net-library
  url: https://www.plivo.com/docs/helpers/dotnet/
- type: x-android-sdk
  url: https://www.plivo.com/docs/sdk/android/
- type: x-base
  url: https://api.plivo.com
- type: x-blog
  url: http://blog.plivo.com
- type: x-blog-rss
  url: http://blog.plivo.com/rss
- type: x-crunchbase
  url: https://crunchbase.com/organization/plivo
- type: x-crunchbase
  url: http://www.crunchbase.com/company/plivo
- type: x-documentation
  url: https://plivo.com/docs/
- type: x-email
  url: marketing@plivo.com
- type: x-email
  url: legalrequests@plivo.com
- type: x-email
  url: privacy@plivo.com
- type: x-faq
  url: https://plivo.com/faq/
- type: x-github
  url: https://github.com/plivo
- type: x-ios-sdk
  url: https://www.plivo.com/docs/sdk/ios/
- type: x-java-sdk
  url: https://www.plivo.com/docs/helpers/java/
- type: x-linkedin
  url: https://www.linkedin.com/company/plivo-inc/
- type: x-node-js-library
  url: https://www.plivo.com/docs/helpers/node/
- type: x-php-sdk
  url: https://www.plivo.com/docs/helpers/php/
- type: x-pricing
  url: https://plivo.com/pricing/
- type: x-privacy
  url: https://plivo.com/privacy/
- type: x-ruby-library
  url: https://www.plivo.com/docs/helpers/python
- type: x-selfservice-registration
  url: https://manage.plivo.com/accounts/register/
- type: x-status
  url: https://status.plivo.com/
- type: x-terms-of-service
  url: https://plivo.com/terms/
- type: x-twitter
  url: https://twitter.com/plivo
- type: x-website
  url: http:///account
- type: x-website
  url: http://plivo.com
- type: x-website
  url: https://www.plivo.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---