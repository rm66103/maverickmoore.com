## Hosting
Site is hosted in `www.maverickmoore.com` S3 bucket.

[aws dashboard](https://s3.console.aws.amazon.com/s3/buckets/www.maverickmoore.com?region=us-east-2&tab=objects)

## Deploy
```
aws s3 sync . s3://www.maverickmoore.com 
```