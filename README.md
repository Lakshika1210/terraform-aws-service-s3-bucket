# Service S3 Bucket

## Overview
This module provisions an AWS S3 bucket using Terraform. It is simple, reusable, and configurable.

## Usage

```hcl
module "s3" {
  source  = "app.terraform.io/nipun-org/service-s3-bucket/aws"
  version = "1.0.1"

  bucket_name = "my-bucket"
}
