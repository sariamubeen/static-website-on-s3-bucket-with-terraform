# static-website-on-s3-bucket-with-terraform

This is terraform script which will help to deploy a static site on s3 buckets. 
Before running you should try to change the bucket name which is in file main.tf in the top section. After it run 
terraform init
then -> 
terraform plan ( to verify it ) 
terraform apply ( to apply the finalized changes)

However, you can also change the region of deployment in config.tf
