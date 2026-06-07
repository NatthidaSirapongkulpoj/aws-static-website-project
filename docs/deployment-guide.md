# Deployment Guide

## Objective

Deploy a static website using Amazon S3 Static Website Hosting.

## Prerequisites

* AWS Account
* GitHub Account
* Git
* VS Code

## Deployment Steps

### Step 1: Create S3 Bucket

1. Open AWS Console
2. Navigate to Amazon S3
3. Create a new bucket
4. Select the desired AWS Region

### Step 2: Upload Website Files

Upload:

* index.html
* style.css

to the S3 bucket.

### Step 3: Enable Static Website Hosting

1. Open Bucket Properties
2. Enable Static Website Hosting
3. Set index document as:

index.html

### Step 4: Configure Public Access

1. Disable Block Public Access
2. Add Bucket Policy to allow public read access

### Step 5: Verify Deployment

Open the S3 Website Endpoint URL and verify that the website loads successfully.

## Result

The static website is publicly accessible through the Amazon S3 Website Endpoint.
