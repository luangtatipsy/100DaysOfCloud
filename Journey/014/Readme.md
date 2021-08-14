# Protecting Application

## Cloud Research
- Today, I've learned about ways to protect systems and services on application layer such as EC2, and API endpoints including protecting secrets needed to access your applications, services, and IT resources.

## __Securing Amazon EC2 Instances__
The process for securing EC2 instances involves principles that are applicable to any OS, whether running in a virtual machine or on premises:
- __Least Access__: Restrict server access from both the network and on the instance, install only the required OS components and applications, and leverage host-based protection software.
- __Least Privilege__: Define the minimum set of privileges each server needs in order to perform its function.
- __Configuration Management__: Create a baseline server configuration and track each server as a configuration item. Assess each server against the current recorded baseline to identify and flag any deviations. Ensure each server is configured to generate and securely store appropriate log and audit data.
- __Change Management__: Create processes to control changes to server configuration baselines.
- __Audit Logs__: Audit access and all changes to EC2 instances to verify server integrity to ensure only authorized changes are made.

## __Securing Endpoints__
### __Amazon API Gateway__
Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. With a few clicks in the AWS Management Console, you can create REST and WebSocket APIs that act as a “front door” for applications to access data, business logic, or functionality from your backend services, such as workloads running on Amazon Elastic Compute Cloud (Amazon EC2), code running on AWS Lambda, any web application, or real-time communication applications.

### __AWS Shield__
AWS Shield is a managed Distributed Denial of Service (DDoS) protection service that safeguards applications running on AWS. AWS Shield provides always-on detection and automatic inline mitigations that minimize application downtime and latency, so there is no need to engage AWS Support to benefit from DDoS protection. There are two tiers of AWS Shield - Standard and Advanced.

### __AWS WAF__
AWS WAF is a web application firewall that helps protect your web applications from common web exploits that could affect application availability, compromise security, or consume excessive resources. AWS WAF gives you control over which traffic to allow or block to your web applications by defining customizable web security rules. You can use AWS WAF to create custom rules that block common attack patterns, such as SQL injection or cross-site scripting, and rules that are designed for your specific application. New rules can be deployed within minutes, letting you respond quickly to changing traffic patterns. Also, AWS WAF includes a full-featured API that you can use to automate the creation, deployment, and maintenance of web security rules.

## __Secrets Manager__
AWS Secrets Manager helps you protect secrets needed to access your applications, services, and IT resources. The service enables you to easily rotate, manage, and retrieve database credentials, API keys, and other secrets throughout their lifecycle. Users and applications retrieve secrets with a call to Secrets Manager APIs, eliminating the need to hardcode sensitive information in plain text. Secrets Manager offers secret rotation with built-in integration for Amazon RDS, Amazon Redshift, and Amazon DocumentDB. Also, the service is extensible to other types of secrets, including API keys and OAuth tokens. In addition, Secrets Manager enables you to control access to secrets using fine-grained permissions and audit secret rotation centrally for resources in the AWS Cloud, third-party services, and on-premises.


## Social Proof
I'm not going to post my progression on social media.
