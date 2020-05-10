# AWS Jenkins Pipeline
This is a DevOps project where I've executed an AWS Jenkins pipeline with two stages to check for syntax errors on a html file using Linting and uploads it to an S3 bucket.
## Requirements
* EC2 Instance (Ubuntu Server 18.0+)
* Jenkins Plugin: Blue Ocean aggregator
* Jenkins Plugin: pipeline-aws
* Jenkins Plugin: Credentials API
* Jenkins Plugin: Git and Github
* Jenkins file in a repository to execute the two stages
## Other Requirements 
IAM user with the following policies 
* AmazonEC2FullAccess
* AmazonVPCFullAccess
* AmazonS3FullAccess
Security Group with Port 22 Access and Port 8080 Access for EC2 Instance hosting Jenkins. 

Network and Server setup can also be done using CloudFormation - Optional !
