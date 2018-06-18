---
name: Xero
x-slug: xero
description: Xero is the QuickBooks alternative. Use Xero accounting software to manage
  invoicing, bank reconciliation, bookkeeping & more. Start a free trial today!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
x-kinRank: "8"
x-alexaRank: "2158"
tags: Count
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/xero/apis.md
specificationVersion: "0.14"
apis:
- name: Clarity Accounting Get Accounts
  x-api-slug: clarity-accounting
  description: Retrieve the chart of accounts
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts
  tags: Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/xero/accounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/xero/accounts-get-openapi.md
- name: Clarity Accounting Post Accounts
  x-api-slug: clarity-accounting
  description: Post accounts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts
  tags: Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/xero/accounts-post-openapi.md
- name: Clarity Accounting Put Accounts
  x-api-slug: clarity-accounting
  description: Put accounts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts
  tags: Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/xero/accounts-put-openapi.md
- name: Clarity Accounting X-related-model Accounts
  x-api-slug: clarity-accounting
  description: X-related-model accounts.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts
  tags: Accounts
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/xero/accounts-xrelatedmodel-openapi.md
- name: Clarity Accounting Delete Accounts
  x-api-slug: clarity-accounting
  description: Delete accounts account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts/{AccountID}
  tags: Accounts,AccountID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/xero/accountsaccountid-delete-openapi.md
- name: Clarity Accounting Get Accounts
  x-api-slug: clarity-accounting
  description: Get accounts account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts/{AccountID}
  tags: Accounts,AccountID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/xero/accountsaccountid-get-openapi.md
- name: Clarity Accounting Post Accounts
  x-api-slug: clarity-accounting
  description: Post accounts account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts/{AccountID}
  tags: Accounts,AccountID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/xero/accountsaccountid-post-openapi.md
- name: Clarity Accounting X-related-model Accounts
  x-api-slug: clarity-accounting
  description: X-related-model accounts account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts/{AccountID}
  tags: Accounts,AccountID
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/xero/accountsaccountid-xrelatedmodel-openapi.md
- name: Clarity Accounting Get Accounts Attachments
  x-api-slug: clarity-accounting
  description: Get accounts account attachments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts/{AccountID}/Attachments
  tags: Accounts,AccountID,Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/xero/accountsaccountidattachments-get-openapi.md
- name: Clarity Accounting Get Accounts Attachments Filename
  x-api-slug: clarity-accounting
  description: Get accounts account attachments filename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts/{AccountID}/Attachments/{FileName}
  tags: Accounts,AccountID,Attachments,FileName
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/xero/accountsaccountidattachmentsfilename-get-openapi.md
- name: Clarity Accounting Post Accounts Attachments Filename
  x-api-slug: clarity-accounting
  description: Post accounts account attachments filename.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0//Accounts/{AccountID}/Attachments/{FileName}
  tags: Accounts,AccountID,Attachments,FileName
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/xero/accountsaccountidattachmentsfilename-post-openapi.md
- name: Clarity Accounting
  x-api-slug: clarity-accounting
  description: Xero is the QuickBooks alternative. Use Xero accounting software to
    manage invoicing, bank reconciliation, bookkeeping & more. Start a free trial
    today!
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/279-xero.jpg
  humanURL: http://www.xero.com/
  baseURL: https://api.xero.com//api.xro/2.0
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/xero/openapi.md
x-common:
- type: x-base
  url: https://api.xero.com
- type: x-blog
  url: http://blog.xero.com
- type: x-blog
  url: https://devblog.xero.com/
- type: x-blog-rss
  url: https://devblog.xero.com/feed
- type: x-blog-rss
  url: http://feeds.feedburner.com/xerolive
- type: x-crunchbase
  url: http://www.crunchbase.com/company/xero
- type: x-crunchbase
  url: https://crunchbase.com/organization/xero
- type: x-developer
  url: http://developer.xero.com/
- type: x-email
  url: support@xero.com
- type: x-email
  url: sales@xero.com
- type: x-email
  url: careers@xero.com
- type: x-email
  url: privacy@xero.com
- type: x-email
  url: phishing@xero.com
- type: x-email
  url: press@xero.com
- type: x-email
  url: AUpress@xero.com
- type: x-email
  url: UKpress@xero.com
- type: x-email
  url: USpress@xero.com
- type: x-github
  url: https://github.com/XeroAPI
- type: x-partners
  url: http://developer.xero.com/partner/
- type: x-pricing
  url: https://www.xero.com/us/pricing/
- type: x-twitter
  url: https://twitter.com/xero
- type: x-website
  url: http://www.xero.com/
- type: x-website
  url: http://xero.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---