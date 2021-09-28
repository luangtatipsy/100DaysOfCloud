# Deployment Configuration

## Cloud Research
Today, I've learned about a new object type of Kubernetes which is `Deployment`. It allows us create a container with multiple Pods, it is also more flexible than Pod alone.

## __Steps__
1. Run the following command to start a minikube cluster
```sh
minikube start
```
2. Ensure that you are on the right cluster configuration
```sh
kubectl config current-context
```
After the above command has run, `minikube` should be displayed on your terminal.

3. Deploy the app by run the following commands
```sh
cd simple-k8s
kubectl apply -f client-deployment.yaml
kubectl apply -f client-node-port.yaml
```

4. Expose a service to be able to access by URL
```sh
minikube service --url client-node-port
```

5. Visit the URL that is displayed from the previous command.
## Social Proof
I'm not going to post my progression on social media.