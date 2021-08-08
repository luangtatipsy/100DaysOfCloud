# Monitoring on AWS

## Cloud Research
- Today, I've learned about basic monitoring and its purposes. AWS CloudWatch provides us many different pre-set metrics that we can select them for monitoring something like CPU, and memory utilization on EC2 intances. AWS CloudWatch has an alarm feature which can notify us when a value on any metric exceed a threshold as well.

## __Understand the Benefits of Monitoring__
Monitoring gives you visibility into your resources, but the question now is, "Why is that important?" The following are some of the benefits of monitoring.
- __Respond to operational issues proactively before your end users are aware of them__. It’s a bad practice to wait for end users to let you know your application is experiencing an outage. Through monitoring, you can keep tabs on metrics like error response rate or request latency, over time, that help signal that an outage is going to occur. This enables you to automatically or manually perform actions to prevent the outage from happening—fixing the problem before your end users are aware of it.
- __Improve the performance and reliability of your resources__. Monitoring the different resources that comprise your application provides you with a full picture of how your solution behaves as a system. Monitoring, if done well, can illuminate bottlenecks and inefficient architectures. This enables you to drive performance and reliability improvement processes.
- __Recognize security threats and events__. When you monitor resources, events, and systems over time, you create what is called a baseline. A baseline defines what activity is normal. Using a baseline, you can spot anomalies like unusual traffic spikes or unusual IP addresses accessing your resources. When an anomaly occurs, an alert can be sent out or an action can be taken to investigate the event.
- __Make data-driven decisions for your business__. Monitoring is not only to keep an eye on IT operational health. It also helps drive business decisions. For example, let’s say you launched a new feature for your cat photo app, and want to know whether it’s being used. You can collect application-level metrics and view the number of users who use the new feature. With your findings, you decide whether to invest more time into improving the new feature.
- __Create more cost-effective solutions__. Through monitoring, you can view resources that are being underutilized and rightsize your resources to your usage. This helps you optimize cost and make sure you aren’t spending more money than necessary.

## __How CloudWatch Works__
The great thing about CloudWatch is that all you need to get started is an AWS account. It is a managed service, which enables you to focus on monitoring, without managing any underlying infrastructure. For applications running on EC2 instances, you can get more granularity by posting metrics every minute instead of every 5 minutes using a feature like detailed monitoring. Detailed monitoring has an extra fee associated. You can read about pricing on the CloudWatch Pricing Page linked in the resources section of this unit.

## Social Proof
I'm not going to post my progression on social media.
