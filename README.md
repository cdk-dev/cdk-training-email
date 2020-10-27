
# Advanced CDK Training Email Course

What: Learn advanced CDK concepts under the [CDK.dev](http://cdk.dev) umbrella

How: Email workshop like the “Blogging for devs” [https://bloggingfordevs.com/](https://bloggingfordevs.com/)

Why: Gap in the available training to advanced application development with CDK

In a series of emails, we will guide you through the process of building advanced CDK apps.

This workshop is a continuation of the AWS CDK workshop. The official CDK workshop introduces and touches on a lot of topics, but it's hard to do the jump to more complex applications without pointers and ideas on what to do next.

### Scenario:

We started introducing AWS-CDK at Moonwalk inc. and are now tasked to develop and deploy a new customer-facing application consisting of a frontend and a backend.

Our first tries with the aws-cdk in *dev* were successful, but now it's important that we adhere to company policy. That means we have to deploy the app via CI/CD pipelines, ensure security, write unit tests and deploy in DR resilient way.

### The architecture:

![image](https://user-images.githubusercontent.com/45762661/97349778-2fb9e000-1890-11eb-945e-e274b50e3f07.png)


## Topics to cover:

- CI/CD - Cross account deployment
- Multi Stack - split app/db/pipeline stack
- (Multi Account and Region?)
- Tagging
- Testing - how to write meaningful tests
- Updating/upgrading your app to newer CDK versions / Projen?
- Everything from this page: [https://openconstructfoundation.org/cdk-helpers/](https://openconstructfoundation.org/cdk-helpers/)
- Where to find 3rd party constructs and how to use em:
    - CDKpatterns.com
    - awscdk.io
    - AWS solutions lib
- How to read the documentation and find examples like Gists on Github. (Eg: How the * do I construct an EBS volume property?)
- Env variables  and context files


## Format:

This will be a series of email that are send out in a regular cadence every couple days. The idea is to split up this workshop in bite size pieces that you can follow at your own pace. 
As an alternative it can be also available in PDF format for people who dislike the format.






