# Service Type: Cluster IP

## Cloud Research
Today, I've learned about one of Kubernetes service types which is Cluster IP. It allows you only access this service while inside the cluster. It is accessible from its `spec.clusterIp port`. If a `spec.ports[*].targetPort` is set it will route from the port to the targetPort. The `CLUSTER-IP` you get when calling kubectl get services is the IP assigned to this service within the cluster internally.

## Social Proof
I'm not going to post my progression on social media.