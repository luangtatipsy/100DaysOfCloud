# AWS Compute

## Cloud Research
- Today, I've learned about AWS compute services consisting EC2, container services, and serverless. They are designed for different purposes and scenarios.

## __Introduction to Amazon Elastic Compute Cloud__
### __What Is Amazon EC2?__
Amazon EC2 is a web service that provides secure, resizable compute capacity in the cloud. It allows you to provision virtual servers called EC2 instances. Although AWS uses the phrase “web service” to describe it, it doesn’t mean that you are limited to running just web servers on your EC2 instances.

### __Explore the EC2 Instance Lifecycle__
<img src="aws-ec2-instance-lifecycle.png" width="1024px" />
When you launch an instance, it enters the pending state (1). When the instance is pending, billing has not started. At this stage, the instance is preparing to enter the running state. Pending is where AWS performs all actions needed to set up an instance, such as copying the AMI content to the root device and allocating the necessary networking components.

When your instance is running (2), it's ready to use. This is also the stage where billing begins. As soon as an instance is running, you are then able to take other actions on the instance, such as reboot, terminate, stop, and stop-hibernate.

When you reboot an instance (3), it’s different than performing a stop action and then a start action. Rebooting an instance is equivalent to rebooting an operating system. The instance remains on the same host computer and maintains its public and private IP address, and any data on its instance store.

It typically takes a few minutes for the reboot to complete. When you stop and start an instance (4), your instance may be placed on a new underlying physical server. Therefore, you lose any data on the instance store that were on the previous host computer. When you stop an instance, the instance gets a new public IP address but maintains the same private IP address.

When you terminate an instance (5), the instance store are erased, and you lose both the public IP address and private IP address of the machine. Termination of an instance means you can no longer access the machine.

## __Container Services on AWS__
### __Manage Containers with Amazon Elastic Container Service (Amazon ECS)__
Amazon ECS is an end-to-end container orchestration service that allows you to quickly spin up new containers and manage them across a cluster of EC2 instances.

### __Use Kubernetes with Amazon Elastic Kubernetes Service (Amazon EKS)__
Kubernetes is a portable, extensible, open source platform for managing containerized workloads and services. By bringing software development and operations together by design, Kubernetes created a rapidly growing ecosystem that is very popular and well established in the market. 

## Serverless
Every definition of serverless mentions four aspects. No servers to provision or manage. Scales with usage.
- You never pay for idle resources.
- Availability and fault tolerance are built-in.
- With serverless, spend time on the things that differentiate your application, rather than spending time on ensuring availability, scaling, and managing servers.
- AWS has several serverless compute options, including AWS Fargate and AWS Lambda.


## Social Proof
I'm not going to post my progression on social media.
