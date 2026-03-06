# Azure CLI Commands Cheatsheet

> Azure CLI is Microsoft's official CLI for Azure. Create, configure, and manage Azure resources.

## Quick Reference

> **Preview** — This is a curated selection of key commands. Explore the full command list with examples, practice exercises, and more on [Command Playground](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=explore-all).

| Command | Description |
|---------|-------------|
| `az login` | Log in to Azure |
| `az logout` | Log out of Azure |
| `az account list` | List all subscriptions |
| `az account show` | Show the active subscription |
| `az account set` | Set the active subscription |
| `az account list-locations` | List all available regions |
| `az configure` | Configure Azure CLI defaults |
| `az version` | Show Azure CLI version |
| `az upgrade` | Upgrade Azure CLI to latest version |
| `az interactive` | Start interactive mode |
| `az group list` | List all resource groups |
| `az group create` | Create a new resource group |
| `az group delete` | Delete a resource group |
| `az group show` | Show resource group details |
| `az group exists` | Check if a resource group exists |
| `az group update` | Update a resource group |
| `az group export` | Export resource group as ARM template |
| `az group lock create` | Create a resource group lock |
| `az group lock list` | List resource group locks |
| `az resource list` | List all resources in a group |
| `az vm list` | List all virtual machines |
| `az vm create` | Create a new virtual machine |
| `az vm delete` | Delete a virtual machine |
| `az vm show` | Show VM details |
| `az vm start` | Start a virtual machine |
| `az vm stop` | Stop a virtual machine |
| `az vm restart` | Restart a virtual machine |
| `az vm deallocate` | Deallocate a virtual machine |
| `az vm resize` | Resize a virtual machine |
| `az vm list-sizes` | List available VM sizes |
| `az vm list-ip-addresses` | List VM IP addresses |
| `az vm open-port` | Open a port on a VM |
| `az vm run-command invoke` | Run a command on a VM |
| `az vm image list` | List available VM images |
| `az vm image list-offers` | List VM image offers |
| `az vm image list-skus` | List VM image SKUs |
| `az vm disk attach` | Attach a disk to a VM |
| `az vm disk detach` | Detach a disk from a VM |
| `az vm extension list` | List VM extensions |
| `az vm extension set` | Install a VM extension |
| `az vm availability-set create` | Create an availability set |
| `az vm availability-set list` | List availability sets |
| `az snapshot create` | Create a disk snapshot |
| `az snapshot list` | List disk snapshots |
| `az disk list` | List managed disks |
| `az disk create` | Create a managed disk |
| `az storage account list` | List storage accounts |
| `az storage account create` | Create a storage account |
| `az storage account delete` | Delete a storage account |
| `az storage account show` | Show storage account details |
| `az storage account keys list` | List storage account keys |
| `az storage account keys renew` | Regenerate a storage key |
| `az storage account show-connection-string` | Show connection string |
| `az storage container list` | List blob containers |
| `az storage container create` | Create a blob container |
| `az storage container delete` | Delete a blob container |
| `az storage blob list` | List blobs in a container |
| `az storage blob upload` | Upload a blob |
| `az storage blob download` | Download a blob |
| `az storage blob delete` | Delete a blob |
| `az storage blob copy start` | Copy a blob |
| `az storage blob url` | Get a blob URL |
| `az storage blob generate-sas` | Generate a blob SAS token |
| `az storage file list` | List files in a share |
| `az storage file upload` | Upload a file |
| `az storage file download` | Download a file |
| `az storage share list` | List file shares |
| `az storage share create` | Create a file share |
| `az storage table list` | List storage tables |
| `az storage queue list` | List storage queues |
| `az webapp list` | List all web apps |
| `az webapp create` | Create a new web app |
| `az webapp delete` | Delete a web app |
| `az webapp show` | Show web app details |
| `az webapp start` | Start a web app |
| `az webapp stop` | Stop a web app |
| `az webapp restart` | Restart a web app |
| `az webapp browse` | Open the web app in a browser |
| `az webapp deployment source config` | Configure deployment source |
| `az webapp deployment source config-zip` | Deploy from a ZIP file |
| `az webapp log tail` | Stream web app logs live |
| `az webapp log download` | Download web app logs |
| `az webapp config appsettings set` | Set app settings |
| `az webapp config appsettings list` | List app settings |
| `az webapp config connection-string set` | Set connection strings |
| `az webapp config set` | Set web app configuration |
| `az webapp identity assign` | Assign a managed identity |
| `az appservice plan list` | List App Service plans |
| `az appservice plan create` | Create an App Service plan |
| `az appservice plan delete` | Delete an App Service plan |
| `az appservice plan update` | Update an App Service plan |
| `az webapp deployment slot create` | Create a deployment slot |
| `az webapp deployment slot swap` | Swap deployment slots |
| `az webapp up` | Quick create and deploy a web app |
| `az functionapp list` | List all function apps |
| `az functionapp create` | Create a function app |
| `az functionapp delete` | Delete a function app |
| `az functionapp show` | Show function app details |
| `az functionapp start` | Start a function app |
| `az functionapp stop` | Stop a function app |
| `az functionapp restart` | Restart a function app |
| `az functionapp config appsettings set` | Set function app settings |
| `az functionapp config appsettings list` | List function app settings |
| `az functionapp deployment source config` | Configure deployment source |
| `az functionapp deployment list-publishing-profiles` | List publishing profiles |
| `az functionapp function list` | List functions in an app |
| `az functionapp function show` | Show function details |
| `az functionapp identity assign` | Assign managed identity |
| `az functionapp keys list` | List function app keys |
| `az sql server list` | List SQL servers |
| `az sql server create` | Create a SQL server |
| `az sql server delete` | Delete a SQL server |
| `az sql server show` | Show SQL server details |
| `az sql server firewall-rule create` | Create a firewall rule |
| `az sql server firewall-rule list` | List firewall rules |
| `az sql server firewall-rule delete` | Delete a firewall rule |
| `az sql db list` | List SQL databases |
| `az sql db create` | Create a SQL database |
| `az sql db delete` | Delete a SQL database |
| `az sql db show` | Show SQL database details |
| `az sql db show-connection-string` | Show database connection string |
| `az sql db copy` | Copy a SQL database |
| `az sql db export` | Export a SQL database |
| `az sql db import` | Import a SQL database |
| `az sql db restore` | Restore a SQL database |
| `az sql elastic-pool list` | List elastic pools |
| `az sql elastic-pool create` | Create an elastic pool |
| `az cosmosdb list` | List Cosmos DB accounts |
| `az cosmosdb create` | Create a Cosmos DB account |
| `az cosmosdb delete` | Delete a Cosmos DB account |
| `az cosmosdb show` | Show Cosmos DB account details |
| `az cosmosdb keys list` | List Cosmos DB keys |
| `az cosmosdb list-connection-strings` | List connection strings |
| `az cosmosdb sql database list` | List Cosmos SQL databases |
| `az cosmosdb sql database create` | Create a Cosmos SQL database |
| `az cosmosdb sql container list` | List Cosmos SQL containers |
| `az cosmosdb sql container create` | Create a Cosmos SQL container |
| `az cosmosdb mongodb database list` | List MongoDB databases |
| `az cosmosdb mongodb database create` | Create a MongoDB database |
| `az cosmosdb update` | Update Cosmos DB account |
| `az cosmosdb failover-priority-change` | Change failover priority |
| `az aks list` | List AKS clusters |
| `az aks create` | Create an AKS cluster |
| `az aks delete` | Delete an AKS cluster |
| `az aks show` | Show AKS cluster details |
| `az aks get-credentials` | Get AKS cluster kubeconfig |
| `az aks browse` | Open AKS dashboard in browser |
| `az aks scale` | Scale an AKS cluster |
| `az aks upgrade` | Upgrade an AKS cluster |
| `az aks get-upgrades` | List available AKS upgrades |
| `az aks nodepool list` | List AKS node pools |
| `az aks nodepool add` | Add a node pool |
| `az aks nodepool delete` | Delete a node pool |
| `az aks nodepool scale` | Scale a node pool |
| `az aks nodepool upgrade` | Upgrade a node pool |
| `az aks enable-addons` | Enable AKS add-ons |
| `az aks disable-addons` | Disable AKS add-ons |
| `az aks install-cli` | Install kubectl |
| `az aks get-versions` | List AKS Kubernetes versions |
| `az acr list` | List container registries |
| `az acr create` | Create a container registry |
| `az acr delete` | Delete a container registry |
| `az acr show` | Show container registry details |
| `az acr login` | Log in to a container registry |
| `az acr repository list` | List repositories in a registry |
| `az acr repository show-tags` | List image tags |
| `az acr repository delete` | Delete a repository or image |
| `az acr build` | Build an image in the cloud |
| `az acr credential show` | Show registry credentials |
| `az acr credential renew` | Regenerate registry credentials |
| `az acr import` | Import an image into a registry |
| `az acr task list` | List ACR tasks |
| `az acr task create` | Create an ACR task |
| `az acr task run` | Run an ACR task manually |
| `az network vnet list` | List virtual networks |
| `az network vnet create` | Create a virtual network |
| `az network vnet delete` | Delete a virtual network |
| `az network vnet show` | Show virtual network details |
| `az network vnet subnet list` | List subnets |
| `az network vnet subnet create` | Create a subnet |
| `az network vnet subnet delete` | Delete a subnet |
| `az network vnet subnet show` | Show subnet details |
| `az network vnet peering list` | List VNet peerings |
| `az network vnet peering create` | Create a VNet peering |
| `az network public-ip list` | List public IP addresses |
| `az network public-ip create` | Create a public IP address |
| `az network public-ip delete` | Delete a public IP address |
| `az network public-ip show` | Show public IP details |
| `az network nic list` | List network interfaces |
| `az network nic create` | Create a network interface |
| `az network nic show` | Show network interface details |
| `az network nsg list` | List network security groups |
| `az network nsg create` | Create a network security group |
| `az network nsg delete` | Delete a network security group |
| `az network nsg show` | Show NSG details |
| `az network nsg rule list` | List NSG rules |
| `az network nsg rule create` | Create an NSG rule |
| `az network nsg rule delete` | Delete an NSG rule |
| `az network nsg rule show` | Show NSG rule details |
| `az network nsg rule update` | Update an NSG rule |
| `az network application-security-group list` | List app security groups |
| `az network application-security-group create` | Create app security group |
| `az network lb list` | List load balancers |
| `az network lb create` | Create a load balancer |
| `az network lb delete` | Delete a load balancer |
| `az network lb show` | Show load balancer details |
| `az network lb frontend-ip list` | List frontend IPs |
| `az network lb frontend-ip create` | Create frontend IP |
| `az network lb address-pool list` | List backend pools |
| `az network lb address-pool create` | Create a backend pool |
| `az network lb rule list` | List load balancing rules |
| `az network lb rule create` | Create a load balancing rule |
| `az network lb probe list` | List health probes |
| `az network lb probe create` | Create a health probe |
| `az network application-gateway list` | List app gateways |
| `az network application-gateway create` | Create an app gateway |
| `az network dns zone list` | List DNS zones |
| `az network dns zone create` | Create a DNS zone |
| `az network dns zone delete` | Delete a DNS zone |
| `az network dns zone show` | Show DNS zone details |
| `az network dns record-set list` | List DNS record sets |
| `az network dns record-set a list` | List A records |
| `az network dns record-set a add-record` | Add an A record |
| `az network dns record-set a remove-record` | Remove an A record |
| `az network dns record-set cname set-record` | Set a CNAME record |
| `az network dns record-set mx add-record` | Add an MX record |
| `az network dns record-set txt add-record` | Add a TXT record |
| `az network private-dns zone list` | List private DNS zones |
| `az network private-dns zone create` | Create a private DNS zone |
| `az keyvault list` | List key vaults |
| `az keyvault create` | Create a key vault |
| `az keyvault delete` | Delete a key vault |
| `az keyvault show` | Show key vault details |
| `az keyvault secret list` | List key vault secrets |
| `az keyvault secret set` | Set a key vault secret |
| `az keyvault secret show` | Show a secret value |
| `az keyvault secret delete` | Delete a secret |
| `az keyvault key list` | List key vault keys |
| `az keyvault key create` | Create a key vault key |
| `az keyvault key show` | Show key details |
| `az keyvault key delete` | Delete a key |
| `az keyvault certificate list` | List certificates |
| `az keyvault certificate create` | Create a certificate |
| `az keyvault certificate import` | Import a certificate |
| `az keyvault set-policy` | Set key vault access policy |
| `az keyvault delete-policy` | Delete key vault access policy |
| `az keyvault recover` | Recover a deleted key vault |
| `az keyvault purge` | Permanently delete a key vault |
| `az monitor metrics list` | List metric values |
| `az monitor metrics list-definitions` | List metric definitions |
| `az monitor activity-log list` | List activity log events |
| `az monitor log-analytics workspace list` | List Log Analytics workspaces |
| `az monitor log-analytics workspace create` | Create a workspace |
| `az monitor log-analytics workspace show` | Show workspace details |
| `az monitor log-analytics workspace delete` | Delete a workspace |
| `az monitor log-analytics query` | Run a log query |
| `az monitor alert-rules list` | List alert rules |
| `az monitor metrics alert list` | List metric alerts |
| `az monitor metrics alert create` | Create a metric alert |
| `az monitor metrics alert delete` | Delete a metric alert |
| `az monitor action-group list` | List action groups |
| `az monitor action-group create` | Create an action group |
| `az monitor diagnostic-settings list` | List diagnostic settings |
| `az monitor diagnostic-settings create` | Create diagnostic settings |
| `az monitor app-insights component show` | Show App Insights details |
| `az monitor app-insights component create` | Create App Insights resource |
| `az ad user list` | List Azure AD users |
| `az ad user create` | Create an Azure AD user |
| `az ad user delete` | Delete an Azure AD user |
| `az ad user show` | Show Azure AD user details |
| `az ad user update` | Update an Azure AD user |
| `az ad group list` | List Azure AD groups |
| `az ad group create` | Create an Azure AD group |
| `az ad group delete` | Delete an Azure AD group |
| `az ad group member list` | List group members |
| `az ad group member add` | Add a member to a group |
| `az ad group member remove` | Remove a member from a group |
| `az ad sp list` | List service principals |
| `az ad sp create-for-rbac` | Create a service principal |
| `az ad sp delete` | Delete a service principal |
| `az ad sp show` | Show service principal details |
| `az ad app list` | List Azure AD applications |
| `az ad app create` | Create an Azure AD application |
| `az ad app delete` | Delete an Azure AD application |
| `az role assignment list` | List role assignments |
| `az role assignment create` | Create a role assignment |
| `az role assignment delete` | Delete a role assignment |
| `az role definition list` | List role definitions |
| `az servicebus namespace list` | List Service Bus namespaces |
| `az servicebus namespace create` | Create a Service Bus namespace |
| `az servicebus namespace delete` | Delete a Service Bus namespace |
| `az servicebus queue list` | List Service Bus queues |
| `az servicebus queue create` | Create a Service Bus queue |
| `az servicebus queue delete` | Delete a Service Bus queue |
| `az servicebus topic list` | List Service Bus topics |
| `az servicebus topic create` | Create a Service Bus topic |
| `az servicebus topic subscription list` | List topic subscriptions |
| `az servicebus topic subscription create` | Create a topic subscription |
| `az eventhubs namespace list` | List Event Hubs namespaces |
| `az eventhubs namespace create` | Create an Event Hubs namespace |
| `az eventhubs eventhub list` | List event hubs |
| `az eventhubs eventhub create` | Create an event hub |
| `az eventgrid topic list` | List Event Grid topics |
| `az eventgrid topic create` | Create an Event Grid topic |
| `az eventgrid event-subscription list` | List event subscriptions |
| `az eventgrid event-subscription create` | Create an event subscription |

## Practice & Resources

| Resource | Link |
|----------|------|
| **Practice Azure CLI interactively** | [Open Terminal](https://technoscripts.com/cli/azure-cli/?utm_source=github&utm_medium=repository&utm_campaign=cli-practice) |
| **Download PDF Cheatsheet** | [Get Cheatsheet](https://technoscripts.com/command-playground/cheatsheet/azure-cli-commands/?utm_source=github&utm_medium=repository&utm_campaign=cheatsheet) |
| **Typing Practice** | [Type Azure CLI Commands](https://technoscripts.com/command-playground/typing-practice/azure-cli/?utm_source=github&utm_medium=repository&utm_campaign=typing) |
| **All 105+ CLI Tools** | [Browse Tools Directory](https://technoscripts.com/command-playground/?utm_source=github&utm_medium=repository&utm_campaign=tools-directory) |

---

*Part of the [CLI Commands Cheatsheet](../README.md) collection by [TechnoScripts](https://technoscripts.com/?utm_source=github&utm_medium=repository&utm_campaign=tool-page)*
