# ua-freshdesk

ConnectALL Freshdesk Adapter is developed as an extension to the Universal adapter capability of ConnectALL. This adapter specifications will let the user use Freshdesk with Webhooks to read and write the data in to Freshdesk.

Please refer to https://wiki.connectall.com/ca/latest/adapters/universal-adapter for more information

# Usecase

As a user of Freshdesk I would like to synchronize tickets to Jira, ADO or similar Project management systems for planning and implementation.

# How to use

> In order to use the Freshdesk adapter you will need to get the license from ConnectALL sales team. Please reach out to sales@connectall.com for licenses and quotes.

## Import specifications
* Download the freshdesk-config.zip from distribution directory
* Navigate to ConnectALL Universal Adapter screen
* Click on `Import Adapter` button and upload the freshdesk-config.zip

> Note: You may need to edit the descriptor to change the metadata config to map your internal project, ticket types and Field configuration to add custom field from ConnectALL UI. Refer [ConnectALL Wiki](https://wiki.connectall.com/ca/latest/adapters/universal-adapter/universal-adapter-descriptor) for more information

## Define application links
* Create an application link in ConnectALL between Freshdesk and a destination application of your choice
* Navigate to `Configuration -> Connections` screen and create a new connection to Freshdesk like `https://connectall.freshdesk.com` as the endpoint
* In the Entity mapping tab under Advanced Properties choose "Sync Type" as POLL
* Use the below REST API templates for each operation

// TODO
|Operation|API Method|Template|
|--- | --- | ---|
|QUERY MODIFIED RECORDS|GET||
|READ RECORD BY ID|GET||
|CREATE RECORD|POST||
|UPDATE RECORD|PUT||
