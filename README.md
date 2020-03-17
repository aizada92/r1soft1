R1soft Module
This module is used for creating R1soft
Prerequisites
Terraform 0.11.14
Steps
Edit the file below
https://github.com/aizada92/r1soft1.git
cd infrastructure/r1soft/
vi configurations/r1soft.tfvars
edit backend.tf and put your bucket name 
source setenv.sh configurations/r1soft.rfvars 
terraform apply -var-file configurations/r1soft.rfvars 

