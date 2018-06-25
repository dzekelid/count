---
name: SendGrid
x-slug: sendgrid
description: Delivering your transactional and marketing emails through the worlds
  largest cloud-based email delivery platform. Send with confidence.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
x-kinRank: "9"
x-alexaRank: "10000"
tags: Count
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/sendgrid/apis.md
specificationVersion: "0.14"
apis:
- name: SendGrid Get Contactdb Recipients Billable Count
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to retrieve the number of Marketing Campaigns recipients that you will be billed for.**

    You are billed for marketing campaigns based on the highest number of recipients you have had in your account at one time. This endpoint will allow you to know the current billable count value.

    The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//contactdb/recipients/billable_count
  tags: Email,Contactdb, Recipients, Billable, Count
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/sendgrid/contactdbrecipientsbillable-count-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/sendgrid/contactdbrecipientsbillable-count-get-openapi.md
- name: SendGrid Get Contactdb Recipients Count
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to retrieve the total number of Marketing Campaigns recipients.**

    The contactdb is a database of your contacts for [SendGrid Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//contactdb/recipients/count
  tags: Email,Contactdb, Recipients, Count
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/sendgrid/contactdbrecipientscount-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/sendgrid/contactdbrecipientscount-get-openapi.md
- name: SendGrid Get User Account
  x-api-slug: sendgrid
  description: |-
    **This endpoint allows you to retrieve your user account details.**

    Your user's account information includes the user's account type and reputation.

    Keeping your user profile up to date is important. This will help SendGrid to verify who you are as well as contact you should we need to.

    For more information about your user profile:

    * [SendGrid Account Settings](https://sendgrid.com/docs/User_Guide/Settings/account.html)
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3//user/account
  tags: Email,User, Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/sendgrid/useraccount-get-openapi.md
- name: SendGrid
  x-api-slug: sendgrid
  description: SendGrids cloud-based email infrastructure relieves businesses of the
    cost and complexity of maintaining custom email systems. SendGrid provides reliable
    delivery, scalability and real-time analytics along with flexible APIs that make
    custom integration a breeze.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/sendgrid/openapi.md
x-common:
- type: x--net-library
  url: https://sendgrid.com/docs/Code_Examples/csharp.html
- type: x-base
  url: https://api.sendgrid.com
- type: x-blog
  url: http://blog.sendgrid.com/
- type: x-blog-rss
  url: http://feeds.feedburner.com/sendgrid/CDXr
- type: x-contact-form
  url: https://sendgrid.com/contact
- type: x-crunchbase
  url: http://www.crunchbase.com/company/sendgrid
- type: x-crunchbase
  url: https://crunchbase.com/organization/sendgrid
- type: x-developer
  url: https://sendgrid.com/developers
- type: x-documentation
  url: https://sendgrid.com/docs/index.html
- type: x-email
  url: privacy@sendgrid.com
- type: x-email
  url: legal@sendgrid.com
- type: x-email
  url: dpo@sendgrid.com
- type: x-forum
  url: http://support.sendgrid.com/forums
- type: x-github
  url: https://github.com/sendgrid
- type: x-go-library
  url: https://sendgrid.com/docs/Code_Examples/go.html
- type: x-ios-library
  url: https://sendgrid.com/docs/Code_Examples/ios.html
- type: x-java-library
  url: https://sendgrid.com/docs/Code_Examples/java.html
- type: x-labs
  url: http://labs.sendgrid.com/
- type: x-linkedin
  url: https://www.linkedin.com/company/sendgrid
- type: x-node-js-library
  url: https://sendgrid.com/docs/Code_Examples/nodejs.html
- type: x-partners
  url: https://sendgrid.com/partners
- type: x-perl-library
  url: https://sendgrid.com/docs/Code_Examples/perl.html
- type: x-php-library
  url: https://sendgrid.com/docs/Code_Examples/php.html
- type: x-pricing
  url: https://sendgrid.com/transactional-email/pricing
- type: x-privacy
  url: https://sendgrid.com/privacy
- type: x-python-library
  url: https://sendgrid.com/docs/Code_Examples/python.html
- type: x-ruby-library
  url: https://sendgrid.com/docs/Code_Examples/ruby.html
- type: x-security
  url: https://sendgrid.com/security
- type: x-selfservice-registration
  url: https://sendgrid.com/user/signup
- type: x-terms-of-service
  url: https://sendgrid.com/tos
- type: x-twitter
  url: https://twitter.com/SendGrid
- type: x-website
  url: http://sendgrid.com
- type: x-website
  url: https://sendgrid.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---