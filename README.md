# AWS S3 Static Website

Basic AWS lab using Amazon S3 to host a static HTML website and applying IAM permissions.

## Objective

The objective of this lab is to understand the basic concepts of Amazon S3 storage and IAM permissions through a simple static website.

## AWS Services

- Amazon S3

- AWS IAM

## Environment

- AWS Region: us-east-1

- Bucket name: aws-s3-static-site-mpalma

- Website files: HTML AND CSS

## Architecture

User -> Amazon S3 -> Static HTML Website

## Configuration

### 1. S3 bucket

- Created an S3 bucket.

- Configured the bucket in us-east-1.

- Uploaded the website files.

- Enabled/configured the required static website functionality.

### 2. Website

The website contains:

- index.html

- style.css

The website was successfully accessed through:

- http://aws-s3-static-site-mpalma.s3-website-us-east-1.amazonaws.com/ 

### 3. IAM

Configured IAM permissions for:

- User: lab-user-3

- Permissions: s3:ListBucket and  s3:GetObject

The permissions were limited to the resources required for the lab.

#### The IAM user can:

- List the contents of the S3 bucket.
- Read objects stored in the bucket.
## Results

- The static website was successfully deployed using Amazon S3.

- IAM permissions were configured to control access to the required AWS resources.

- The IAM permissions were tested using the IAM Policy Simulator.

## Screenshots

- S3 bucket

- Uploaded website files

- Static website configuration

- Bucket policies

- IAM user/role

- IAM permissions/policy

- IAM Policy Simulator

- Website displayed in browser

## What I learned

- Basic Amazon S3 storage concepts

- Static website hosting

- Basic IAM users, roles and permissions

- Principle of least privilege

- Relationship between storage and access control in AWS
