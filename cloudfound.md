### <h2> <ins> <center> Aws Cloud Foundations

##### <ins> Question 1: 

* What are IaaS, PaaS, and SaaS?

![Alt text](image-17.png)

##### <ins> Question 2: 

* What are the advantages of cloud computing?

![
](image-18.png)  <marquee>Here are the advantages !</marquee>


##### <ins> Question 3:    

* What is an AWS region?


 
>AWS Regions are separate geographical areas where Amazon Web Services operates data centres. Each region comprises multiple isolated Availability Zones for redundancy and fault tolerance. They allow users to place resources in different global locations to comply with regulations, reduce latency, and enhance availability based on their specific needs.
 

##### <ins> Question 4:

* What is an availability zone? 
 
>Availability Zones (AZs) are isolated locations within an AWS Region, containing one or more data centres with redundant power, networking, and connectivity. They are designed to be independent from one another, to allow AWS services to continue if one data service fails or loses power, while operating in separate physical locations within a region.

##### <ins> Question 5:

* What are all the AWS Regions?

>AWS has a global infrastructure that spans multiple geographic regions around the world. Each AWS Region is a separate geographic area, often located in a specific country or continent. These Regions are designed to provide low-latency access to AWS services and offer fault tolerance and redundancy. 


##### <ins> Question 6:

*  What are the categories in which the AWS services are grouped?

>AWS services are grouped into several categories, including but not limited to:

- Compute
- Storage
- Databases
- Networking
- Security, Identity and Compliance
- Management and Governance

<center> Cloud Foundations 2



> Q1:

![Alt text](image-21.png)

The shared responsibility model is how the security of the cloud is split between AWS and the customer, which can help relieve the customers operational burden. AWS controls the security OF the cloud such as the the actual hardware, availability zones etc. The customer assumes responsibility of security IN the cloud such as management of the operating system and application software including the configuration of the AWS-provided security group firewall.

> Q2: 

![
](image-22.png)

> Q3:

Explain an AWS Identity and Access Management Policy:
 
AWS Identity and Access Management (IAM) allows control over access to AWS resources through IAM policies written in JSON. These policies define who can access specific resources and the actions they can take. For instance, an IAM policy might allow reading from a certain folder in an S3 bucket, enable actions like uploading and deleting files in another folder, and restrict all actions within a confidential folder unless tagged as "Confidential." These policies, attached to IAM users, groups, or roles, ensure fine-grained access control, following the principle of least privilege for heightened security in the AWS environment.

>Q4: 

Describe an Amazon Machine Image (AMI)
 
An Amazon Machine Image (AMI) in AWS acts as a blueprint for launching virtual servers within EC2, containing an OS, software, and configuration settings. Users can create AMIs from existing instances or customize them, serving as the starting point when launching new instances. These images, available as public or private, simplify instance provisioning and maintain consistency across deployments, crucial for managing computing resources and scaling within AWS.

> Q5:

Amazon EC2 offers a variety of instance types tailored for specific use cases, including general-purpose, compute-intensive, memory-intensive, and GPU-intensive workloads. Some examples include T2, M5, C5, and P3 instances

![
](image-24.png)

> Q6:

![Alt text](image-25.png)

> Q7: 

A public subnet is a subnet that is associated with a route table that has a route to an Internet gateway. This connects the VPC to the Internet and to other AWS services. A private subnet is a subnet that is associated with a route table that doesn't have a route to an internet gateway.

![Alt text](image-27.png)





