# Subscriptions and tenants
* Show subscriptions
`az account show`
id: subscription
homeTenantId: id of tenant

* Show tenants
`az account tenant list`
* Show users
`az ad user list --query [].displayName`
* login to a different tenant
`az login --tenant NAME.onmicrosoft.com --allow-no-subscriptions`
 #gives an url and a code
- Show vms
`az vm list`
* Show management groups
`az account management-group list`
`az account management-group show --name NAME`
