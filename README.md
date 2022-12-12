# S11-E1 Initialize Tterraform for Azure
This is to initialize terraform configuration with your Azure account.  This is created for video S11-E1 

## Step to run
1. Create a Service Principal in Azure.  See how to do this through [Azure Portal](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/guides/service_principal_client_secret#creating-a-service-principal-in-the-azure-portal) 

2. Create a file terraform.tfvars and provide Client-Id, Secret, Subscription and Tenant

3. Initialize Terraform

    terraform init

4. You can validate and see the plan

    terraform validate
    terraform plan

5. Now execute terraform

    terraform apply


