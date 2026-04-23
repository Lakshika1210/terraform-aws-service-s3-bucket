# Service S3 Bucket

## Overview
This module creates an AWS S3 bucket.

## Usage

```hcl
module "s3" {
  source  = "app.terraform.io/nipun-org/service-s3-bucket/aws"
  version = "1.0.0"

  bucket_name = "my-bucket"
}
