# tf-module-skeleton example
simple example of tf-module-skeletion

## Usage
```
module "sample" {
   source = "github.com/ukslee/tf-module-skeleton.git?ref=master"

   sample_variable = "sample"
}
```

## Steps to test run this example
1. edit `terraform.tfvars` file to specify your credential for test environment
1. run below commands
```
$ terraform init
$ terraform plan
$ terraform apply
```