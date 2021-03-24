
# Space Hellas Microsoft Azure Lighthouse - Arc

We offer managed services through Azure Lighthouse and Arc suited to meet our customers' Cloud transformation objectives: administration  and service management of the cloud migrated infrastructure, technical support, automation and governance. Azure Lighthouse provides capabilities to perform cross-tenant management at scale.  We do this by having the ability to view and manage multiple customers from a single context. [Learn more](https://azure.com/lighthouse).

As far as Managed Services Space Hellas provides NOC/SOC facilities located in EU and provide 24 hour level -1 support while local skills can be use to interact with our customers.

## Space Hellas Service Desk - 1st Level Support and Ticket Management

Space Hellas Service Desk is responsible 24/7 to receive new support requests from our customers via phone or Customer's ticketing system. Service Desk engineers are responsible to escalate each support case to the appropriate Azure engineer (2nd level). 

## Service Desk Telephones:
* +30-210-6504433 – Mon-Fri 7:00 – 20:00 local time
* +30-210-6504230 – After working hours and Weekends        
* Service Desk Email: tac@space.gr 

### Space Hellas Managed Services Templates
This repository contains samples to help you use Azure Resource Manager to oboard configure [Azure delegated resource management](https://docs.microsoft.com/azure/lighthouse/concepts/azure-delegated-resource-management) and to configure monitoring and management of customer environments.

The templates shown below can be used to [onboard new customers to Azure Lighthouse](https://docs.microsoft.com/en-us/azure/lighthouse/how-to/onboard-customer). You can deploy these manually, or use the "Deploy to Azure" buttons to deploy directly in the Azure portal.
# Deploy to Azure buttons

Name | Description   | Auto-deploy   | Manual deploy |
-----| ------------- |--------------- |------- 
| Azure Lighthouse - Subscription Deployment |onboard a *subscription* | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Lighthouse-samples%2Fmaster%2Ftemplates%2Fdelegated-resource-management%2FdelegatedResourceManagement.json) | [templates](https://github.com/Azure/Azure-Lighthouse-samples/tree/master/templates/delegated-resource-management)
| Azure Lighthouse - Resource Group Deployment | onboard a *resource group* | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Lighthouse-samples%2Fmaster%2Ftemplates%2Frg-delegated-resource-management%2FrgDelegatedResourceManagement.json) | [templates](https://github.com/Azure/Azure-Lighthouse-samples/tree/master/templates/rg-delegated-resource-management)
| Azure Lighthouse - Multiple Resource Group Deployment | onboard multiple *resource groups* | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Lighthouse-samples%2Fmaster%2Ftemplates%2Frg-delegated-resource-management%2FmultipleRgDelegatedResourceManagement.json) | [templates](https://github.com/Azure/Azure-Lighthouse-samples/tree/master/templates/rg-delegated-resource-management)
| Azure Lighthouse + Azure AD PIM - Subscription Deployment  | onboard a *subscriptions* using **Azure AD PIM** (preview) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Lighthouse-samples%2Fmaster%2Ftemplates%2Fdelegated-resource-management-eligible-authorizations%2FdelegatedResourcemanagement-eligible-authorizations.json) | [templates](https://github.com/Azure/Azure-Lighthouse-samples/tree/master/templates/delegated-resource-management-eligible-authorizations)
| Azure Lighthouse + Azure AD PIM - Resource Group Deployment | onboard a *resource groups using **Azure AD PIM** (preview) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Lighthouse-samples%2Fmaster%2Ftemplates%2Frg-delegatedResourceManagement-eligible-authorizations%2Frg-delegatedResourcemanagement-eligible-authorizations.json) | [templates](https://github.com/Azure/Azure-Lighthouse-samples/tree/master/templates/rg-delegatedResourceManagement-eligible-authorizations)
| Azure Lighthouse + Azure AD PIM - Multiple Resource Group Deployment | onboard multiple *resource groups* using **Azure AD PIM** (preview) | [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzure-Lighthouse-samples%2Fmaster%2Ftemplates%2Frg-delegatedResourceManagement-eligible-authorizations%2FmultipleRgDelegatedResourceManagement-eligible-authorizations.json) | [templates](https://github.com/Azure/Azure-Lighthouse-samples/tree/master/templates/rg-delegatedResourceManagement-eligible-authorizations)


