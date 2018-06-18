---
name: Azure Cognitive Services
x-slug: azure-cognitive-services
description: Enable natural and contextual interaction with tools that augment users
  experiences using the power of machine-based intelligence. Tap into an ever-growing
  collection of powerful artificial intelligence algorithms for vision, speech, language,
  and knowledge.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/cognitive-services.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Count
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/azure-cognitive-services/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Cognitive Services Accounts List By Resource Group
  x-api-slug: azure-cognitive-services
  description: Returns all the resources of a particular type belonging to a resource
    group
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/cognitive-services.png
  humanURL: https://azure.microsoft.com/en-us/services/cognitive-services/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.CognitiveServices/accounts
  tags: Machine Learning,Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/azure-cognitive-services/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-cognitiveservicesaccounts-get-openapi.md
- name: Azure Cognitive Services Accounts List
  x-api-slug: azure-cognitive-services
  description: Returns all the resources of a particular type belonging to a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/cognitive-services.png
  humanURL: https://azure.microsoft.com/en-us/services/cognitive-services/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.CognitiveServices/accounts
  tags: Machine Learning,Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/azure-cognitive-services/subscriptionssubscriptionidprovidersmicrosoft-cognitiveservicesaccounts-get-openapi.md
- name: Azure Cognitive Services
  x-api-slug: azure-cognitive-services
  description: Enable natural and contextual interaction with tools that augment users
    experiences using the power of machine-based intelligence. Tap into an ever-growing
    collection of powerful artificial intelligence algorithms for vision, speech,
    language, and knowledge.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/cognitive-services.png
  humanURL: https://azure.microsoft.com/en-us/services/cognitive-services/
  baseURL: ://management.azure.com//
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/azure-cognitive-services/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/cognitive-services/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/cognitive-services/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/cognitive-services/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/cognitive-services/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---