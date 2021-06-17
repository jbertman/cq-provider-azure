
# Table: azure_postgresql_server_private_endpoint_connections
Azure postgresql server private endpoint connection
## Columns
| Name        | Type           | Description  |
| ------------- | ------------- | -----  |
|server_id|uuid|Unique ID of azure_postgresql_servers table (FK)|
|resource_id|text|Resource ID of the Private Endpoint Connection|
|private_endpoint_id|text|Resource id of the private endpoint|
|private_link_service_connection_state_status|text|The private link service connection status Possible values include: 'Approved', 'Pending', 'Rejected', 'Disconnected'|
|private_link_service_connection_state_description|text|The private link service connection description|
|private_link_service_connection_state_actions_required|text|The actions required for private link service connection Possible values include: 'None'|
|provisioning_state|text|State of the private endpoint connection Possible values include: 'Approving', 'Ready', 'Dropping', 'Failed', 'Rejecting'|