# [ether-labs] Check Point Certified Security Expert (CCSE)

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
This repository provides learning labs for the Check Point Certified Security Expert (CCSE) certification.

You can find the official training brief [here](https://www.checkpoint.com/downloads/training/CCSE_Overview_Flyer.pdf). I STRONGLY recommended purchasing an official practice exam for the CCSE R81 through Pearson Vue due to the sheer volume of content on the blueprint.

ether-net produced lab manuals are 100% free to use. Always. You can fork and modify all exercises to your heart's content.

Detailed answer guides are coming soon as an optional paid resource through Leanpub while this repo is maintained.

<br />

## Pre-Requisites
The following are mandatory - you can't book the exam without this!
1. Check Point Certified Security Administrator (CCSA) or equivalent knowledge/experience

<br />

## CCSE Exam Domains
Please note that Check Point do not release weightings for each domain.
* Domain 1: Management Upgrade and Migration
* Domain 2: Management High Availability
* Domain 3: Security Gateway Upgrade
* Domain 4: Advanced Check Point Maintenance
* Domain 5: Security Gateway Operations
* Domain 6: Policy Installation
* Domain 7: GAIA and Management APIs
* Domain 8: Acceleration
* Domain 9: Site-to-Site VPN
* Domain 10: Remote Access VPN
* Domain 11: Mobile Access VPN
* Domain 12: Clustering
* Domain 13: Advanced Logs and Monitoring

<br />

## CCSE Learning Objectives
* Provide an overview of the upgrade service and options available.
* Explain how to perform management upgrade and migration.
* Articulate the process using CPUSE features.
* Articulate the purpose and function of Management High Availability.
* Explain Primary vs Secondary, Active vs Standby and Synchronization.
* Explain disaster recovery steps in case the primary management server becomes unavailable.
* Provide overview of Central Deployment in SmartConsole.
* Articulate an understanding of Security Gateway cluster upgrade methods.
* Explain about Multi Version Cluster (MVC) upgrades.
* Discuss Gaia Commands and how they are used.
* Explain the main processes on s and s.
* Describe how to work with scripts and SmartTasks to configure automatic actions.
* Explain the Management Data Plane Separation (MDPS)
* Explain kernel operations and traffic flow
* Articulate Dynamic and Updatable Objects in Security Gateways
* Explain the policy installation flow and files used.
* Describe the use of policy installation history.
* Explain concurrent and accelerated install policy.
* Describe an overview of APIs and ways to use and authenticate.
* Explain how to make changes in GAIA and management configuration.
* Explain how to install policy using API.
* Explain how the SecureXL acceleration technology enhances and optimizes Security Gateway performance.
* Describe how the CoreXL acceleration technology enhances and improves Security Gateway performance.
* Articulate how utilizing multiple traffic queues can make traffic handling more efficient.
* Discuss Site-to-Site VPN basics, deployment and communities.
* Describe how to analyze and interpret VPN tunnel traffic.
* Explain Link Selection and ISP Redundancy options.
* Explain tunnel management features.
* Discuss Check Point Remote Access solutions and how they differ from each other.
* Describe how client security can be provided by Remote Access .
* Explain authentication methods including machine authentication.
* Explain Multiple Entry Point (MEP).
* Discuss the Mobile Access Software Blade and how it secures communication and data exchange during remote connections.
* Describe Mobile Access deployment options.
* Discuss various features in Mobile Access like Portals, Link Translation, running Native Applications, Reverse Proxy and more.
* Explain basic concepts of Clustering and ClusterXL.
* Explain about Cluster Control Protocol (CCP) and synchronization.
* Describe advanced ClusterXL functions and modes like Load Sharing, Active-Active, VMAC mode etc.
* Discuss Cluster Correction Layer (CCL) to provide connection stickyness.
* Advanced Logs and Monitoring

<br />

## Lab Cost Estimate

TBA

<br />

## CCSE Labs
There is ONE (1) type of lab for the CCSE:
1. Certification Aligned = These are aligned with certification objectives

*Industry Skilled labs for the CCSA/CCSE are covered in a non-certification lab booklet called " Check Point Advanced Networking"*

| Lab ID  | Type | Description |
|---------|------|-------------|
| CCSE-01 | Certification Aligned | Prepare for a Security Management Server Upgrade |
| CCSE-02 | Certification Aligned | Upgrade the Security Management Server |
| CCSE-03 | Certification Aligned | Deploy a Secondary Security Management Server |
| CCSE-04 | Certification Aligned | Configure a Distributed Log Server |
| CCSE-05 | Certification Aligned | Upgrade a Security Gateway from SmartConsole |
| CCSE-06 | Certification Aligned | Work with the Command Line |
| CCSE-07 | Certification Aligned | Use Scripts and SmartTasks |
| CCSE-08 | Certification Aligned | Configure Dynamic Objects |
| CCSE-09 | Certification Aligned | Monitor Traffic |
| CCSE-10 | Certification Aligned | Verify Policy Installation and Status |
| CCSE-11 | Certification Aligned | Work with GAIA and Management APIs |
| CCSE-12 | Certification Aligned | Work with Acceleration Features |
| CCSE-13 | Certification Aligned | Create a Locally Managed Site-to-Site VPN |
| CCSE-14 | Certification Aligned | Configure a Site-to-Site VPN with an Interoperable Device |
| CCSE-15 | Certification Aligned | Configure Remote Access VPN |
| CCSE-16 | Certification Aligned | Configure Mobile Access VPN |
| CCSE-17 | Certification Aligned | Configure a High Availability Cluster |
| CCSE-18 | Certification Aligned | Work with ClusterXL |
| CCSE-19 | Certification Aligned | Configure Policy Compliance |
| CCSE-20 | Certification Aligned | Deploy SmartEvent |

<br />

## Lab Topology - Check Point

Image Coming Soon!

<br />

## Lab Topology - AWS Architecture 

Image Coming Soon!