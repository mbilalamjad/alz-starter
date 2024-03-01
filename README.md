# ALZ Starter

### Step 1. Update version of module in main.tf file and version of provider in terraform.tf to latest

## Core Resources Deployment Phase 1
### Step 2. Update the following variables after which run the following commands
az login
terraform init
terraform plan
terraform apply
For more details see here https://github.com/Azure/terraform-azurerm-caf-enterprise-scale/wiki/%5BExamples%5D-Deploy-Demo-Landing-Zone-Archetypes

## Management Resources Deployment  Phase 2
### Step 3. Update the following variable to true and udpdate settings.management.tf after which run the following commands
terraform plan
terraform apply
for more details https://github.com/Azure/terraform-azurerm-caf-enterprise-scale/wiki/%5BExamples%5D-Deploy-Management-Resources-With-Custom-Settings

## Connectivity Resources Deployment  Phase 3
### Step 4. Update the following variable to true and udpdate settings.connectivity.tf after which run the following commands
terraform plan
terraform apply
for more details https://github.com/Azure/terraform-azurerm-caf-enterprise-scale/wiki/%5BExamples%5D-Deploy-Connectivity-Resources-With-Custom-Settings

## Identity Resources Deployment  Phase 4
### Step 5. Update the following variable to true and udpdate settings.identity.tf after which run the following commands
terraform plan
terraform apply
for more details https://github.com/Azure/terraform-azurerm-caf-enterprise-scale/wiki/%5BExamples%5D-Deploy-Identity-Resources-With-Custom-Settings
