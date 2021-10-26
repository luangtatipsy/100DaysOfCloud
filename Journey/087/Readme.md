# Building a ZIP File Archive
## Cloud Research
Today, I've learned about how to build a ZIP file archive. To build your serverless application as a .zip file archive, declare PackageType: Zip for your serverless function. AWS SAM builds your application for the architecture that you specify. If you don't specify an architecture, AWS SAM uses x86_64 by default. If your Lambda function depends on packages that have natively compiled programs, use the `--use-container` flag. This flag locally compiles your functions in a Docker container that behaves like a Lambda environment, so they're in the right format when you deploy them to the AWS Cloud.

When you use the `--use-container` option, by default AWS SAM pulls the container image from Amazon ECR Public. If you would like to pull a container image from another repository, for example DockerHub, you can use the `--build-image` option and provide the URI of an alternate container image. Following are two example commands for building applications using container images from the DockerHub repository

```yaml
# Build a Node.js 12 application using a container image pulled from DockerHub
sam build --use-container --build-image amazon/aws-sam-cli-build-image-nodejs12.x

# Build a function resource using the Python 3.8 container image pulled from DockerHub
sam build --use-container --build-image Function1=amazon/aws-sam-cli-build-image-python3.8 
```


## Social Proof
I'm not going to post my progression on social media.