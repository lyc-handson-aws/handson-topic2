# Topic 1 - Simple Http Static Website on AWS S3

###### Yuanchao Hands-on Project

###### Check better this doc and project template on Github  [here](https://github.com/lyc-handson-aws/handson-topic2)

## **Overview** 

**Project's main points**

:point_right:  AWS S3 Bucket with static website configuration

:point_right:  AWS S3 bucket with block public access disabled: allow S3 bucket to be accessed by Public

:point_right: AWS S3 Bucket with a simple native redirect rule: a predefined route(by parm) is redirected to root path(index.html), other no-existed path is redirected to error.html

## **Architecture**

the diagram below illustrates the architecture(principle) of this project:

![](images/1-architecture.png)

## **CloudFormation Stack Quick-create Link**

Click here to quickly create a same project with the same AWS resources:  [here](https://eu-west-3.console.aws.amazon.com/cloudformation/home?region=eu-west-3#/stacks/create/review?templateURL=https://s3-lyc-handson-cfstacks.s3.eu-west-3.amazonaws.com/topic2.yaml)

> the default region is  "Europe(Paris)  eu-west-3"

## **AWS Resources**

Project's AWS resourcs:

:point_right: S3 bucket

:point_right: S3 bucket policy
