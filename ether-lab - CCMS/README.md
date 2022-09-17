# [ether-labs] Check Point Certified Multi-Domain Security Management Specialist (CCAS)

**Status**\
<span style="color:red">UNDER DEVELOPMENT<span>

**Last Updated**\
Friday 16th September 2022

**Target GAIA Version**\
R80.20

<br />

## DISCLAIMER - READ THIS IF YOU WANT LABS TO WORK

By using any of the Terraform code in this repo you acknowledge that ether-net is not responsible for...:
1. The accuracy of cost estimates
2. Costs incurred by running these labs, including any unplanned costs
3. Damages incurred if you build your infrastructure within a production cloud environment

To prove that you have fully read, comprehended, and acknowledged this section you **must** change the `disclaimer_accepted` variable in tfvars.tf to `TRUE` for the Terraform build process to work.

<br />

## Overview
This repository provides learning labs for the Check Point Multi-Domain Security Management (CCMS) certification.

You can find the official training brief [here](https://www.checkpoint.com/downloads/training/CCMS-R80-x-course-overview.pdf).

ether-net produced lab manuals are 100% free to use. Always. You can fork and modify all exercises to your heart's content.

Detailed answer guides are coming soon as an optional paid resource through Leanpub while this repo is maintained.

<br />

## Pre-Requisites
The following are required or recommended:
1. Check Point Certified Security Expert (CCSE) knowledge / equivalent experience
2. Understanding of Check Point GAIA OS components, such as core daemons and databases that Security Management Servers and Security Gateways leverage
3. A device with Terraform installed and configured with AWS

<br />

## CCMS Exam Domains
Please note that Check Point do not release weightings for each domain.
* Domain 1: Multi-Domain Security Management
* Domain 2: MDSM Implementation and Configuration
* Domain 3: MDSM Log Management
* Domain 4: Global Policy Management
* Domain 5: MDSM Troubleshooting
* Domain 6: Incorporating VSX (limited lab)

<br />

## CCMS Learning Objectives
* Discuss challenges associated with securing large-scale business organizations with distributed network environments
* Describe the Check Point Multi-Domain Security Management solution and its benefits
* Understand the components of MDSM and how they work together to help administrators manage multiple network security environments within a single management framework
* Understand how to install and configure the Multi-Domain Security Management environment
* Describe how to implement Management High Availability within the MDSM environment
* Discuss the two types of log server options used to store logs in the Multi-Domain Security Management environment, and how they differ
* Understand how to manage and view Multi-Domain activity logs in SmartConsole.
* Understand how to configure and implement Global Policy to manage rules for multiple domains.
* Identify various MDSM command line tools commonly used to retrieve information and perform configuration changes on a MDSM Server.
* Describe troubleshooting tools to use for addressing MDSM Server issues.
* Understand how VSX works and how to integrate the technology within the MDSM environment.

<br />

## Lab Cost Estimate

TBA

<br />

## CCMS Labs
There are TWO (2) types of labs:
1. Certification Aligned = These are aligned with certification objectives
2. Industry Skill = Labs focused on common real-world tasks a CCMS may perform - these are not necessarily required to prepare for the certification exam.

| Lab ID  | Type | Description |
|---------|------|-------------|
| CCMS-01 | Certification Aligned | Demonstrating Multi-Domain Securty Management |
| CCMS-02 | Certification Aligned | Migrating a Security Management Server into a Domain Management Server |
| CCMS-03 | Certification Aligned | Implementing Management High Availability |
| CCMS-04 | Certification Aligned | Deploying a Multi-Domain Log Server |
| CCMS-05 | Certification Aligned | Regionalizing the Multi-Domain Environment |
| CCMS-06 | Certification Aligned | Deploying a Global Policy |
| CCMS-07 | Certification Aligned | Integrating SmartEvent into Multi-Domain Environment |
| CCMS-08 | Certification Aligned | Deploying VSX in a Multi-Domain Environment |
| CCMS-09 | Industry Skill | MDSM and VPNs |
| CCMS-10 | Industry Skill | Case Study 1: MDMS within an Enterprise Organization |
| CCMS-11 | Industry Skill | Case Study 2: MDMS as a Service Provider |
| CCMS-12 | Industry Skill | Case Study 3: MDMS Cloud Considerations |
| CCMS-13 | Industry Skill | Sizing and Licensing MDMS Deployments |

<br />

## Lab Topology - Check Point

Image Coming Soon!

<br />

## Lab Topology - AWS Architecture 

Image Coming Soon!