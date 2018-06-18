---
name: 3scale
x-slug: 3scale
description: 3scales API Management platform gives you the tools you need to take
  control of your API. Trusted by more customers than any other vendor.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
x-kinRank: "10"
x-alexaRank: "345437"
tags: Count
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/apis.md
specificationVersion: "0.14"
apis:
- name: 3Scale Account Management API Account List
  x-api-slug: 3scale-account-management-api
  description: Account list.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/accounts.xml
  tags: Account,List
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccounts-xml-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccounts-xml-get-openapi.md
- name: 3Scale Account Management API Account Find
  x-api-slug: 3scale-account-management-api
  description: Account find.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/accounts/find.xml
  tags: Account,Find
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsfind-xml-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsfind-xml-get-openapi.md
- name: 3Scale Account Management API Account Message
  x-api-slug: 3scale-account-management-api
  description: Account message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/accounts/{account_id}/messages.xml
  tags: Account,Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsaccount-idmessages-xml-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsaccount-idmessages-xml-post-openapi.md
- name: 3Scale Account Management API Account Fetch Account Plan
  x-api-slug: 3scale-account-management-api
  description: Account fetch account plan.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/accounts/{account_id}/plan.xml
  tags: Account,Fetch,Account,Plan
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsaccount-idplan-xml-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsaccount-idplan-xml-get-openapi.md
- name: 3Scale Account Management API Account Delete
  x-api-slug: 3scale-account-management-api
  description: Account delete .
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/accounts/{id}.xml
  tags: Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsid-xml-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsid-xml-delete-openapi.md
- name: 3Scale Account Management API Account Read
  x-api-slug: 3scale-account-management-api
  description: Account read.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/accounts/{id}.xml
  tags: Account,Read
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsid-xml-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsid-xml-get-openapi.md
- name: 3Scale Account Management API Account Update
  x-api-slug: 3scale-account-management-api
  description: Account update.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/accounts/{id}.xml
  tags: Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsid-xml-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsid-xml-put-openapi.md
- name: 3Scale Account Management API Account Approve
  x-api-slug: 3scale-account-management-api
  description: Account approve.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/accounts/{id}/approve.xml
  tags: Account,Approve
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsidapprove-xml-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsidapprove-xml-put-openapi.md
- name: 3Scale Account Management API Account Change Plan
  x-api-slug: 3scale-account-management-api
  description: Account change plan.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/accounts/{id}/change_plan.xml
  tags: Account,Change,Plan
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsidchange-plan-xml-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsidchange-plan-xml-put-openapi.md
- name: 3Scale Account Management API Account Delete Credit Card
  x-api-slug: 3scale-account-management-api
  description: Account delete credit card.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/accounts/{id}/credit_card.xml
  tags: Account,,Credit,Card
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsidcredit-card-xml-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsidcredit-card-xml-delete-openapi.md
- name: 3Scale Account Management API Account Set Credit Card
  x-api-slug: 3scale-account-management-api
  description: Account set credit card.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/accounts/{id}/credit_card.xml
  tags: Account,Set,Credit,Card
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsidcredit-card-xml-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsidcredit-card-xml-put-openapi.md
- name: 3Scale Account Management API Account Reset to Pending
  x-api-slug: 3scale-account-management-api
  description: Account reset to pending.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/accounts/{id}/make_pending.xml
  tags: Account,Reset,To,Pending
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsidmake-pending-xml-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsidmake-pending-xml-put-openapi.md
- name: 3Scale Account Management API Account Reject
  x-api-slug: 3scale-account-management-api
  description: Account reject.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/accounts/{id}/reject.xml
  tags: Account,Reject
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsidreject-xml-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccountsidreject-xml-put-openapi.md
- name: 3Scale Account Management API Account Plan List
  x-api-slug: 3scale-account-management-api
  description: Account plan list.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/account_plans.xml
  tags: Account,Plan,List
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccount-plans-xml-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccount-plans-xml-get-openapi.md
- name: 3Scale Account Management API Account Plan Create
  x-api-slug: 3scale-account-management-api
  description: Account plan create.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/account_plans.xml
  tags: Account,Plan,Create
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccount-plans-xml-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccount-plans-xml-post-openapi.md
- name: 3Scale Account Management API Account Plan Feature List
  x-api-slug: 3scale-account-management-api
  description: Account plan feature list.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/account_plans/{account_plan_id}/features.xml
  tags: Account,Plan,Feature,List
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccount-plansaccount-plan-idfeatures-xml-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccount-plansaccount-plan-idfeatures-xml-get-openapi.md
- name: 3Scale Account Management API Account Plan Features Delete
  x-api-slug: 3scale-account-management-api
  description: Account plan features delete.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/account_plans/{account_plan_id}/features/{id}.xml
  tags: Account,Plan,Features
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccount-plansaccount-plan-idfeaturesid-xml-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccount-plansaccount-plan-idfeaturesid-xml-delete-openapi.md
- name: 3Scale Account Management API Account Plan Features Create
  x-api-slug: 3scale-account-management-api
  description: Account plan features create.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/account_plans/{account_plan_id}/features/{id}.xml
  tags: Account,Plan,Features,Create
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccount-plansaccount-plan-idfeaturesid-xml-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccount-plansaccount-plan-idfeaturesid-xml-post-openapi.md
- name: 3Scale Account Management API Account Plan Delete
  x-api-slug: 3scale-account-management-api
  description: Account plan delete.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/account_plans/{id}.xml
  tags: Account,Plan
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccount-plansid-xml-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccount-plansid-xml-delete-openapi.md
- name: 3Scale Account Management API Account Plan Read
  x-api-slug: 3scale-account-management-api
  description: Account plan read.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/account_plans/{id}.xml
  tags: Account,Plan,Read
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccount-plansid-xml-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccount-plansid-xml-get-openapi.md
- name: 3Scale Account Management API Account Plan Update
  x-api-slug: 3scale-account-management-api
  description: Account plan update.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/account_plans/{id}.xml
  tags: Account,Plan
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccount-plansid-xml-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccount-plansid-xml-put-openapi.md
- name: 3Scale Account Management API Account Plan set to Default
  x-api-slug: 3scale-account-management-api
  description: Account plan set to default.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/account_plans/{id}/default.xml
  tags: Account,Plan,Set,To,Default
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccount-plansiddefault-xml-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiaccount-plansiddefault-xml-put-openapi.md
- name: 3Scale Account Management API Account Feature List
  x-api-slug: 3scale-account-management-api
  description: Account feature list.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/features.xml
  tags: Account,Feature,List
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapifeatures-xml-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapifeatures-xml-get-openapi.md
- name: 3Scale Account Management API Account Feature Create
  x-api-slug: 3scale-account-management-api
  description: Account feature create.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/features.xml
  tags: Account,Feature,Create
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapifeatures-xml-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapifeatures-xml-post-openapi.md
- name: 3Scale Account Management API Account Feature Delete
  x-api-slug: 3scale-account-management-api
  description: Account feature delete.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/features/{id}.xml
  tags: Account,Feature
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapifeaturesid-xml-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapifeaturesid-xml-delete-openapi.md
- name: 3Scale Account Management API Account Feature Read
  x-api-slug: 3scale-account-management-api
  description: Account feature read.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/features/{id}.xml
  tags: Account,Feature,Read
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapifeaturesid-xml-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapifeaturesid-xml-get-openapi.md
- name: 3Scale Account Management API Account Feature Update
  x-api-slug: 3scale-account-management-api
  description: Account feature update.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/features/{id}.xml
  tags: Account,Feature
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapifeaturesid-xml-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapifeaturesid-xml-put-openapi.md
- name: 3Scale Account Management API Account Read
  x-api-slug: 3scale-account-management-api
  description: Account read.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/provider.xml
  tags: Account,Read
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiprovider-xml-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiprovider-xml-get-openapi.md
- name: 3Scale Account Management API User List (provider account)
  x-api-slug: 3scale-account-management-api
  description: User list (provider account).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/users.xml
  tags: User,List,(provider,Account)
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiusers-xml-get-openapi.md
- name: 3Scale Account Management API User Create (provider account)
  x-api-slug: 3scale-account-management-api
  description: User create (provider account).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/users.xml
  tags: User,(provider,Account)
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiusers-xml-post-openapi.md
- name: 3Scale Account Management API User Delete (provider account)
  x-api-slug: 3scale-account-management-api
  description: User delete (provider account).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/users/{id}.xml
  tags: User,,(provider,Account)
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiusersid-xml-delete-openapi.md
- name: 3Scale Account Management API User Read (provider account)
  x-api-slug: 3scale-account-management-api
  description: User read (provider account).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/users/{id}.xml
  tags: User,Read,(provider,Account)
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiusersid-xml-get-openapi.md
- name: 3Scale Account Management API User Update (provider account)
  x-api-slug: 3scale-account-management-api
  description: User update (provider account).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/users/{id}.xml
  tags: User,,(provider,Account)
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiusersid-xml-put-openapi.md
- name: 3Scale Account Management API User Activate (provider account)
  x-api-slug: 3scale-account-management-api
  description: User activate (provider account).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/users/{id}/activate.xml
  tags: User,Activate,(provider,Account)
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiusersidactivate-xml-put-openapi.md
- name: 3Scale Account Management API User change Role to Admin (provider account)
  x-api-slug: 3scale-account-management-api
  description: User change role to admin (provider account).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/users/{id}/admin.xml
  tags: User,Change,Role,To,Admin,(provider,Account)
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiusersidadmin-xml-put-openapi.md
- name: 3Scale Account Management API User change Role to Member (provider account)
  x-api-slug: 3scale-account-management-api
  description: User change role to member (provider account).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/users/{id}/member.xml
  tags: User,Change,Role,To,Member,(provider,Account)
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiusersidmember-xml-put-openapi.md
- name: 3Scale Account Management API User Suspend (provider account)
  x-api-slug: 3scale-account-management-api
  description: User suspend (provider account).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/users/{id}/suspend.xml
  tags: User,Suspend,(provider,Account)
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiusersidsuspend-xml-put-openapi.md
- name: 3Scale Account Management API User Unsuspend (of provider account)
  x-api-slug: 3scale-account-management-api
  description: User unsuspend (of provider account).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/users/{id}/unsuspend.xml
  tags: User,Unsuspend,(of,Provider,Account)
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/adminapiusersidunsuspend-xml-put-openapi.md
- name: 3Scale Account Management API
  x-api-slug: 3scale-account-management-api
  description: 3scales API Management platform gives you the tools you need to take
    control of your API. Trusted by more customers than any other vendor.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net//
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/openapi.md
- name: 3Scale Billing API Invoice List by Account
  x-api-slug: 3scale-billing-api
  description: Invoice list by account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////api/accounts/{account_id}/invoices.xml
  tags: Invoice,List,By,Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/apiaccountsaccount-idinvoices-xml-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/apiaccountsaccount-idinvoices-xml-get-openapi.md
- name: 3Scale Billing API Invoice by Account
  x-api-slug: 3scale-billing-api
  description: Invoice by account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////api/accounts/{account_id}/invoices/{id}.xml
  tags: Invoice,By,Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/apiaccountsaccount-idinvoicesid-xml-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/apiaccountsaccount-idinvoicesid-xml-get-openapi.md
- name: 3Scale Billing API
  x-api-slug: 3scale-billing-api
  description: 3scales API Management platform gives you the tools you need to take
    control of your API. Trusted by more customers than any other vendor.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net//
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/3scale/openapi.md
x-common:
- type: x-blog
  url: http://www.3scale.net/blog/
- type: x-blog-rss
  url: http://www.3scale.net/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/3scale
- type: x-crunchbase
  url: https://crunchbase.com/organization/3scale
- type: x-email
  url: sales@3scale.net
- type: x-email
  url: info@3scale.net
- type: x-github
  url: https://github.com/3scale
- type: x-pricing
  url: https://www.3scale.net/pricing/
- type: x-privacy
  url: https://www.3scale.net/privacy-policy/
- type: x-support
  url: https://support.3scale.net
- type: x-openapi-spec
  url: https://support.3scale.net/reference/active-docs
- type: x-terms-of-service
  url: https://www.3scale.net/terms-and-conditions/
- type: x-twitter
  url: https://twitter.com/3scale
- type: x-website
  url: http://3scale.net
- type: x-website
  url: http://
- type: x-website
  url: http://www.3scale.net
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---