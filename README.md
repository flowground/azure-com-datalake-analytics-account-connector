# ![LOGO](logo.png) DataLakeAnalyticsAccountManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the DataLakeAnalyticsAccountManagementClient API (version 2016-11-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/datalake-analytics-account/2016-11-01/swagger.json<br/>
Generated at: 2019-05-07T17:37:58+03:00

## API Description

Creates an Azure Data Lake Analytics account management client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available Data Lake Analytics REST API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.

### Gets the first page of Data Lake Analytics accounts, if any, within the current subscription. This includes a link to the next page, if any.

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Gets subscription-level properties and limits for Data Lake Analytics specified by resource location.

*Tags:* `Locations`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - The resource location without whitespace.
* `api-version` - _required_ - Client Api Version.

### Checks whether the specified account name is available or taken.

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `location` - _required_ - The resource location without whitespace.
* `api-version` - _required_ - Client Api Version.

### Gets the first page of Data Lake Analytics accounts, if any, within a specific resource group. This includes a link to the next page, if any.

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Begins the delete process for the Data Lake Analytics account object specified by the account name.

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `api-version` - _required_ - Client Api Version.

### Gets details of the specified Data Lake Analytics account.

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `api-version` - _required_ - Client Api Version.

### Updates the Data Lake Analytics account object specified by the accountName with the contents of the account object.

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `api-version` - _required_ - Client Api Version.

### Creates the specified Data Lake Analytics account. This supplies the user with computation services for Data Lake Analytics workloads.

*Tags:* `Accounts`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `api-version` - _required_ - Client Api Version.

### Lists the Data Lake Analytics compute policies within the specified Data Lake Analytics account. An account supports, at most, 50 policies

*Tags:* `ComputePolicies`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `api-version` - _required_ - Client Api Version.

### Deletes the specified compute policy from the specified Data Lake Analytics account

*Tags:* `ComputePolicies`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `computePolicyName` - _required_ - The name of the compute policy to delete.
* `api-version` - _required_ - Client Api Version.

### Gets the specified Data Lake Analytics compute policy.

*Tags:* `ComputePolicies`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `computePolicyName` - _required_ - The name of the compute policy to retrieve.
* `api-version` - _required_ - Client Api Version.

### Updates the specified compute policy.

*Tags:* `ComputePolicies`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `computePolicyName` - _required_ - The name of the compute policy to update.
* `api-version` - _required_ - Client Api Version.

### Creates or updates the specified compute policy. During update, the compute policy with the specified name will be replaced with this new compute policy. An account supports, at most, 50 policies

*Tags:* `ComputePolicies`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `computePolicyName` - _required_ - The name of the compute policy to create or update.
* `api-version` - _required_ - Client Api Version.

### Gets the first page of Data Lake Store accounts linked to the specified Data Lake Analytics account. The response includes a link to the next page, if any.

*Tags:* `DataLakeStoreAccounts`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `$filter` - _optional_ - OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Updates the Data Lake Analytics account specified to remove the specified Data Lake Store account.

*Tags:* `DataLakeStoreAccounts`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `dataLakeStoreAccountName` - _required_ - The name of the Data Lake Store account to remove
* `api-version` - _required_ - Client Api Version.

### Gets the specified Data Lake Store account details in the specified Data Lake Analytics account.

*Tags:* `DataLakeStoreAccounts`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `dataLakeStoreAccountName` - _required_ - The name of the Data Lake Store account to retrieve
* `api-version` - _required_ - Client Api Version.

### Updates the specified Data Lake Analytics account to include the additional Data Lake Store account.

*Tags:* `DataLakeStoreAccounts`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `dataLakeStoreAccountName` - _required_ - The name of the Data Lake Store account to add.
* `api-version` - _required_ - Client Api Version.

### Lists the Data Lake Analytics firewall rules within the specified Data Lake Analytics account.

*Tags:* `FirewallRules`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `api-version` - _required_ - Client Api Version.

### Deletes the specified firewall rule from the specified Data Lake Analytics account

*Tags:* `FirewallRules`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `firewallRuleName` - _required_ - The name of the firewall rule to delete.
* `api-version` - _required_ - Client Api Version.

### Gets the specified Data Lake Analytics firewall rule.

*Tags:* `FirewallRules`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `firewallRuleName` - _required_ - The name of the firewall rule to retrieve.
* `api-version` - _required_ - Client Api Version.

### Updates the specified firewall rule.

*Tags:* `FirewallRules`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `firewallRuleName` - _required_ - The name of the firewall rule to update.
* `api-version` - _required_ - Client Api Version.

### Creates or updates the specified firewall rule. During update, the firewall rule with the specified name will be replaced with this new firewall rule.

*Tags:* `FirewallRules`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `firewallRuleName` - _required_ - The name of the firewall rule to create or update.
* `api-version` - _required_ - Client Api Version.

### Gets the first page of Azure Storage accounts, if any, linked to the specified Data Lake Analytics account. The response includes a link to the next page, if any.

*Tags:* `StorageAccounts`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `$filter` - _optional_ - The OData filter. Optional.
* `$top` - _optional_ - The number of items to return. Optional.
* `$skip` - _optional_ - The number of items to skip over before returning elements. Optional.
* `$select` - _optional_ - OData Select statement. Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description. Optional.
* `$orderby` - _optional_ - OrderBy clause. One or more comma-separated expressions with an optional "asc" (the default) or "desc" depending on the order you'd like the values sorted, e.g. Categories?$orderby=CategoryName desc. Optional.
* `$count` - _optional_ - The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true. Optional.
* `api-version` - _required_ - Client Api Version.

### Updates the specified Data Lake Analytics account to remove an Azure Storage account.

*Tags:* `StorageAccounts`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `storageAccountName` - _required_ - The name of the Azure Storage account to remove
* `api-version` - _required_ - Client Api Version.

### Gets the specified Azure Storage account linked to the given Data Lake Analytics account.

*Tags:* `StorageAccounts`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `storageAccountName` - _required_ - The name of the Azure Storage account for which to retrieve the details.
* `api-version` - _required_ - Client Api Version.

### Updates the Data Lake Analytics account to replace Azure Storage blob account details, such as the access key and/or suffix.

*Tags:* `StorageAccounts`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `storageAccountName` - _required_ - The Azure Storage account to modify
* `api-version` - _required_ - Client Api Version.

### Updates the specified Data Lake Analytics account to add an Azure Storage account.

*Tags:* `StorageAccounts`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `storageAccountName` - _required_ - The name of the Azure Storage account to add
* `api-version` - _required_ - Client Api Version.

### Lists the Azure Storage containers, if any, associated with the specified Data Lake Analytics and Azure Storage account combination. The response includes a link to the next page of results, if any.

*Tags:* `StorageAccounts`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `storageAccountName` - _required_ - The name of the Azure storage account from which to list blob containers.
* `api-version` - _required_ - Client Api Version.

### Gets the specified Azure Storage container associated with the given Data Lake Analytics and Azure Storage accounts.

*Tags:* `StorageAccounts`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `storageAccountName` - _required_ - The name of the Azure storage account from which to retrieve the blob container.
* `containerName` - _required_ - The name of the Azure storage container to retrieve
* `api-version` - _required_ - Client Api Version.

### Gets the SAS token associated with the specified Data Lake Analytics and Azure Storage account and container combination.

*Tags:* `StorageAccounts`

#### Input Parameters
* `subscriptionId` - _required_ - Get subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The name of the Azure resource group.
* `accountName` - _required_ - The name of the Data Lake Analytics account.
* `storageAccountName` - _required_ - The name of the Azure storage account for which the SAS token is being requested.
* `containerName` - _required_ - The name of the Azure storage container for which the SAS token is being requested.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-datalake-analytics-account-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
