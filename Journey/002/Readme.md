# Security in the AWS Cloud

## Cloud Research
- Today, I've learned about how AWS security works. AWS uses a model called "AWS Shared Responsibility Model" to protect incomming attacks. Furthermore, following IAM best practices is a must. It helps protecting us from nefarious actors.

## __Security and the AWS Shared Responsibility Model__
<img src="aws-shared-responsibility-model.jpg" width="1024px" />


### __What Is AWS Responsible For?__
AWS is responsible for security of the cloud. This means AWS is required to protect and secure the infrastructure that runs all the services offered in the AWS Cloud. AWS is responsible for:
  - Protecting and securing AWS Regions, Availability Zones, and data centers, down to the physical security of the buildings
  - Managing the hardware, software, and networking components that run AWS services, such as the physical server, host operating systems, virtualization layers, and AWS networking components

### __What Is the Customer Responsible For?__
You’re responsible for security in the cloud. When using any AWS service, you’re responsible for properly configuring the service and your applications, as well as ensuring your data is secure.

## __Protect the AWS Root User__

### __Understand Authentication__
When you create your AWS account, you use a combination of an email address and a password to verify your identity. If the user types in the correct email and password, the system assumes the user is allowed to enter and grants them access. This is the process of authentication.

Authentication ensures that the user is who they say they are. Usernames and passwords are the most common types of authentication, but you may also work with other forms, such as token-based authentication or biometric data like a fingerprint. Authentication simply answers the question, “Are you who you say you are?”

### __Understand Authorization__
Once you’re inside your AWS account, you might be curious about what actions you can take. This is where authorization comes in. Authorization is the process of giving users permission to access AWS resources and services. Authorization determines whether the user can perform an action—whether it be to read, edit, delete, or create resources. Authorization answers the question, “What actions can you perform?”

### __Use MFA on AWS__
If you enable MFA on your root user, you are required to present a piece of identifying information from both the something you know category and the something you have category. The first piece of identifying information the user enters is an email and password combination. The second piece of information is a temporary numeric code provided by an MFA device.

Enabling MFA adds an additional layer of security because it requires users to use a supported MFA mechanism in addition to their regular sign-in credentials. It’s best practice to enable MFA on the root user.

## Social Proof
I'm not going to post my progression on social media.
