# AWS S3 Static Website Hosting with CloudFront

## Project Overview

This project demonstrates how to host a static website using Amazon S3 and deliver the website through Amazon CloudFront, AWS's Content Delivery Network (CDN). CloudFront caches website content at edge locations, providing lower latency, faster page loading, and improved user experience.

## Objectives

* Create an Amazon S3 bucket.
* Upload static website files (HTML, CSS, JavaScript, and images).
* Enable Static Website Hosting on the S3 bucket.
* Configure a bucket policy to allow public read access.
* Create an Amazon CloudFront distribution using the S3 website as the origin.
* Access the website through the CloudFront distribution URL.

## AWS Services Used

* Amazon S3
* Amazon CloudFront

## Project Steps

1. Created an Amazon S3 bucket.
2. Uploaded all website files to the bucket.
3. Enabled Static Website Hosting.
4. Configured the bucket policy to allow public access.
5. Created a CloudFront distribution with the S3 website endpoint as the origin.
6. Waited for the CloudFront distribution to deploy.
7. Verified that the website was accessible through the CloudFront URL.


## Outcome

The static website was successfully hosted on Amazon S3 and delivered through Amazon CloudFront. Using CloudFront improved content delivery by caching website assets at AWS edge locations, resulting in faster load times and reduced latency for users.

## Learning Outcomes

* Learned how to host a static website using Amazon S3.
* Understood S3 bucket permissions and bucket policies.
* Configured Amazon CloudFront for content delivery.
* Gained hands-on experience with AWS storage and CDN services.

## Author

**Bikram Dash**
