# Complete ELB example

Configuration in this directory creates ELB, EC2 instances and attach them together.

This example also creates ACM SSL certificate which can be attached to a secure listener in ELB.

Data sources are used to discover existing VPC resources (VPC, subnet and security group).

## Usage

To run this example you need to execute:

```bash
$ terraform init
$ terraform plan
$ terraform apply
```
Please also create a key_name variable to access the EC2 instance  
