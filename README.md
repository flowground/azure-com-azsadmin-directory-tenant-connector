# ![LOGO](logo.png) SubscriptionsManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the SubscriptionsManagementClient API (version 2015-11-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/azsadmin-DirectoryTenant/2015-11-01/swagger.json<br/>
Generated at: 2019-06-11T18:13:34+03:00

## API Description

The Admin Subscriptions Management Client.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all the directory tenants under the current subscription and given resource group name.

*Tags:* `DirectoryTenants`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription.The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group the resource is located under.
* `api-version` - _required_ - Client Api Version.

### Delete a directory tenant under a resource group.

*Tags:* `DirectoryTenants`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription.The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group the resource is located under.
* `tenant` - _required_ - Directory tenant name.
* `api-version` - _required_ - Client Api Version.

### Get a directory tenant by name.

*Tags:* `DirectoryTenants`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription.The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group the resource is located under.
* `tenant` - _required_ - Directory tenant name.
* `api-version` - _required_ - Client Api Version.

### Create or updates a directory tenant.

*Tags:* `DirectoryTenants`

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription.The subscription ID forms part of the URI for every service call.
* `resourceGroupName` - _required_ - The resource group the resource is located under.
* `tenant` - _required_ - Directory tenant name.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-azsadmin-directory-tenant-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
