# Creating an Encoded Secret
## Cloud Research
Today, I've learned about Kubernetes Secerts, which is a service securely stores a piece of information in the cluster, such as a database password.

```sh
kubectl create secert <generic/docker-registry/tls> <secret-name> --from-literal <key=value>
```

`generic/docker-registry/tls`: Types of secret  
`secret-name`: Name of secret for later reference in a pod configuration  
`--from-literal`: We are going to add the secert information into this command, as opposed to from . file  
`key=value`: Key-value pair of the secret information  

In order to list all secrets, you can run the command below.
```sh
kubectl get secrets
```

## Social Proof
I'm not going to post my progression on social media.