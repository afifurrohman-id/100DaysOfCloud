
# Amazon Machine Image AWS (Udemy | Stephane Mareek)

## Introduction
An Amazon Machine Image is a special type of virtual appliance that is used to create a virtual machine within the Amazon Elastic Compute Cloud. It serves as the basic unit of deployment for services delivered using EC2. The journey will be like this:
- AMI = Amazon Machine Image Intro
- AMI Process (from an EC2 instance) 
- EC2 Image Builder

## Cloud Research

### AMI = Amazon Machine Image
- AMI are a customization of an EC2 instance
> - You add your own software, configuration, operating system, monitoring…
> - Faster boot / configuration time because all your software is pre-packaged
- AMI are built for a specific region (and can be copied across regions)
- You can launch EC2 instances from:
> - A Public AMI: AWS provided
> - Your own AMI: you make and maintain them yourself
> - An AWS Marketplace AMI: an AMI someone else made (and potentially sells)

### AMI Process (from an EC2 instance) 
Start an EC2 instance and customize it
- Stop the instance (for data integrity)
- Build an AMI – this will also create EBS snapshots
- Launch instances from other AMIs


### EC2 Image Builder
- Used to automate the creation of Virtual Machines or container images
- Automate the creation, maintain, validate and test EC2 AMIs
- Can be run on a schedule (weekly, whenever packages are updated, etc…)
- Free service (only pay for the underlying resources)

## Next Steps

- EC2 Instance Store

## Social Proof

[Personal Web Article](https://afifurrohman-id.github.io/article/100DaysOfCloud)
