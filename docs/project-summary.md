# Project Summary

## AWS Static Website Hosting on Amazon S3

### Project Objective

The objective of this project was to deploy a static website using Amazon S3 Static Website Hosting while gaining hands-on experience with AWS cloud services, website deployment, access control, and technical documentation.

---

## Business Scenario

Organizations often require a low-cost and highly available solution for hosting static websites such as company landing pages, portfolios, documentation sites, and internal information portals.

Amazon S3 provides a scalable and cost-effective solution for serving static web content without the need to manage servers.

---

## Solution Overview

A static website was developed using HTML and CSS and deployed to Amazon S3.

The project included:

* S3 Bucket Creation
* Static Website Hosting Configuration
* Public Access Management
* Bucket Policy Configuration
* Website Deployment
* Architecture Documentation
* GitHub Version Control

---

## Architecture

User → Internet → Amazon S3 Static Website Endpoint → Website Files

Website Files:

* index.html
* style.css

---

## AWS Services Used

| Service                | Purpose                |
| ---------------------- | ---------------------- |
| Amazon S3              | Static website hosting |
| Bucket Policy          | Public website access  |
| AWS Management Console | Resource management    |

---

## Key Challenges

### Access Denied (403)

Issue:

The website was inaccessible after deployment.

Resolution:

* Disabled Block Public Access
* Configured Bucket Policy
* Verified Website Endpoint Settings

### Git Commit Failure

Issue:

Git refused to create commits due to missing user identity configuration.

Resolution:

Configured:

* git config --global user.name
* git config --global user.email

---

## Skills Demonstrated

* AWS S3
* Static Website Hosting
* Cloud Architecture Documentation
* Git and GitHub
* Troubleshooting
* Technical Documentation
* HTML and CSS Fundamentals

---

## Project Outcome

Successfully deployed a publicly accessible static website hosted on Amazon S3 and documented the deployment process following cloud engineering best practices.

---

## Future Enhancements

* Amazon CloudFront CDN
* HTTPS with AWS Certificate Manager
* Route 53 Custom Domain
* GitHub Actions CI/CD Pipeline
* Terraform Infrastructure as Code
