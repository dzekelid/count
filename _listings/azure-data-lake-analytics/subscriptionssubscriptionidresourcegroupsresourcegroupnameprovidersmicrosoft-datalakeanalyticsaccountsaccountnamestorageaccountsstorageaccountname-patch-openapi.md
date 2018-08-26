---
swagger: "2.0"
x-collection-name: Azure Data Lake Analytics
x-complete: 0
info:
  title: Azure Data Lake Analytics API Storage Accounts Update
  description: Updates the Data Lake Analytics account to replace Azure Storage blob
    account details, such as the access key and/or suffix.
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