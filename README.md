# Static Website on Amazon S3 using Terraform

Hosts a static website on Amazon S3 with Terraform.

## Resources
- S3 bucket with static website hosting enabled
- Public access block disabled and public-read bucket policy
- index.html uploaded to the bucket

## Usage
terraform init
terraform plan
terraform apply

## Test
Open the `website_url` output in a browser.

## Cleanup
terraform destroy

