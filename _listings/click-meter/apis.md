---
name: Click Meter
x-slug: click-meter
description: ClickMeter was founded in 2012 as a byproduct of an experienced web-marketing
  agency. The ClickMeter System was initially a web tool created to address the needs
  of our agency to precisely count and track the web-marketing actions we performed
  for our customers.The system evolved rapidly, and emerged as one of the most widely
  used software solutions in our agency to collect, analyze, and share data for and
  with our customers. After few years after the development of the first ClickMeter
  system, we decided to go live with a service that can be useful to everyone involved
  in web-marketing activities.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Count
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/apis.md
specificationVersion: "0.14"
apis:
- name: Click Meter Retrieve current account data
  x-api-slug: click-meter
  description: Retrieve current account data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account
  tags: Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/account-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/account-get-openapi.md
- name: Click Meter Update current account data
  x-api-slug: click-meter
  description: Update current account data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/account-post-openapi.md
- name: Click Meter Retrieve list of a domains allowed to redirect in DDU mode
  x-api-slug: click-meter
  description: Retrieve list of a domains allowed to redirect in ddu mode.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/domainwhitelist
  tags: Account,Domainwhitelist
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/accountdomainwhitelist-get-openapi.md
- name: Click Meter Create an domain entry
  x-api-slug: click-meter
  description: Create an domain entry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/domainwhitelist
  tags: Account,Domainwhitelist
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/accountdomainwhitelist-post-openapi.md
- name: Click Meter Delete an domain entry
  x-api-slug: click-meter
  description: Delete an domain entry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/domainwhitelist/{whitelistId}
  tags: Account,Domainwhitelist,WhitelistId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/accountdomainwhitelistwhitelistid-delete-openapi.md
- name: Click Meter Retrieve list of a guest
  x-api-slug: click-meter
  description: Retrieve list of a guest.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/guests
  tags: Account,Guests
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/accountguests-get-openapi.md
- name: Click Meter Create a guest
  x-api-slug: click-meter
  description: Create a guest.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/guests
  tags: Account,Guests
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/accountguests-post-openapi.md
- name: Click Meter Retrieve count of guests
  x-api-slug: click-meter
  description: Retrieve count of guests.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/guests/count
  tags: Account,Guests,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/accountguestscount-get-openapi.md
- name: Click Meter Delete a guest
  x-api-slug: click-meter
  description: Delete a guest.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/guests/{guestId}
  tags: Account,Guests,GuestId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/accountguestsguestid-delete-openapi.md
- name: Click Meter Retrieve a guest
  x-api-slug: click-meter
  description: Retrieve a guest.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/guests/{guestId}
  tags: Account,Guests,GuestId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/accountguestsguestid-get-openapi.md
- name: Click Meter Update a guest
  x-api-slug: click-meter
  description: Update a guest.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/guests/{guestId}
  tags: Account,Guests,GuestId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/accountguestsguestid-post-openapi.md
- name: Click Meter Retrieve permissions for a guest
  x-api-slug: click-meter
  description: Retrieve permissions for a guest.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/guests/{guestId}/permissions
  tags: Account,Guests,GuestId,Permissions
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/accountguestsguestidpermissions-get-openapi.md
- name: Click Meter Retrieve count of the permissions for a guest
  x-api-slug: click-meter
  description: Retrieve count of the permissions for a guest.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/guests/{guestId}/permissions/count
  tags: Account,Guests,GuestId,Permissions,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/accountguestsguestidpermissionscount-get-openapi.md
- name: Click Meter Change the permission on a shared object
  x-api-slug: click-meter
  description: Change the permission on a shared object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/guests/{guestId}/{type}/permissions/patch
  tags: Account,Guests,GuestId,Type,Permissions,Patch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/accountguestsguestidtypepermissionspatch-post-openapi.md
- name: Click Meter Change the permission on a shared object
  x-api-slug: click-meter
  description: Change the permission on a shared object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/guests/{guestId}/{type}/permissions/patch
  tags: Account,Guests,GuestId,Type,Permissions,Patch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/accountguestsguestidtypepermissionspatch-put-openapi.md
- name: Click Meter Retrieve list of a ip to exclude from event tracking
  x-api-slug: click-meter
  description: Retrieve list of a ip to exclude from event tracking.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/ipblacklist
  tags: Account,Ipblacklist
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/accountipblacklist-get-openapi.md
- name: Click Meter Create an ip blacklist entry
  x-api-slug: click-meter
  description: Create an ip blacklist entry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/ipblacklist
  tags: Account,Ipblacklist
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/accountipblacklist-post-openapi.md
- name: Click Meter Delete an ip blacklist entry
  x-api-slug: click-meter
  description: Delete an ip blacklist entry.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/ipblacklist/{blacklistId}
  tags: Account,Ipblacklist,BlacklistId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/accountipblacklistblacklistid-delete-openapi.md
- name: Click Meter Retrieve current account plan
  x-api-slug: click-meter
  description: Retrieve current account plan.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////account/plan
  tags: Account,Plan
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/accountplan-get-openapi.md
- name: Click Meter Retrieve a count of conversions
  x-api-slug: click-meter
  description: Retrieve a count of conversions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions/count
  tags: Conversions,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/conversionscount-get-openapi.md
- name: Click Meter Retrieve a count of datapoints connected to this conversion
  x-api-slug: click-meter
  description: Retrieve a count of datapoints connected to this conversion.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////conversions/{conversionId}/datapoints/count
  tags: Conversions,ConversionId,Datapoints,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/conversionsconversioniddatapointscount-get-openapi.md
- name: Click Meter Count the datapoints associated to the user
  x-api-slug: click-meter
  description: Count the datapoints associated to the user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////datapoints/count
  tags: Datapoints,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/datapointscount-get-openapi.md
- name: Click Meter Retrieve count of domains
  x-api-slug: click-meter
  description: Retrieve count of domains.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////domains/count
  tags: Domains,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/domainscount-get-openapi.md
- name: Click Meter Count the groups associated to the user.
  x-api-slug: click-meter
  description: Count the groups associated to the user..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups/count
  tags: Groups,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/groupscount-get-openapi.md
- name: Click Meter Count the datapoints associated to the user in this group.
  x-api-slug: click-meter
  description: Count the datapoints associated to the user in this group..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////groups/{id}/datapoints/count
  tags: Groups,Id,Datapoints,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/groupsiddatapointscount-get-openapi.md
- name: Click Meter Retrieve count of retargeting scripts
  x-api-slug: click-meter
  description: Retrieve count of retargeting scripts.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////retargeting/count
  tags: Retargeting,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/retargetingcount-get-openapi.md
- name: Click Meter Count the datapoints associated to the retargeting script.
  x-api-slug: click-meter
  description: Count the datapoints associated to the retargeting script..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////retargeting/{id}/datapoints/count
  tags: Retargeting,Id,Datapoints,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/retargetingiddatapointscount-get-openapi.md
- name: Click Meter List of all the groups associated to the user filtered by this
    tag.
  x-api-slug: click-meter
  description: List of all the groups associated to the user filtered by this tag..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////tags/count
  tags: Tags,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/tagscount-get-openapi.md
- name: Click Meter Count the datapoints associated to the user filtered by this tag
  x-api-slug: click-meter
  description: Count the datapoints associated to the user filtered by this tag.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////tags/{tagId}/datapoints/count
  tags: Tags,TagId,Datapoints,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/tagstagiddatapointscount-get-openapi.md
- name: Click Meter Count the groups associated to the user filtered by this tag
  x-api-slug: click-meter
  description: Count the groups associated to the user filtered by this tag.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80////tags/{tagId}/groups/count
  tags: Tags,TagId,Groups,Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/tagstagidgroupscount-get-openapi.md
- name: Click Meter
  x-api-slug: click-meter
  description: ClickMeter was founded in 2012 as a byproduct of an experienced web-marketing
    agency. The ClickMeter System was initially a web tool created to address the
    needs of our agency to precisely count and track the web-marketing actions we
    performed for our customers.The system evolved rapidly, and emerged as one of
    the most widely used software solutions in our agency to collect, analyze, and
    share data for and with our customers. After few years after the development of
    the first ClickMeter system, we decided to go live with a service that can be
    useful to everyone involved in web-marketing activities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/clickmeter-logo.png
  humanURL: http://clickmeter.com
  baseURL: https://apiv2.clickmeter.com:80//
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/click-meter/openapi.md
x-common:
- type: x-blog
  url: https://blog.clickmeter.com/
- type: x-pricing
  url: http://clickmeter.com/pricing-signup
- type: x-support
  url: https://support.clickmeter.com/hc/en-us
- type: x-terms-of-service
  url: http://clickmeter.com/terms-conditions
- type: x-twitter
  url: https://twitter.com/clickmeter
- type: x-website
  url: http://clickmeter.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---