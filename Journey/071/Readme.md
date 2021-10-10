# Passing Secrets as Environment Variables
## Cloud Research
Today, I've learned about how to passing secrets that we created previously as environment variables.

```yaml
  ...
  env:
    - name: ENV_NAME
      valueFrom:
        secretKeyRef:
          name: SECRET_NAME
          key: KEY_OF_SECRET
  ...
```

## Social Proof
I'm not going to post my progression on social media.