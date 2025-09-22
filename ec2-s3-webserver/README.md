# EC2 Web Server + S3 Static Website

## Overview
This project demonstrates deploying a web server (EC2) that serves static content from an S3 bucket. It covers EC2, S3, IAM roles, security groups, and basic networking.

## Architecture
![Architecture](diagrams/architecture.png)

## AWS Services Used
- EC2
- S3
- IAM
- Security Groups

## Implementation Steps
1. Created S3 bucket and uploaded index.html
2. Launched EC2 instance with Apache and User Data script
3. Configured security groups to allow HTTP/SSH
4. Attached IAM role to allow EC2 access to S3
5. Tested web server by accessing public IP

## Screenshots
- `screenshots/s3-bucket-list.png`
- `screenshots/s3-bucket-properties.png`
- `screenshots/ec2-instance-dashboard.png`
- `screenshots/ec2-security-group.png`
- `screenshots/ec2-userdata.png`
- `screenshots/iam-role.png`
- `screenshots/website-output.png`

## Lessons Learned
- Proper IAM roles are critical for secure S3 access
- User Data scripts automate EC2 configuration
- Security group rules are essential to control traffic

## Notes
- EC2 instance and S3 bucket were deleted after testing to avoid charges

