# Terraform Azure Resource Group Module

This module creates an Azure Resource Group.

## Usage

```hcl
module "rg" {
  source   = "git::https://github.com/YOUR_ORG/terraform-azure-resource-group.git?ref=v1.0.0"
  name     = "my-resource-group"
  location = "East US"
}
