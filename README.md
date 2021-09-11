## Terraform config file for all the projects :
This is a template containing terraform configuration for instance creation as well as k8s cluster creation in AWS
template is continously updating and then we can attach it to the ci/cd pipeline :fire: 
### prerequisites :

* Install the `terraform CLI` from [official download page](https://www.terraform.io/downloads.html)
* Create a `AWS IAM account` and grab the secret and access key and notedown the region .
* Basic knowledge about AWS required .

### How to get started :

* `terraform init` to start initiate the config file .
* `terraform plan` to see if the configuration is correct or not .
* `terraform apply` to apply the configuration to infrastructure .
