I decided to try a Lambda function with API Gateway

Ensure that changes to the source code can be automatically tested before they are deployed
setup a CircleCI/Jenkins for automated testing on each specific branch commit 
Publishing code out to s3 bucket on successful build

Specific version of the service can be launched for testing, debugging and demos
Testing version specific Lambda deployments (WIP)
Customize API Gateway domains for 4 environments

Infrastructure and required services provisioning as well as deployment is automated and can be triggered with a click of a button or a command in a terminal
Cloudformation template to create resources and publish endpoint

Service is reasonably resilient and a single node failure does not affect end users
Service can be scaled, preferably automatically, to handle increased loads
I wanted to use a serverless architecture and Lambda scaling 
	

Alternatively I looked at a more server based Chef,Docker,Kubernetes deployment via build server triggers and kubernetes cluster would setup each application


Some Reading:
https://github.com/matsev/lambda-continuous-delivery

https://aws.amazon.com/blogs/compute/continuous-integration-deployment-for-aws-lambda-functions-with-jenkins-and-grunt-part-2/

https://read.acloud.guru/some-quick-thoughts-on-blue-green-deployment-for-lambda-with-cloudformation-ac66797984f
