# terraform-azure
Practices with terraform in AZURE cloud

az login
az account set --subcription "name subcription"

well practices

$Env:ARM_CLIENT_ID = "<APPID_VALUE>"
$Env:ARM_CLIENT_SECRET = "<PASSWORD_VALUE>"
$Env:ARM_SUBSCRIPTION_ID = "<SUBSCRIPTION_ID>"
$Env:ARM_TENANT_ID = "<TENANT_VALUE>"

create main.tf

terraform init
terraform fmt
terraform validate
terraform plan
terraform apply


#### show state terraform

terraform show.