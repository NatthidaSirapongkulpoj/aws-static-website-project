# Architecture Notes

## Solution Overview

This project hosts a static website using Amazon S3 Static Website Hosting.

The solution is designed to provide a simple, low-cost, and scalable method for hosting static web content.

---

## Architecture Components

### User

The end user accesses the website using a web browser.

### Internet

The user's request is routed through the internet to the Amazon S3 website endpoint.

### Amazon S3 Bucket

Amazon S3 stores website assets and serves static content.

### Website Files

The website consists of:

* index.html
* style.css

---

## Request Flow

1. User enters the website URL.
2. Request reaches the Amazon S3 Website Endpoint.
3. Amazon S3 retrieves website files.
4. Website content is returned to the user's browser.
5. Browser renders the webpage.

---

## Benefits

* Low Cost
* Highly Durable
* Easy Deployment
* Minimal Maintenance

---

## Future Architecture Enhancements

* Amazon CloudFront CDN
* HTTPS Encryption
* Route 53 Custom Domain
* CI/CD Automation
