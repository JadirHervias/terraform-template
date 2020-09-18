# terraform_shopper

## Setup

```bash
# Download provider plugins inside the target environment directory (/env/<environment>)
$ terraform init -input=false

# Check terraform file syntax
$ terraform validate

# Plan infraestructure
$ terraform plan -var-file=<environment>.auto.tfvars.json

# "Deploy"/execute infraestructure
$ terraform apply

# "Deploy"/execute - Omit approvement
terraform apply -auto-approve

# Destroy Infrastructura
terraform destroy

# Destroy Infrastructure - Omit approvement
terraform destroy -auto-approve
```
