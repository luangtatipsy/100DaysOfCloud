# Building a Container Image
## Cloud Research
Today, I've learned about how to build a container image. To build your serverless application as a container image, declare PackageType: Image for your serverless function. You must also declare the Metadata resource attribute with the following entries:
  - `Dockerfile`
      The name of the Dockerfile associated with the Lambda function.
  - `DockerContext`
      The location of the Dockerfile.
  - `DockerTag`
      (Optional) A tag to apply to the built image.
  - `DockerBuildArgs`
      Build arguments for the build.

The following is an example Metadata resource attribute section:
```yaml
    Metadata:
      Dockerfile: Dockerfile
      DockerContext: ./hello_world
      DockerTag: v1
```

## Social Proof
I'm not going to post my progression on social media.