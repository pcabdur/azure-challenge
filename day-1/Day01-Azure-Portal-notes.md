📘 Azure Resource Groups – Summary Notes
What is a Resource Group?
A logical container that holds related Azure resources like VMs, storage, and databases.

Why Use Resource Groups?

Manage billing, permissions, and policies

Group resources by project or app

Delete all resources at once

Azure CLI Commands:

# Create RG
az group create --name rg-az204-cli --location "Central India"

# List RGs
az group list --output table

# Delete RG
az group delete --name rg-az204-cli --yes --no-wait
