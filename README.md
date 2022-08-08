AWS S3 Terraform Module
===========

A terraform module to create a S3 bucket in AWS.

Module Input Variables
----------------------

- `bucket_name` - (Required) Name of the bucket


Usage
-----

```hcl
module "my_s3_bucket" {
  source = "./modules/terraform-aws-s3"

  name = "my-bucket-name"
}
```


Outputs
=======

 - `bucket_name` - The name of the bucket.
