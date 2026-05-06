# Static Website Hosting Project

## Project Overview

This project demonstrates how to host a static website using AWS cloud services. The website is designed for informational purposes and is deployed using Amazon S3 and Amazon CloudFront.

## Objective

The objective of this project is to host a static website in a secure, highly available, and cost-effective way.

## Cloud Services Used

- Amazon S3
- Amazon CloudFront
- AWS Identity and Access Management
- HTTPS through CloudFront

## Architecture

The website files are stored in a private Amazon S3 bucket. Amazon CloudFront is used as a content delivery network to securely deliver the website to users over HTTPS.

## Features

- Static HTML and CSS website
- Private S3 bucket
- CloudFront CDN
- HTTPS access
- HTTP to HTTPS redirection
- Cost-effective hosting
- High availability

## Deployment Steps

1. Created static website files using HTML and CSS.
2. Created an Amazon S3 bucket.
3. Uploaded website files to the S3 bucket.
4. Kept the S3 bucket private.
5. Created a CloudFront distribution.
6. Configured Origin Access Control.
7. Updated the S3 bucket policy to allow CloudFront access.
8. Set `index.html` as the default root object.
9. Tested the website using the CloudFront URL.

## Live Website URL

Replace this with your CloudFront URL:

https://your-cloudfront-url.cloudfront.net

## Repository

Replace this with your GitHub repository URL:

https://github.com/your-username/aws-static-website-hosting

## Security Considerations

The S3 bucket is not publicly accessible. Access is only allowed through CloudFront using Origin Access Control. The website is served over HTTPS.

## Cost Optimization

This setup is cost-effective because it uses serverless static hosting. There is no EC2 server to manage or pay for continuously. S3 stores the files cheaply, while CloudFront caches and delivers the content efficiently.

## Author

Johnny