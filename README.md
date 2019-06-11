# ![LOGO](logo.png) Security Center **flow**ground Connector

## Description

A generated **flow**ground connector for the Security Center API (version 2015-06-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/security-tasks/2015-06-01-preview/swagger.json<br/>
Generated at: 2019-06-11T18:14:16+03:00

## API Description

API spec for Microsoft.Security (Azure Security Center) resource provider

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Recommended tasks that will help improve the security of the subscription proactively

*Tags:* `Tasks`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
* `subscriptionId` - _required_ - Azure subscription ID
* `ascLocation` - _required_ - The location where ASC stores the data of the subscription. can be retrieved from Get locations
* `$filter` - _optional_ - OData filter. Optional.

### Recommended tasks that will help improve the security of the subscription proactively

*Tags:* `Tasks`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
* `subscriptionId` - _required_ - Azure subscription ID
* `ascLocation` - _required_ - The location where ASC stores the data of the subscription. can be retrieved from Get locations
* `taskName` - _required_ - Name of the task object, will be a GUID

### Recommended tasks that will help improve the security of the subscription proactively

*Tags:* `Tasks`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
* `subscriptionId` - _required_ - Azure subscription ID
* `ascLocation` - _required_ - The location where ASC stores the data of the subscription. can be retrieved from Get locations
* `taskName` - _required_ - Name of the task object, will be a GUID
* `taskUpdateActionType` - _required_ - Type of the action to do on the task
    Possible values: Activate, Dismiss, Start, Resolve, Close.

### Recommended tasks that will help improve the security of the subscription proactively

*Tags:* `Tasks`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
* `subscriptionId` - _required_ - Azure subscription ID
* `$filter` - _optional_ - OData filter. Optional.

### Recommended tasks that will help improve the security of the subscription proactively

*Tags:* `Tasks`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `ascLocation` - _required_ - The location where ASC stores the data of the subscription. can be retrieved from Get locations
* `$filter` - _optional_ - OData filter. Optional.

### Recommended tasks that will help improve the security of the subscription proactively

*Tags:* `Tasks`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `ascLocation` - _required_ - The location where ASC stores the data of the subscription. can be retrieved from Get locations
* `taskName` - _required_ - Name of the task object, will be a GUID

### Recommended tasks that will help improve the security of the subscription proactively

*Tags:* `Tasks`

#### Input Parameters
* `api-version` - _required_ - API version for the operation
* `subscriptionId` - _required_ - Azure subscription ID
* `resourceGroupName` - _required_ - The name of the resource group within the user's subscription. The name is case insensitive.
* `ascLocation` - _required_ - The location where ASC stores the data of the subscription. can be retrieved from Get locations
* `taskName` - _required_ - Name of the task object, will be a GUID
* `taskUpdateActionType` - _required_ - Type of the action to do on the task
    Possible values: Activate, Dismiss, Start, Resolve, Close.

## License

**flow**ground :- Telekom iPaaS / azure-com-security-tasks-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
