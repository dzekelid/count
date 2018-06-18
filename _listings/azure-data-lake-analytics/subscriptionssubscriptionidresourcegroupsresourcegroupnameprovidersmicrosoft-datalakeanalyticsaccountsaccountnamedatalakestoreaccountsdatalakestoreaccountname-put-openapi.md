---
swagger: "2.0"
x-collection-name: Azure Data Lake Analytics
x-complete: 0
info:
  title: Azure Data Lake Analytics API Data Lake Store Accounts Add
  description: Updates the specified Data Lake Analytics account to include the additional
    Data Lake Store account.
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/firewallRules
  : get:
      summary: Firewall Rules List By Account
      description: Lists the Data Lake Analytics firewall rules within the specified
        Data Lake Analytics account.
      operationId: FirewallRules_ListByAccount
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamefirewallrules-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account from which to get
          the firewall rules
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Firewall Rule Account
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/StorageAccounts/{storageAccountName}
  : get:
      summary: Storage Accounts Get
      description: Gets the specified Azure Storage account linked to the given Data
        Lake Analytics account.
      operationId: StorageAccounts_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountname-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account from which to retrieve
          Azure storage account details
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      - in: path
        name: storageAccountName
        description: The name of the Azure Storage account for which to retrieve the
          details
      responses:
        200:
          description: OK
      tags:
      - Stage Account
    delete:
      summary: Storage Accounts Delete
      description: Updates the specified Data Lake Analytics account to remove an
        Azure Storage account.
      operationId: StorageAccounts_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountname-delete
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account from which to remove
          the Azure Storage account
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      - in: path
        name: storageAccountName
        description: The name of the Azure Storage account to remove
      responses:
        200:
          description: OK
      tags:
      - Stage Account
    patch:
      summary: Storage Accounts Update
      description: Updates the Data Lake Analytics account to replace Azure Storage
        blob account details, such as the access key and/or suffix.
      operationId: StorageAccounts_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountname-patch
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account to modify storage
          accounts in
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters containing the access key and suffix to update
          the storage account with, if any
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      - in: path
        name: storageAccountName
        description: The Azure Storage account to modify
      responses:
        200:
          description: OK
      tags:
      - Stage Account
    put:
      summary: Storage Accounts Add
      description: Updates the specified Data Lake Analytics account to add an Azure
        Storage account.
      operationId: StorageAccounts_Add
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountname-put
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account to which to add the
          Azure Storage account
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The parameters containing the access key and optional suffix
          for the Azure Storage Account
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      - in: path
        name: storageAccountName
        description: The name of the Azure Storage account to add
      responses:
        200:
          description: OK
      tags:
      - Stage Account
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/StorageAccounts/{storageAccountName}/Containers
  : get:
      summary: Storage Accounts List Storage Containers
      description: Lists the Azure Storage containers, if any, associated with the
        specified Data Lake Analytics and Azure Storage account combination. The response
        includes a link to the next page of results, if any.
      operationId: StorageAccounts_ListStorageContainers
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountnamecontainers-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account for which to list
          Azure Storage blob containers
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      - in: path
        name: storageAccountName
        description: The name of the Azure storage account from which to list blob
          containers
      responses:
        200:
          description: OK
      tags:
      - Stage Account Stage Containers
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/StorageAccounts/{storageAccountName}/Containers/{containerName}/listSasTokens
  : post:
      summary: Storage Accounts List Sas Tokens
      description: Gets the SAS token associated with the specified Data Lake Analytics
        and Azure Storage account and container combination.
      operationId: StorageAccounts_ListSasTokens
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamestorageaccountsstorageaccountnamecontainerscontainernamelistsastokens-post
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account from which an Azure
          Storage accounts SAS token is being requested
      - in: path
        name: containerName
        description: The name of the Azure storage container for which the SAS token
          is being requested
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      - in: path
        name: storageAccountName
        description: The name of the Azure storage account for which the SAS token
          is being requested
      responses:
        200:
          description: OK
      tags:
      - Stage Account Satokens
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DataLakeAnalytics/accounts/{accountName}/DataLakeStoreAccounts/{dataLakeStoreAccountName}
  : get:
      summary: Data Lake Store Accounts Get
      description: Gets the specified Data Lake Store account details in the specified
        Data Lake Analytics account.
      operationId: DataLakeStoreAccounts_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-get
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account from which to retrieve
          the Data Lake Store account details
      - in: path
        name: dataLakeStoreAccountName
        description: The name of the Data Lake Store account to retrieve
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Data Lake Ste Account
    delete:
      summary: Data Lake Store Accounts Delete
      description: Updates the Data Lake Analytics account specified to remove the
        specified Data Lake Store account.
      operationId: DataLakeStoreAccounts_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-delete
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account from which to remove
          the Data Lake Store account
      - in: path
        name: dataLakeStoreAccountName
        description: The name of the Data Lake Store account to remove
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Data Lake Ste Account
    put:
      summary: Data Lake Store Accounts Add
      description: Updates the specified Data Lake Analytics account to include the
        additional Data Lake Store account.
      operationId: DataLakeStoreAccounts_Add
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-datalakeanalyticsaccountsaccountnamedatalakestoreaccountsdatalakestoreaccountname-put
      parameters:
      - in: path
        name: accountName
        description: The name of the Data Lake Analytics account to which to add the
          Data Lake Store account
      - in: path
        name: dataLakeStoreAccountName
        description: The name of the Data Lake Store account to add
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The details of the Data Lake Store account
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the Azure resource group that contains the Data Lake
          Analytics account
      responses:
        200:
          description: OK
      tags:
      - Data Lake Ste Account
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---