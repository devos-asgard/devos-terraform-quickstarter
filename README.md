# Getting started with DevOS Terraform Provisioning

Use this project for an exercise when getting started on the DevOS Terraform Provisioning feature. 
This exercise provisions AWS EC2 instances using DevOS Terraform Provisioning feature.

## Examples of the extra variables when you create a provisioing
- key_pair: Enter the key pair name.
  - i.e.: "ec2-key-pair"
- region: Enter the region.
  - i.e.: "ap-northeast-1"
- security_groups: Enter the security group ID.
  - i.e.: ["sg-xxxxxxxxxxx"]
- subnet_id: Enter the subnet ID.
  - i.e.: "subnet-xxxxxxxx"
- ec2_name: Enter a name for your EC2 instance that will be created.
  - i.e.: "demo-instance"
- instance_type: Enter the instance type.
  - i.e.: "t2.micro"
- Assign a Public IPv4 address
  - i.e.: true
                    
