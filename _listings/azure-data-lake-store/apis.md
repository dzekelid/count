---
name: Azure Data Lake Store
x-slug: azure-data-lake-store
description: The Data Lake store provides a single repository where you can capture
  data of any size type and speed simply without forcing changes to your application
  as the data scales. In the store, data can be shared for collaboration with enterprise-grade
  security. It is also designed for high-performance processing and analytics from
  HDFS applications (ie. Azure HDInsight, Data Lake analytics service, Hortonworks,
  Cloudera, MapR) and tools, including support for low latency workloads. For example,
  data can be ingested in real-time from sensors and devices for IoT solutions, or
  from online shopping websites into the store without the restriction of fixed limits
  on account or file size unlike current offerings in the market.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Count
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/azure-data-lake-store/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Data Lake Store API Account Create
  x-api-slug: azure-data-lake-store-api
  description: Creates the specified Data Lake Store account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{name}
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsname-put-openapi.md
- name: Azure Data Lake Store API Account Update
  x-api-slug: azure-data-lake-store-api
  description: Updates the specified Data Lake Store account information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{name}
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsname-patch-openapi.md
- name: Azure Data Lake Store API Account Delete
  x-api-slug: azure-data-lake-store-api
  description: Deletes the specified Data Lake Store account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{name}
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsname-delete-openapi.md
- name: Azure Data Lake Store API Account Get
  x-api-slug: azure-data-lake-store-api
  description: Gets the specified Data Lake Store account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{name}
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsname-get-openapi.md
- name: Azure Data Lake Store API Account Enable Key Vault
  x-api-slug: azure-data-lake-store-api
  description: Attempts to enable a user managed key vault for encryption of the specified
    Data Lake Store account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts/{accountName}/enableKeyVault
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccountsaccountnameenablekeyvault-post-openapi.md
- name: Azure Data Lake Store API Account List By Resource Group
  x-api-slug: azure-data-lake-store-api
  description: Lists the Data Lake Store accounts within a specific resource group.
    The response includes a link to the next page of results, if any.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeStore/accounts
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/azure-data-lake-store/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakestoreaccounts-get-openapi.md
- name: Azure Data Lake Store API Account List
  x-api-slug: azure-data-lake-store-api
  description: Lists the Data Lake Store accounts within the subscription. The response
    includes a link to the next page of results, if any.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: ://////subscriptions/{subscriptionId}/providers/Microsoft.DataLakeStore/accounts
  tags: Account
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/azure-data-lake-store/subscriptionssubscriptionidprovidersmicrosoft-datalakestoreaccounts-get-openapi.md
- name: Azure Data Lake Store API
  x-api-slug: azure-data-lake-store-api
  description: The Data Lake store provides a single repository where you can capture
    data of any size type and speed simply without forcing changes to your application
    as the data scales. In the store, data can be shared for collaboration with enterprise-grade
    security. It is also designed for high-performance processing and analytics from
    HDFS applications (ie. Azure HDInsight, Data Lake analytics service, Hortonworks,
    Cloudera, MapR) and tools, including support for low latency workloads. For example,
    data can be ingested in real-time from sensors and devices for IoT solutions,
    or from online shopping websites into the store without the restriction of fixed
    limits on account or file size unlike current offerings in the market.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-data-lake-store-01-petabyte.png
  humanURL: https://azure.microsoft.com/en-us/services/data-lake-store/
  baseURL: :////
  tags: Count
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/count/master/_listings/azure-data-lake-store/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/data-lake-store/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/data-lake-store/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/data-lake-store/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/data-lake-store/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---