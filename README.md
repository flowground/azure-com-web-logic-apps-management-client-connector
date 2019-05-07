# ![LOGO](logo.png) LogicAppsManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the LogicAppsManagementClient API (version 2016-06-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/web-logicAppsManagementClient/2016-06-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:23+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the connection gateways

> Gets a list of gateways under a subscription

*Tags:* `Connection Gateways`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `api-version` - _required_ - API Version

### List of custom APIs

> Gets a list of all custom APIs for a subscription id

*Tags:* `Custom APIs`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `api-version` - _required_ - API Version
* `$top` - _optional_ - The number of items to be included in the result
* `skiptoken` - _optional_ - Skip Token

### Gets a list of installed gateways that the user is an admin of

> Gets a list of installed gateways that the user is an admin of, in a specific subscription and at a certain location

*Tags:* `Connection Gateways`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `location` - _required_ - The location
* `api-version` - _required_ - API Version

### Gets an installed gateway that the user is an admin of

> Get a specific installed gateway that the user is an admin of, in a specific subscription and at a certain location

*Tags:* `Connection Gateways`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `location` - _required_ - The location
* `gatewayId` - _required_ - Gateway ID
* `api-version` - _required_ - API Version

### Returns API definition from WSDL

> Parses the specified WSDL and extracts the API definition

*Tags:* `Custom APIs`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `location` - _required_ - The location
* `api-version` - _required_ - API Version

### Lists WSDL interfaces

> This returns the list of interfaces in the WSDL

*Tags:* `Custom APIs`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `location` - _required_ - The location
* `api-version` - _required_ - API Version

### Lists managed APIs

> Gets a list of managed APIs

*Tags:* `Managed APIs`

#### Input Parameters
* `location` - _required_ - The location
* `subscriptionId` - _required_ - Subscription Id
* `api-version` - _required_ - API Version

### Gets managed API

> Gets a managed API

*Tags:* `Managed APIs`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `location` - _required_ - The location
* `apiName` - _required_ - API name
* `api-version` - _required_ - API Version

### Lists all of the connection gateways

> Gets a list of gateways under a subscription and in a specific resource group

*Tags:* `Connection Gateways`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `resourceGroupName` - _required_ - The resource group
* `api-version` - _required_ - API Version

### Deletes a specific gateway

> Deletes a specific gateway for under a subscription and in a specific resource group

*Tags:* `Connection Gateways`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `resourceGroupName` - _required_ - The resource group
* `connectionGatewayName` - _required_ - The connection gateway name
* `api-version` - _required_ - API Version

### Gets a specific gateway

> Gets a specific gateway under a subscription and in a specific resource group

*Tags:* `Connection Gateways`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `resourceGroupName` - _required_ - The resource group
* `connectionGatewayName` - _required_ - The connection gateway name
* `api-version` - _required_ - API Version

### Updates a specific gateway

> Updates a connection gateway's tags

*Tags:* `Connection Gateways`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `resourceGroupName` - _required_ - The resource group
* `connectionGatewayName` - _required_ - The connection gateway name
* `api-version` - _required_ - API Version

### Replaces a specific gateway

> Creates or updates a specific gateway for under a subscription and in a specific resource group

*Tags:* `Connection Gateways`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `resourceGroupName` - _required_ - The resource group
* `connectionGatewayName` - _required_ - The connection gateway name
* `api-version` - _required_ - API Version

### Get all connections

> Gets a list of connections

*Tags:* `Connections`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `resourceGroupName` - _required_ - The resource group
* `$top` - _optional_ - The number of items to be included in the result
* `$filter` - _optional_ - The filter to apply on the operation
* `api-version` - _required_ - API Version

### Delete an existing connection

> Deletes a connection

*Tags:* `Connections`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `resourceGroupName` - _required_ - The resource group
* `connectionName` - _required_ - Connection name
* `api-version` - _required_ - API Version

### Get a connection

> Get a specific connection

*Tags:* `Connections`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `resourceGroupName` - _required_ - The resource group
* `connectionName` - _required_ - Connection name
* `api-version` - _required_ - API Version

### Update an existing connection

> Updates a connection's tags

*Tags:* `Connections`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `resourceGroupName` - _required_ - The resource group
* `connectionName` - _required_ - Connection name
* `api-version` - _required_ - API Version

### Replace an existing connection

> Creates or updates a connection

*Tags:* `Connections`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `resourceGroupName` - _required_ - The resource group
* `connectionName` - _required_ - Connection name
* `api-version` - _required_ - API Version

### Confirms the consent code for a connection

> Confirms consent code of a connection

*Tags:* `Connections`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `resourceGroupName` - _required_ - The resource group
* `connectionName` - _required_ - Connection name
* `api-version` - _required_ - API Version

### Lists consent links for a connection

> Lists the consent links of a connection

*Tags:* `Connections`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `resourceGroupName` - _required_ - The resource group
* `connectionName` - _required_ - Connection name
* `api-version` - _required_ - API Version

### List of custom APIs

> Gets a list of all custom APIs in a subscription for a specific resource group

*Tags:* `Custom APIs`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `resourceGroupName` - _required_ - The resource group
* `api-version` - _required_ - API Version
* `$top` - _optional_ - The number of items to be included in the result
* `skiptoken` - _optional_ - Skip Token

### Delete a custom API

> Deletes a custom API from the resource group

*Tags:* `Custom APIs`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `resourceGroupName` - _required_ - The resource group
* `apiName` - _required_ - API name
* `api-version` - _required_ - API Version

### Get a custom API

> Gets a custom API by name for a specific subscription and resource group

*Tags:* `Custom APIs`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `resourceGroupName` - _required_ - The resource group
* `apiName` - _required_ - API name
* `api-version` - _required_ - API Version

### Update an existing custom API

> Updates an existing custom API's tags

*Tags:* `Custom APIs`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `resourceGroupName` - _required_ - The resource group
* `apiName` - _required_ - API name
* `api-version` - _required_ - API Version

### Replaces an existing custom API

> Creates or updates an existing custom API

*Tags:* `Custom APIs`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `resourceGroupName` - _required_ - The resource group
* `apiName` - _required_ - API name
* `api-version` - _required_ - API Version

### Moves the custom API

> Moves a specific custom API

*Tags:* `Custom APIs`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription Id
* `resourceGroupName` - _required_ - The resource group
* `apiName` - _required_ - API name
* `api-version` - _required_ - API Version

## License

**flow**ground :- Telekom iPaaS / azure-com-web-logic-apps-management-client-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
