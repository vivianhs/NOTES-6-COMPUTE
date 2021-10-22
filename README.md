# NOTES-6-COMPUTE
CIT 114 NOTES


### 8.01 Operating systems
Is the most important software that runs on a computer. 
Manages the computer’s memory and processes the software and hardware. Allos to communicate with computers without knowing how to speak the computer’s language. 
The operating system access the CPU, the memory and the storage to make sure each program gets what it needs

#### Types of operating systems
The most common type of operating system are Microsoft Windows, macOS, and Linux. 
Modern operating systems use a graphical user interface or GIU which lets you use the mouse, click on icons, buttons, and menus and displays everything with graphics and text. 

##### Microsoft Windows
Was created in the mid 1980s. There have been many different versions, with Windows 10 (2015) being the most recent. Is the most popular operating system in the world.

On Amazon AWS, Windows Servers are used to serve information while desktop versions of Windows can be used as remote desktops.

##### Linux
Is a family of open-source operating systems, which means they can be modified and distributed by anyone around the world. It is free, and there are different distributions or versions to choose from. Less than 2% users operate with Linux


### 8.02 Available Operating Systems at AWS

Amazon has a variety of operating systems that can be used in EC2 based virtual machines and other compute resources.

Linux, macOS, Raspberry Pi OS, Windows Server

Amazon Linux 2
Is the next generation of Amazon Linux. Provides a secure, stable and high performance execution environment to develop and run cloud and enterprise applications.
 CentOs, Red Hat, Debian

Windows on AWS 
Not regular Windows


### 8.03 AWS Compute Services

Pending https://riohondo.instructure.com/courses/16491/pages/8-dot-03-aws-compute-services?module_item_id=879919

In AWS there are four broad categories of compute services:
Virtual machines
Containers
Serverless
Platform as a Service


### 8.04 Choosing the Right Service

#### Selecting Compute Resources  

https://riohondo.instructure.com/courses/16491/pages/8-dot-04-choosing-the-right-service?module_item_id=879920

In AWS, compute is available in three forms: instances, containers, and functions:
Instances
Containers
Functions


#### Best Practices for Selecting Compute Resources
Evaluate the available compute options
Understand the available compute configuration options
Collect compute-related metrics
Determine the required configuration by right-sizing
Use the available elasticity of resources
Re-evaluate compute needs based on metrics



### 8.05 What are Virtual Machines?
VMs are computers that run inside of other commuting using a process known as virtualization. Often used for testing, backing up data, or running SaaS applications.

#### What is a Virtual Machine?
Operating systems: Manages the computer’s hardware and other softwares in ways that are useful to the user. Typically, operating systems exist within a physical computer at a one-to-one ratio; for each machine there is a single OS managing its physical resources.
There are two or more OS in a computer, 

#### What is a Hypervisor? 
Is the software, firmware, or hardware that  VM’s run on.

What are virtual machines used for?
How does cloud computing use virtual machines?



### 8.06 Introduction to EC2
Amazon Elastic Compute Cloud (Amazon EC2) 
Provides virtual machines where you can host the same kinds of applications that might run on traditional on-premises servers. It provides secure, resizable compute capacity in the cloud. ECS instances can support a variety of workloads.

#### What is Amazon's Elastic Compute Cloud?
Amazon Elastic Compute Cloud (EC2) forms a central part of Amazon.com's cloud-computing platform, Amazon Web Services (AWS), by allowing users to rent virtual computers on which to run their own computer applications. EC2 encourages scalable deployment of applications by providing a web service through which a user can boot an Amazon Machine Image (AMI) to configure a virtual machine, which Amazon calls an instance, containing any software desired. A user can create, launch, and terminate server-instances as needed, paying by the second for active servers – hence the term elastic. EC2 provides users with control over the geographical location of instances that allows for latency optimization and high levels of redundancy.

#### Features & Terminology of Amazon EC2
Virtual computing environments, known as instances
Preconfigured templates for your instances, known as Amazon Machine Images (AMIs), 
Various configurations of CPU, memory, storage, and networking capacity for your instances, known as instance types
Secure login information for your instances using key pairs
Storage volumes for temporary data that's deleted when you stop or terminate your instance, known as instance store volumes
Persistent storage volumes for your data using Amazon Elastic Block Store (Amazon EBS), known as Amazon EBS volumes
Multiple physical locations for your resources, such as instances and Amazon EBS volumes, known as Regions and Availability Zones
A firewall that enables you to specify the protocols, ports, and source IP ranges that can reach your instances using security groups
Static IPv4 addresses for dynamic cloud computing, known as Elastic IP addresses
Metadata, known as tags, that you can create and assign to your Amazon EC2 resources
Virtual networks you can create that are logically isolated from the rest of the AWS cloud, and that you can optionally connect to your own network, known as virtual private clouds (VPCs)

#### Key Benefits of EC2
Elastic Web-Scale Computing
Completely Controlled
Flexible Cloud Hosting Services
Integrated
Reliable
Secure
Inexpensive
Easy to Start

VIDEO
Add graphic, about metrics for easy instances
CPU memory and storage on EC2


### 8.07 Instance Types

General Purpose
Compute Optimized
Memory Optimized
Accelerated Computing
Storage Optimized


### 8.08 Amazon Machine Images (AMI)


### 8.09 EC2 Pricing

On-Demand 


Spot Instance


Dedicated Host. 
A physical EC2 server dedicated for your use. Help to reduce cost bny allowing to use of your existing server-bound software licenses, including Windows Server, SQL Server and SUSE Linux Enterprise Server.
Can be purchased on demand (hourly) 
Can be purchased as a Reservation for up to 70% of the On-Demand price.
Are recommended for :
Bring your own license
Applications with specific corporate compliance and regulatory restrictions
Applications that require usage of licensing tracking
Greater control over the instance placement
Reserve Instance
Dedicated Instance
Scheduled Reserved Instances
Savings Plans
Free Tier


Per Second Billing
Pay only for what you use. ECS are billed on one second increments, with a minimum of 60 seconds. Is available for instances launched in:

On-Demand, Reserved and Spot forms
All regions and Availability Zones
Amazon Linux and Ubuntu


### 8.10 Four Pillars of Cost Optimization

Pillar 1. Right Size

Pillar 2. Increase Elasticity

Pillar 3: Leverage the right pricing model

Pillar 4: Optimize storage
