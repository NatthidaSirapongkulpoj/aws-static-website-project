# Lessons Learned

## Project Overview

This project involved deploying a static website using Amazon S3 Static Website Hosting.

The objective was to gain hands-on experience with AWS cloud services and understand the deployment process for static web applications.

---

## Skills Gained

Through this project, I developed practical experience in:

* Amazon S3 Bucket Creation
* Static Website Hosting
* Bucket Policy Configuration
* Public Access Management
* Git and GitHub Version Control
* Basic HTML and CSS Deployment
* Cloud Architecture Documentation

---

## Challenges Encountered

### Challenge 1: Access Denied (403 Forbidden)

Issue:

After enabling Static Website Hosting, the website displayed an AccessDenied error.

Root Cause:

The S3 bucket policy and public access settings were not configured correctly.

Resolution:

* Disabled Block Public Access
* Configured Bucket Policy to allow public read access
* Verified website endpoint configuration

---

### Challenge 2: Git Commit Failure

Issue:

Git refused to create commits.

Error:

Author identity unknown

Root Cause:

Git user name and email were not configured.

Resolution:

Configured Git identity using:

git config --global user.name
git config --global user.email

---

## Key Takeaways

* Understanding S3 permissions is critical.
* Static Website Hosting requires both hosting configuration and access permissions.
* Git configuration is required before committing code.
* Documentation improves project maintainability and professionalism.

---

## Future Improvements

Planned enhancements for the next version:

* Amazon CloudFront CDN
* HTTPS using AWS Certificate Manager
* Route 53 Custom Domain
* GitHub Actions CI/CD Pipeline
* Infrastructure as Code using Terraform

---

## Overall Outcome

Successfully deployed a static website on Amazon S3 and documented the solution following cloud engineering best practices.
