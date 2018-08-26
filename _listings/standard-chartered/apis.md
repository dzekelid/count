---
name: Standard Chartered
x-slug: standard-chartered
description: Standard Chartered PLC is a British multinational banking and financial
  services company headquartered in London, England. It operates a network of more
  than 1,200 branches and outlets (including subsidiaries, associates and joint ventures)
  across more than 70 countries and employs around 87,000 people. It is a universal
  bank with operations in consumer, corporate and institutional banking, and treasury
  services. Despite its UK base, it does not conduct retail banking in the UK, and
  around 90% of its profits come from Asia, Africa and the Middle East.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/standard-charter.png
x-kinRank: "7"
x-alexaRank: "4658"
tags: Count
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/standard-chartered/apis.md
specificationVersion: "0.14"
apis:
- name: Standard Chartered Accounts
  x-api-slug: standard-chartered
  description: "The \u201CGetAccountBalance\u201D API upon successful user authentication
    and entitlement checks will return the various types of \u201CAccount Balances\u201D
    applicable for the specified Account Number."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/standard-charter.png
  humanURL: https://developer.sc.com
  baseURL: https://developer.sc.com////cib/service/s2b/api/v1/banks/scb/accounts/{accountId}/{viewId}/account
  tags: Cib, Service, S2b, Api, V1, Banks, Scb, Accounts, Account, View, Account
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/standard-chartered/cibservices2bapiv1banksscbaccountsaccountidviewidaccount-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/standard-chartered/cibservices2bapiv1banksscbaccountsaccountidviewidaccount-get-openapi.md
- name: Standard Chartered Finds all support transaction types for a given account
  x-api-slug: standard-chartered
  description: "The \u201CGetTransactionTypes\u201D API upon successful user authentication
    and entitlement checks will return the supported transaction types for the specified
    account"
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/standard-charter.png
  humanURL: https://developer.sc.com
  baseURL: https://developer.sc.com////cib/service/s2b/api/v1/banks/scb/accounts/{accountId}/{viewId}/transaction-request-types
  tags: Cib, Service, S2b, Api, V1, Banks, Scb, Accounts, Account, View, Transaction,
    Request, Types
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/standard-chartered/cibservices2bapiv1banksscbaccountsaccountidviewidtransactionrequesttypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/standard-chartered/cibservices2bapiv1banksscbaccountsaccountidviewidtransactionrequesttypes-get-openapi.md
- name: Standard Chartered Account Details & Balances
  x-api-slug: standard-chartered
  description: List available bank accounts
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/standard-charter.png
  humanURL: https://developer.sc.com
  baseURL: https://developer.sc.com////cib/service/s2b/api/v1/banks/scb/accounts/{viewId}/accounts
  tags: Cib, Service, S2b, Api, V1, Banks, Scb, Accounts, View, Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/standard-chartered/cibservices2bapiv1banksscbaccountsviewidaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/standard-chartered/cibservices2bapiv1banksscbaccountsviewidaccounts-get-openapi.md
- name: Standard Chartered Holiday Calendar Inquiry (Country)
  x-api-slug: standard-chartered
  description: "The \u201CGetHolidayCalendar\u201D API returns list of holidays applicable
    for the specified combination of:\n<ul><li>Country</li><li>Date Range</li></lu>"
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/standard-charter.png
  humanURL: https://developer.sc.com
  baseURL: https://developer.sc.com////cib/service/s2b/api/v1/banks/scb/reference/default/holiday-calendar/country/{country}
  tags: Cib, Service, S2b, Api, V1, Banks, Scb, Reference, Default, Holay, Calendar,
    Country, Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/standard-chartered/cibservices2bapiv1banksscbreferencedefaultholidaycalendarcountrycountry-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/standard-chartered/cibservices2bapiv1banksscbreferencedefaultholidaycalendarcountrycountry-get-openapi.md
- name: Standard Chartered Retrieve trade finance customer profile
  x-api-slug: standard-chartered
  description: Retrieve trade finance customer profile
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/standard-charter.png
  humanURL: https://developer.sc.com
  baseURL: https://developer.sc.com////cib/service/s2b/api/v1/trade/{countryCode}/{customerId}/profile
  tags: Cib, Service, S2b, Api, V1, Trade, Countrycode, Customer, Profile
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/standard-chartered/cibservices2bapiv1tradecountrycodecustomeridprofile-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/standard-chartered/cibservices2bapiv1tradecountrycodecustomeridprofile-get-openapi.md
- name: Standard Chartered Retrieve trade finance limit details
  x-api-slug: standard-chartered
  description: Retrieve trade finance limit details
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/standard-charter.png
  humanURL: https://developer.sc.com
  baseURL: https://developer.sc.com////cib/service/s2b/api/v1/trade/{countryCode}/{customerId}/limits
  tags: Cib, Service, S2b, Api, V1, Trade, Countrycode, Customer, Limits
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/standard-chartered/cibservices2bapiv1tradecountrycodecustomeridlimits-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/standard-chartered/cibservices2bapiv1tradecountrycodecustomeridlimits-get-openapi.md
- name: Standard Chartered Retrieve all trade finance transaction status for the current
    date (localised to tz)
  x-api-slug: standard-chartered
  description: Retrieve all trade finance transaction status for the current date
    (localised to tz)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/standard-charter.png
  humanURL: https://developer.sc.com
  baseURL: https://developer.sc.com////cib/service/s2b/api/v1/trade/{countryCode}/{customerId}/transactions
  tags: Cib, Service, S2b, Api, V1, Trade, Countrycode, Customer, Transactions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/standard-chartered/cibservices2bapiv1tradecountrycodecustomeridtransactions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/standard-chartered/cibservices2bapiv1tradecountrycodecustomeridtransactions-get-openapi.md
- name: Standard Chartered Retrieve trade finance transaction status for specific
    transaction reference Id
  x-api-slug: standard-chartered
  description: Retrieve trade finance transaction status for specific transaction
    reference Id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/standard-charter.png
  humanURL: https://developer.sc.com
  baseURL: https://developer.sc.com////cib/service/s2b/api/v1/trade/{countryCode}/{customerId}/transaction/{transactionId}
  tags: Cib, Service, S2b, Api, V1, Trade, Countrycode, Customer, Transaction, Transaction
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/standard-chartered/cibservices2bapiv1tradecountrycodecustomeridtransactiontransactionid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/standard-chartered/cibservices2bapiv1tradecountrycodecustomeridtransactiontransactionid-get-openapi.md
- name: Standard Chartered
  x-api-slug: standard-chartered
  description: Standard Chartered PLC is a British multinational banking and financial
    services company headquartered in London, England. It operates a network of more
    than 1,200 branches and outlets (including subsidiaries, associates and joint
    ventures) across more than 70 countries and employs around 87,000 people. It is
    a universal bank with operations in consumer, corporate and institutional banking,
    and treasury services. Despite its UK base, it does not conduct retail banking
    in the UK, and around 90% of its profits come from Asia, Africa and the Middle
    East.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/standard-charter.png
  humanURL: https://developer.sc.com
  baseURL: https://developer.sc.com//
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/standard-chartered/openapi.md
x-common:
- type: x-accessibility
  url: https://developer.sc.com/cib/#/accessibility
- type: x-applications
  url: https://developer.sc.com/cib/#/showcases
- type: x-crunchbase
  url: https://crunchbase.com/organization/standard-chartered-bank
- type: x-documentation
  url: https://developer.sc.com/cib/#/api-documentation/3
- type: x-privacy-policy
  url: https://developer.sc.com/cib/#/privacy
- type: x-terms-of-service
  url: https://developer.sc.com/cib/#/legal-notice
- type: x-twitter
  url: https://twitter.com/StanChart
- type: x-website
  url: https://developer.sc.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---