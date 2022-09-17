# [ether-labs] Check Point Cloud Network Security Expert for Azure (CNSE-Azure)

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
This repository provides learning labs for the Check Point Cloud Network Security Expert for Azure (CNSE-Azure) certification.

You can find the official training brief [here](https://www.checkpoint.com/downloads/training/CNSE-Azure-R81-Course-Overview_Flyer.pdf).

ether-net produced lab manuals are 100% free to use. Always. You can fork and modify all exercises to your heart's content.

Detailed answer guides are coming soon as an optional paid resource through Leanpub while this repo is maintained.

<br />

## Pre-Requisites
The following are required or recommended:
1. Check Point Certified Cloud Specialist (CCCS)
2. Copy of Toni Pasanen's [Azure Networking Fundamentals](https://leanpub.com/azure_networking_fundamentals) if you are unfamiliar with Azure networking concepts and services.
3. Lab 31 requires Aviatrix Certified Engineer (ACE) and Aviatrix Certified Infrastructure as Code (IAC) certification, or equivalent knowledge/experience. Refer to [Aviatrix Training & Courses for Cloud Practitioners](https://aviatrix.com/ace-multicloud-networking-training/) for additional information.
4. A device with Terraform installed and configured with Azure 

<br />

## CNSE-Azure Exam Domains
Please note that Check Point do not release weightings for each domain.
* Domain 1: x
* Domain 2: x
* Domain 3: x
* Domain 4: x
* Domain 5: x

<br />

## CNSE-Azure Learning Objectives
* Discuss Azure Platform Components and their relationship to Check Point CloudGuard Network Security.
* Explain how to maintain a secure, efficient, and stable cloud environment.
* Describe the components and constraints of a hub and spoke cloud security environment.
* Describe the function of the Cloud Management Extension
* Explain the purpose of identity and access controls and constraints in different cloud platforms.
* Explain the steps required to configure Identity and Access controls in Azure.
* Describe the purpose and function of the CloudGuard Controller, its processes, and how it is tied to the Identity Awareness feature.
* Explain how to design and configure Cloud Adaptive Policies.
* Discuss the purpose and function of Data Center Objects.
* Describe the function and advantages of Cloud Service Provider (CSP) automation templates for instance and resource deployments.
* Explain how CSP templates can be used for maintenance tasks in the cloud environment.
* Discuss Third-Party Automation tools, how they can simplify deployment and maintenance tasks, and the constraints associated with them.
* Discuss Scaling Solutions and Options for Cloud Environments.
* Explain the Scaling Options in Azure.
* Describe the workflow for configuring scaling solutions in Azure.
* Discuss how ClusterXL operates and what elements work together to permit traffic failover.
* Explain how ClusterXL functions differently in a Cloud Environment.
* Describe how clusters are created and function in Azure.
* Discuss the elements involved in Hybrid Data Center deployments, the advantages of them, and the constraints involved.
* Explain the nature of a “Greenfield” deployment, the advantages of it, and the constraints involved.
* Describe the components and constraint involved in deploying a Disaster
* Recovery Site in the cloud.
* Discuss the steps required for troubleshooting automation in Azure.
* Explain the steps required for troubleshooting Scaling Solution issues in Azure.
* Describe the steps required for troubleshooting clusters in Azure

<br />

## Lab Cost Estimate

TBA

<br />

## CNSE-Azure Labs
There are TWO (2) types of labs:
1. Certification Aligned = These are aligned with certification objectives
2. Industry Skill = Labs focused on common real-world tasks a CNSE-Azure may perform - these are not necessarily required to prepare for the certification exam.

| Lab ID  | Type | Description |
|---------|------|-------------|----------------|
| CNSE-AZURE-01 | Certification Aligned | Deploy a Security Management Server |
| CNSE-AZURE-02 | Certification Aligned | Connect to SmartConsole |
| CNSE-AZURE-03 | Certification Aligned | Configure Azure Active Directory and the Service Principal |
| CNSE-AZURE-04 | Certification Aligned | Install the Cloud Management Extension |
| CNSE-AZURE-05 | Certification Aligned | Configure the Cloud Management Extension | - |
| CNSE-AZURE-06 | Certification Aligned | Configure the Access Control Policy | - |
| CNSE-AZURE-07 | Certification Aligned | Assign the Service Principle | - |
| CNSE-AZURE-08 | Certification Aligned | Create the CloudGuard Controller Object | - |
| CNSE-AZURE-09 | Certification Aligned | Configure Access Control Policy with a Data Center Object | - |
| CNSE-AZURE-10 | Certification Aligned | Deploy the Spoke vNets | - |
| CNSE-AZURE-11 | Certification Aligned | Create the Spoke Route Table | - |
| CNSE-AZURE-12 | Certification Aligned | Deploy Web Servers into the Spoke vNets | - |
| CNSE-AZURE-13 | Certification Aligned | Deploy the Virtual Machine Scale Set | - |
| CNSE-AZURE-14 | Certification Aligned | Assign the Service Principle to the VMSS Resource Group | - |
| CNSE-AZURE-15 | Certification Aligned | Enable Identity Awareness on the VMSS | - |
| CNSE-AZURE-16 | Certification Aligned | Create Load Balancer Rules | - |
| CNSE-AZURE-17 | Certification Aligned | Create Web Server Access Control policy | - |
| CNSE-AZURE-18 | Certification Aligned | Deploy the Azure High Availability Solution | - |
| CNSE-AZURE-19 | Certification Aligned | Create the Cluster Object | - |
| CNSE-AZURE-20 | Certification Aligned | Configure the vNet Peering | - |
| CNSE-AZURE-21 | Certification Aligned | Create the Internal User Defined Routes | - |
| CNSE-AZURE-22 | Certification Aligned | Create the Security Policy for Internal Traffic | - |
| CNSE-AZURE-23 | Certification Aligned | Test the Internal Traffic | - |
| CNSE-AZURE-24 | Certification Aligned | Troubleshoot the CloudGuard Controller | - |
| CNSE-AZURE-25 | Certification Aligned | Debug the CloudGuard Controller | - |
| CNSE-AZURE-26 | Certification Aligned | Debug the Cloud Management Extension | - |
| CNSE-AZURE-27 | Industry Skill | Exploring DNS within Azure | - |
| CNSE-AZURE-28 | Industry Skill | Azure Routing Considerations | - |
| CNSE-AZURE-29 | Industry Skill | Exploring Azure Load Balancers & CloudGuard | - |
| CNSE-AZURE-30 | Industry Skill | Deploying & Managing CloudGuard in Azure with Terraform IAC | - |
| CNSE-AZURE-31 | Industry Skill | Integrating Azure Active Directory into Identity Management | - |
| CNSE-AZURE-32 | Industry Skill | Engaging Check Point Support for PAYG CloudGuard Infrastructure | - |
| CNSE-AZURE-33 | Industry Skill | Exploring Aviatrix Firenet and CloudGuard Deployments in Azure | - |
| CNSE-AZURE-34 | Industry Skill | Understanding Azure CloudGuard Deployment Costs | - |

<br />

## Lab Topology - Check Point

Image Coming Soon!

<br />

## Lab Topology - AWS Architecture 

Image Coming Soon!