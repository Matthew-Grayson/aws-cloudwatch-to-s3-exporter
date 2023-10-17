# aws-cloudwatch-to-s3-exporter
AWS Lambda function that exports CloudWatch log groups to an S3 bucket daily; coded in TypeScript using AWS SDK for JavaScript v3.
This project is coded to create a production lambda and a staging lambda that each export only their respective logs. This means only buckets tagged with stage: staging would be exported by the staging lambda.
