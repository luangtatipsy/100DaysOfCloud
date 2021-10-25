# Building Applications
## Cloud Research
Today, I've learned about how to build serverless application. To build your serverless application, use the sam build command. This command also gathers the build artifacts of your application's dependencies and places them in the proper format and location for next steps, such as locally testing, packaging, and deploying. You specify your application's dependencies in a manifest file, such as requirements.txt (Python) or package.json (Node.js), or by using the Layers property of a function resource. The Layers property contains a list of AWS Lambda layer resources that the Lambda function depends on.

The format of your application's build artifacts depends on each function's PackageType property. The options for this property are:
  - __Zip__ – A .zip file archive, which contains your application code and its dependencies. If you package your code as a .zip file archive, you must specify a Lambda runtime for your function.

  - __Image__ – A container image, which includes the base operating system, runtime, and extensions, in addition to your application code and its dependencies.

## Social Proof
I'm not going to post my progression on social media.
