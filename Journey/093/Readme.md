# Generating Sample Event Payloads

## Cloud Research
Today, I've learned about using event for local testing. To make local development and testing of Lambda functions easier, you can generate and customize event payloads for a number of AWS services like API Gateway, AWS CloudFormation, Amazon S3, and so on. For the full list of services that you can generate sample event payloads for, use this command:
```sh
sam local generate-event --help
```

For the list of options you can use for a particular service, use this command:
```sh
sam local generate-event [SERVICE] --help
```
Examples:
```sh
#Generates the event from S3 when a new object is created
sam local generate-event s3 put

# Generates the event from S3 when an object is deleted
sam local generate-event s3 delete
```


## Social Proof
I'm not going to post my progression on social media.