# cfn-s3-cloudfront-route53-acm

## Jekyll Website

```
                    [CloudFormation Template]
|---------------------------------------------------------------------|
|           (Resolve Domain name)                                     |
|         |-->[Amazon Route53]                                        |
|         |                               (Get contents)              |
|         |                     |-->[Amazon S3 contents Bucket]       |
| Users---|-->[AWS CloudFront]--|                                     |
|         |                     |-->[Amazon S3 Logging Bucket]        |
|         |                               (Save Logs)                 |
|         |-->[AWS Certificate Manager]                               |
|---------------------------------------------------------------------|
```
