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
To complete this step, I needed to familiarize myself with HTML, CSS, and JS as most of the code is already written for you. You simply need to edit the HTML files with your own information and create a simple JavaScript script for counting number of visitors.
### S3, Route53 and Cloudfront
The next step is to create an S3 bucket uploaded with my static website and enable HTTPS using Cloudfront, an AWS CDN service. I also had to register a domain using route53 and configure the proper records. Finally to complete this integration I needed to request a certificate using AWS ACM and link it to my domain to establish the HTTPS connection to my website. 
### Wrapping it all up
The steps that follow include creating a DynamoDB database, writing Python Lambda functions, and using Terraform for Infrastructure as Code (IAC). I'll also be using GitHub for source control and setting up Continuous Integration and Continuous Deployment (CI/CD) for my website's frontend and backend.
