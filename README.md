Serverless Image Processing

Description: Automatically resize or compress images uploaded to S3.

Services Used: S3, Lambda, CloudWatch

Tasks:

Create an S3 bucket for uploads.

Trigger a Lambda function when an image is uploaded.

Lambda resizes/compresses the image and stores it in another S3 bucket.

Monitor Lambda execution in CloudWatch logs.
