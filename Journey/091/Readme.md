# Running API Gateway Locally

## Cloud Research
Today, I've learned about how to run API Gateway locally. You can use the `sam local start-api` command to start a local instance of API Gateway that you will use to test HTTP request/response functionality. This functionality features hot reloading to enable you to quickly develop and iterate over your functions. You must execute `sam local start-api` in the project directory containing the function you want to invoke.

```sh
sam local start-api
```

AWS SAM automatically finds any functions within your AWS SAM template that have HttpApi or Api event sources defined. Then, it mounts them at the defined HTTP paths.

## Social Proof
I'm not going to post my progression on social media.