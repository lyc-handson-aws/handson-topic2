# Yuanchao Hands-on project - Topic 1 - Simple Http Static Website on AWS S3

## **Overview** 

In this project,  it's a static website hosted on we are going to deploy a simple static website to S3 bucket via AWS CloudFormation in three simple steps:
:point_right: Step 1. Create a simple static web app via Angular
:point_right: Step 2. Create S3 bucket and its policy, and configure it to host a static website
:point_right: Step 3. Build and deploy static website manually to newly created S3 bucket (optional, you can skip it and go to [Module 2](https://dev.to/tiamatt/aws-project-module-2-automate-the-build-of-a-static-website-on-aws-s3-via-codebuild-and-cloudformation-nc2) for build automation)

> In [next](https://dev.to/tiamatt/aws-project-module-2-automate-the-build-of-a-static-website-on-aws-s3-via-codebuild-and-cloudformation-nc2) module we will automate the deployment via CodeBuild.

As I’m strongly against managing environments manually and take Infrastructure as Code for granted (if we are not on the same page, I’d suggest you to read [this](https://www.simplethread.com/why-infrastructure-as-code/) article first), AWS CloudFormation can be a great choice to provision and manage the complete infrastructure and AWS resources in a text file. 

## **Architecture**

the diagram below illustrates the architecture(principle) of this project:

![](images/1-architecture.png)

## **CloudFormation Stack Quick-create Link**

Click here to quickly create a same environment with the same AWS resources:  [here](https://eu-west-3.console.aws.amazon.com/cloudformation/home?region=eu-west-3#/stacks/create/review?templateURL=https://s3-lyc-handson-cfstacks.s3.eu-west-3.amazonaws.com/topic1.yaml)

> the default region is  "Europe(Paris)  eu-west-3"

## **AWS Resources**

Here is the list of AWS resources used in this project:
:point_right: S3 bucket
:point_right: S3 bucket policy
