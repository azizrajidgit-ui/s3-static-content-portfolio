# S3 Static Content Hosting Portfolio Project

## Overview
AWS S3 bucket provisioning with controlled public object access.

### Technologies Used
- AWS CLI v2
- Amazon S3
- EC2 Instance (Ubuntu 26.04 LTS)

### Skills Demonstrated
- S3 bucket provisioning via CLI
- Object-level public ACLs (not bucket-wide)
- Public access block configuration
- Multi-interface verification (Console + CLI)

## Architecture
This project creates a publicly accessible S3 bucket where only specific objects (not the entire bucket) are exposed.

## Prerequisites
- AWS Account with IAM credentials
- EC2 Instance (Linux)
- AWS CLI v2 installed


### 1. EC2 Instance Running
![EC2 Instance List](screenshots/01-ec2-instances-list.png)

### 2. SSH Connection Established
![SSH Connected](screenshots/02-ssh-connected-terminal.png)

### 3. AWS CLI Version Check
![AWS CLI Version](screenshots/03-aws-cli-version-check.png)

### 4. IAM User Created
![IAM User](screenshots/04-iam-user-created.png)

### 5. Access Keys Retrieved
![Access Keys](screenshots/05-access-keys-downloaded.png)

### 6. S3 Bucket Permissions — Block Public Access OFF
![S3 Permissions](screenshots/06-s3-bucket-permissions.png)

### 7. S3 Object Ownership — Bucket Owner Preferred
![S3 Ownership ACL](screenshots/07-s3-ownership-acl.png)

### 8. HTML File Creation
![HTML Creation](screenshots/08-html-file-creation.png)

### 9. Bucket Listing & ACL Verification
![Bucket Listing & ACL](screenshots/09-bucket-listing-and-acl.png)

### 10. Browser Showing Live S3 Page
![Browser Live](screenshots/10-browser-page-live.png)

