# aws-cloud-resume-challenge

This is my attempt at the AWS cloud resume challenge. What is the cloud resume challenge? - A series of challenges, which deepen AWS knowledge and provide an opportunity to perform technical experience using AWS. The main goal is to create and deploy a static website hosting a resume. The project was published by Forrest Brazeal. The details of the challenge can be found here https://cloudresumechallenge.dev/docs/the-challenge/aws/ 

# Architecture
![image](https://github.com/jag1020/aws-cloud-resume-challenge/assets/147641656/30fc420f-453e-4067-a3b5-a82b4bc64fbe)


Services Used:

* S3
* AWS CloudFront
* Route 53
* Certificate Manager
* AWS Lambda
* Dynamo DB
* GitHub Actions
* Terraform

# Challenge Stages
### HTML CSS & JS
To complete this step, I needed to familiarize myself with HTML, CSS, and JS as most of the code is already written for you. I simply needed to edit the HTML files with my own information and create a simple JavaScript script for counting number of visitors.
### S3, Route53 and Cloudfront
The next step is to create an S3 bucket uploaded with my static website and enable HTTPS using Cloudfront, an AWS CDN service. I also had to register a domain using route53 and configure the proper records. Finally to complete this integration I needed to request a certificate using AWS ACM and link it to my domain to establish the HTTPS connection to my website. 
### DynamoDB, Lambda and Terraform
The steps that follow include creating a DynamoDB database, writing Python Lambda functions, and using Terraform for Infrastructure as Code (IAC). I'll also be using GitHub for source control and setting up Continuous Integration and Continuous Deployment (CI/CD) for my website's frontend and backend.
### Troubleshooting Security
While completing this challenge I encountered some issues pertaining to security between the multiple AWS services. I had to troubleshoot and learn how to apply the correct IAM roles and policies to the different services (Lambda,DynamoDB,S3) for them to be able to securly communicate to eachother.

# Thank you
This challenge tested my ability to launch and configure multiple AWS services and use Infastructure as Code to deploy a static website promoting my experience and ceritifcations to potential employers. Thank you for taking the time to learn more about my experience with the AWS Cloud Resume Challenge. 
