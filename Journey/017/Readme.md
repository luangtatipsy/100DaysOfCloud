# VM Import and VM on AWS

## Cloud Research
- Today, I've learned about how to import/export existing virtual machine (VM) to AWS EC2.

## __What is VM Import/Export?__
VM Import/Export enables you to import virtual machine (VM) images from your existing virtualization environment to Amazon EC2, and then export them back. This enables you to migrate applications and workloads to Amazon EC2, copy your VM image catalog to Amazon EC2, or create a repository of VM images for backup and disaster recovery.

## __Features of VM Import/Export__
VM Import provides the following features:
- The ability to import a VM from your virtualization environment to Amazon EC2 as an Amazon Machine Image (AMI). You can launch EC2 instances from your AMI any time.
- The ability to import a VM from your virtualization environment to Amazon EC2 as an EC2 instance. The instance is initially in a stopped state. You can create an AMI from the instance.
- The ability to export a VM that was previously imported from your virtualization environment.
- The ability to import disks as Amazon EBS snapshots.
- VM import supports ENA drivers for Linux. ENA support will be enabled only if the original VM has ENA and/or NVMe drivers installed. We recommend installing the latest drivers.


## Social Proof
I'm not going to post my progression on social media.
