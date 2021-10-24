# Working with layers

## Cloud Research
Today, I've learned about how to include with custom layers to your serverless application.

## __Including layers in your application__
To include layers in your application, use the Layers property of the AWS::Serverless::Function resource type. The following is an example AWS SAM template with a Lambda function that includes a layer

```yaml
ServerlessFunction:
  Type: AWS::Serverless::Function
  Properties:
    CodeUri: .
    Handler: my_handler
    Runtime: Python3.7
    Layers:
        - <LayerVersion ARN>
```

When you invoke your function using one of the sam local commands, the layers package of your function is downloaded and cached on your local host. For information about building custom layers, see a [documentation](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-layers.html).


## Social Proof
I'm not going to post my progression on social media.
