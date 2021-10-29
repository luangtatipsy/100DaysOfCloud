# Invoking functions locally

## Cloud Research
Today, I've learned about how to invoke AWS SAM application locally. You can invoke your function locally by using the `sam local invoke` command and providing its function logical ID and an event file. Alternatively, sam local invoke also accepts stdin as an event. For more information about events, see [Event](https://docs.aws.amazon.com/lambda/latest/dg/gettingstarted-concepts.html#gettingstarted-concepts-event) in the AWS Lambda Developer Guide. You must execute sam local invoke in the project directory containing the function you want to invoke.

There are several ways to invoke function, the first one is invoking function with event file.
```sh
sam local invoke "Ratings" -e event.json
```

the second one is invoking function with event via stdin
```sh
echo '{"message": "Hey, are you there?" }' | sam local invoke --event - "Ratings"
```

## Social Proof
I'm not going to post my progression on social media.