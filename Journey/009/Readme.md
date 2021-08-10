# Optimization

## Cloud Research
- Today, I've learned about how we can optimize the system to handle different load dynamically. Load balancer helps us for routing incomming traffics and distribute them to EC2 instances. By the way, there is another stuff to improve, EC2 auto scaler, it can scale up EC2 instances to keep a steady performance when there are so many incomming traffics. On the other hand, it scale down EC2 instances for less traffics as well.

## __What’s a Load Balancer?__
Load balancing refers to the process of distributing tasks across a set of resources. In the case of the corporate directory application, the resources are EC2 instances that host the application, and the tasks are the different requests being sent. It’s time to distribute the requests across all the servers hosting the application using a load balancer.

### __Select Between ELB Types__
<img src="elb-use-cases.png" width="1024px" />

## __Use Amazon EC2 Auto Scaling__
The EC2 Auto Scaling service works to add or remove capacity to keep a steady and predictable performance at the lowest possible cost. By adjusting the capacity to exactly what your application uses, you only pay for what your application needs. And even with applications that have steady usage, EC2 Auto Scaling can help with fleet management. If there is an issue with an EC2 instance, EC2 Auto Scaling can automatically replace that instance. This means that EC2 Auto Scaling helps both to scale your infrastructure and ensure high availability. 

### __Configure EC2 Auto Scaling Components__
There are three main components to EC2 Auto Scaling.
- __Launch template or configuration__: What resource should be automatically scaled?
- __EC2 Auto Scaling Group__: Where should the resources be deployed?
- __Scaling policies__: When should the resources be added or removed?

## Social Proof
I'm not going to post my progression on social media.
