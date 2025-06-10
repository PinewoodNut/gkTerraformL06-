terraform {
   backend "azurerm" {
      resource_group_name = "demo-rg"
      storage_account_name = "storage52087058"
      container_name = "sclab06"
      key = "demo-rg.terraform.tfstate"
   }
}
