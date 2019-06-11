# ![LOGO](logo.png) MonitorManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the MonitorManagementClient API (version 2016-03-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/monitor-logProfiles_API/2016-03-01/swagger.json<br/>
Generated at: 2019-06-11T18:14:03+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List the log profiles.

*Tags:* `LogProfiles`

#### Input Parameters
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription Id.

### Deletes the log profile.

*Tags:* `LogProfiles`

#### Input Parameters
* `logProfileName` - _required_ - The name of the log profile.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription Id.

### Gets the log profile.

*Tags:* `LogProfiles`

#### Input Parameters
* `logProfileName` - _required_ - The name of the log profile.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription Id.

### Updates an existing LogProfilesResource. To update other fields use the CreateOrUpdate method.

#### Input Parameters
* `subscriptionId` - _required_ - The Azure subscription Id.
* `logProfileName` - _required_ - The name of the log profile.
* `api-version` - _required_ - Client Api Version.

### Create or update a log profile in Azure Monitoring REST API.

*Tags:* `LogProfiles`

#### Input Parameters
* `logProfileName` - _required_ - The name of the log profile.
* `api-version` - _required_ - Client Api Version.
* `subscriptionId` - _required_ - The Azure subscription Id.

## License

**flow**ground :- Telekom iPaaS / azure-com-monitor-log-profiles-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
