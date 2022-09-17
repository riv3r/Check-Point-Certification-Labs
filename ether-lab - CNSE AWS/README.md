# [ether-labs] Check Point Cloud Network Security Expert for AWS (CNSE-AWS)

**Status**\
<span style="color:red">UNDER DEVELOPMENT<span>

**Last Updated**\
Friday 16th September 2022

**Target GAIA Version**\
R81.10

<br />

## DISCLAIMER - READ THIS IF YOU WANT LABS TO WORK

By using any of the Terraform code in this repo you acknowledge that ether-net is not responsible for...:
1. The accuracy of cost estimates
2. Costs incurred by running these labs, including any unplanned costs
3. Damages incurred if you build your infrastructure within a production cloud environment

To prove that you have fully read, comprehended, and acknowledged this section you **must** change the `disclaimer_accepted` variable in tfvars.tf to `TRUE` for the Terraform build process to work.

<br />

## Overview
This repository provides learning labs for the Check Point Cloud Network Security Expert for AWS (CNSE-AWS) certification.

You can find the official training brief [here](https://www.checkpoint.com/downloads/training/CNSE-AWS-R81-Course-Overview_Flyer.pdf).

ether-net produced lab manuals are 100% free to use. Always. You can fork and modify all exercises to your heart's content.

Detailed answer guides are coming soon as an optional paid resource through Leanpub while this repo is maintained.

<br />

## Pre-Requisites
The following are required or recommended:
1. Check Point Certified Cloud Specialist (CCCS)
2. Copy of Toni Pasanen's [AWS Networking Fundamentals](https://leanpub.com/aws-networking-fundamentals) if you are unfamiliar with AWS networking concepts and services.
3. Lab 31 requires Aviatrix Certified Engineer (ACE) and Aviatrix Certified Infrastructure as Code (IAC) certification, or equivalent knowledge/experience. Refer to [Aviatrix Training & Courses for Cloud Practitioners](https://aviatrix.com/ace-multicloud-networking-training/) for additional information.
4. A device with Terraform installed and configured with AWS

<br />

## CNSE-AWS Exam Domains
Please note that Check Point do not release weightings for each domain.
* Domain 1: x
* Domain 2: x
* Domain 3: x
* Domain 4: x
* Domain 5: x

<br />

## CNSE-AWS Learning Objectives
* Discuss AWS Platform Components and their relationship to Check Point CloudGuard Network Security.
* Explain how to maintain a secure, efficient, and stable cloud environment.
* Describe the components and constraints of a hub and spoke security environment.
* Describe the function of the Cloud Management Extension.
* Explain the purpose of identity and access controls and constraints in different cloud platforms.
* Explain the steps required to configure Identity and Access controls in AWS.
* Describe the purpose and function of the CloudGuard Controller, its processes, and how it is tied to the Identity Awareness feature.
* Explain how to design and configure Cloud Adaptive Policies.
* Discuss the purpose and function of Data Center Objects.
* Describe the function and advantages of Cloud Service Provider (CSP) automation templates for instance and resource deployments.
* Explain how CSP templates can be used for maintenance tasks in the cloud environment.
* Discuss Third-Party Automation tools, how they can simplify deployment and maintenance tasks, and the constraints associated with them.
* Discuss Scaling Solutions and Options for Cloud Environments.
* Explain the Scaling Options in AWS.
* Describe the workflow for configuring scaling solutions in AWS.
* Discuss how ClusterXL operates and what elements work together to permit traffic failover.
* Explain how ClusterXL functions differently in a Cloud Environment.
* Describe how clusters are created and function in AWS.
* Discuss the elements involved in Hybrid Data Center deployments, the advantages of them, and the constraints involved.
* Explain the nature of a “Greenfield” deployment, the advantages of it, and the constraints involved.
* Describe the components and constraint involved in deploying a Disaster Recovery Site in the cloud.
* Discuss the steps required for troubleshooting automation in AWS.
* Explain the steps required for troubleshooting Scaling Solution issues in AWS.
* Describe the steps required for troubleshooting clusters in AWS

<br />

## Lab Cost Estimate

TBA

<br />

## CNSE-AWS Labs
There are TWO (2) types of labs:
1. Certification Aligned = These are aligned with certification objectives
2. Industry Skill = Labs focused on common real-world tasks a CNSE-AWS may perform - these are not necessarily required to prepare for the certification exam.

| Lab ID  | Type | Description |
|---------|------|-------------|
| CNSE-AWS-01 | Certification Aligned | Create a SSH Key Pair |
| CNSE-AWS-02 | Certification Aligned | Create a VPC |
| CNSE-AWS-03 | Certification Aligned | Deploy an SMS |
| CNSE-AWS-04 | Certification Aligned | Connect to SmartConsole |
| CNSE-AWS-05 | Certification Aligned | Review the IAM Role |
| CNSE-AWS-06 | Certification Aligned | Configure the Cloud Management Extension |
| CNSE-AWS-07 | Certification Aligned | Configure the Access Control Policy |
| CNSE-AWS-08 | Certification Aligned | Create Access Control Policy with a Data Center Object |
| CNSE-AWS-09 | Certification Aligned | Create AWS VPC Spokes |
| CNSE-AWS-10 | Certification Aligned | Deploy Web Servers into the Spoke VPCs |
| CNSE-AWS-11 | Certification Aligned | Create AWS Auto Scale Deployment |
| CNSE-AWS-12 | Certification Aligned | Create the VPC for the Auto Scale Deployment |
| CNSE-AWS-13 | Certification Aligned | Create the VPC Peers |
| CNSE-AWS-14 | Certification Aligned | Deploy the CloudGuard Cluster Template |
| CNSE-AWS-15 | Certification Aligned | Create the AWS VPN Gateway |
| CNSE-AWS-16 | Certification Aligned | Configure the Tunnel Interfaces |
| CNSE-AWS-17 | Certification Aligned | Configure the Static Routes |
| CNSE-AWS-18 | Certification Aligned | Configure the Network Objects |
| CNSE-AWS-19 | Certification Aligned | Configure the VPN Community |
| CNSE-AWS-20 | Certification Aligned | Configure the Security Policy |
| CNSE-AWS-21 | Certification Aligned | Test Cloud Network Traffic |
| CNSE-AWS-22 | Certification Aligned | Troubleshoot the CloudGuard Controller |
| CNSE-AWS-23 | Certification Aligned | Debug the CloudGuard Controller |
| CNSE-AWS-24 | Certification Aligned | Debug the Cloud Management Extension |
| CNSE-AWS-25 | Industry Skill | Exploring DNS within AWS |
| CNSE-AWS-26 | Industry Skill | AWS Transit Gateway Considerations |
| CNSE-AWS-27 | Industry Skill | Exploring AWS ELB & CloudGuard |
| CNSE-AWS-28 | Industry Skill | Deploying & Managing CloudGuard in AWS with Terraform IAC |
| CNSE-AWS-29 | Industry Skill | Integrating AWS Directory Services into Identity Management | 
| CNSE-AWS-30 | Industry Skill | Engaging Check Point Support for PAYG CloudGuard Infrastructure |
| CNSE-AWS-31 | Industry Skill | Exploring Aviatrix Firenet and CloudGuard Deployments in AWS |
| CNSE-AWS-32 | Industry Skill | Understanding AWS CloudGuard Deployment Costs |

<br />

## Lab Topology - Check Point

Image Coming Soon!

<br />

## Lab Topology - AWS Architecture 

Image Coming Soon!