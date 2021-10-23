# Validating AWS SAM template files

## Cloud Research
Today, I've learned about how to validate AWS SAM template files. Validate your templates with `sam validate`. Currently, this command validates that the template provided is valid JSON / YAML. As with most AWS SAM CLI commands, it looks for a template. YAML/YML file in your current working directory by default. You can specify a different template file/location with the `-t` or `--template` option. However, the sam validate command requires AWS credentials to be configured.

```sh
sam validate
```
The output should be like example below.
```
<path-to-file>/template.yml is a valid SAM Template
```


## Social Proof
I'm not going to post my progression on social media.
