# [ether-labs] Check Point Certified Cloud Specialist (CCCS)

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
This repository provides learning labs for the Check Point Certified Cloud Specialist (CCAS) certification.

You can find the official training brief [here](https://www.checkpoint.com/downloads/training/CCCS-R81-course-overview.pdf).

The CCCS is a simple and introductory certification. Its primary objective is to demonstrate how Check Point CloudGuard design patterns can protect cloud infrastructure. Its secondary objective is to detail CloudGuard's integration with Check Point's product portfolio. You do not need to be a Cloud Network guru *for this exam*.

ether-net produced lab manuals are 100% free to use. Always. You can fork and modify all exercises to your heart's content.

Detailed answer guides are coming soon as an optional paid resource through Leanpub while this repo is maintained.

<br />

## Pre-Requisites
The following are required or recommended:
1. AWS Cloud Practitioner and Microsoft Azure Fundamentals (AZ-900) certification or equivalent experience
2. An AWS, Azure, and optionally GCP account
3. Lab 16 requires Aviatrix Certified Engineer (ACE) and Aviatrix Certified Infrastructure as Code (IAC) certification, or equivalent knowledge/experience. Refer to [Aviatrix Training & Courses for Cloud Practitioners](https://aviatrix.com/ace-multicloud-networking-training/) for additional information.
<br />

## CCCS Exam Domains
Please note that Check Point do not release weightings for each domain.
* Domain 1: Introduction to Cloud Security 
* Domain 2: Introducing CloudGuard
* Domain 3: CloudGuard Architectures
* Domain 4: CloudGuard Automation
* Domain 5: CloudGuard Security Policy
* Domain 6: CloudGuard Troubleshooting
* Domain 7: Introduction to Cloud Security Posture Management

<br />

## CCCS Learning Objectives
* Explain the nature of cloud architecture
* Describe the five pillars of cloud architecture
* Explain the Basics of Cloud Infrastructure
* Explain the Basics of Cloud Automation
* Explain Check Point Security Management and How it Applies to CloudGuard
* Describe CloudGuard Security Gateway offerings
* Describe Cloud Load Balancers
* Explain CloudGuard Licensing
* Explain the different Deployment options and architectures for CloudGuard
* Explain how and why CloudGuard is automated
* Describe the functions of CloudGuard that can be automated
* Describe the tools used to automate CloudGuard
* Explain CloudGuard Automation Requirements
* Explain basic troubleshooting techniques specific to Check Point Security Management Servers and Security Gateways
* Describe the steps for Troubleshooting CloudGuard Network Installation
* Explain the tools and techniques used to troubleshoot CloudGuard Network Automation
* Explain the need for Cloud Security Posture Management
* Describe the posture management tools available in CloudGuard
* Explain methods for correcting Cloud Security Posture Management Issues

<br />

## Lab Cost Estimate

TBA

<br />

## CCCS Labs
There are TWO (2) types of labs:
1. Certification Aligned = These are aligned with certification objectives
2. Industry Skill = Labs focused on common real-world tasks a CCCS may perform - these are not necessarily required to prepare for the certification exam.

| Lab ID  | Type | Description |
|---------|------|-------------|
| CCCS-01 | Certification Aligned | Deploy a Security Management Server in the Cloud |
| CCCS-02 | Certification Aligned | Install a Security Gateway Image |
| CCCS-03 | Certification Aligned | Create Virtual Networks |
| CCCS-04 | Certification Aligned | Deploy Internal and External Load Balancers |
| CCCS-05 | Certification Aligned | Deploy a Security Gateway Using Templates |
| CCCS-06 | Certification Aligned | Assign Public IP Addresses to Cloud Devices |
| CCCS-07 | Certification Aligned | Create Web Servers in the Cloud |
| CCCS-08 | Certification Aligned | Configure North-South Traffic Policy |
| CCCS-09 | Certification Aligned | Configure East-West Traffic Policy and Routes |
| CCCS-10 | Certification Aligned | Troubleshoot North-South Traffic Issues |
| CCCS-11 | Certification Aligned | Troubleshoot East-West Traffic Issues |
| CCCS-12 | Industry Skill | Exploring CloudGuard in Google Cloud |
| CCCS-13 | Industry Skill | Exploring Security Management Server Cloud Management Extension |
| CCCS-14 | Industry Skill | The Importance of Good Tagging  |
| CCCS-15 | Industry Skill | Exploring the Check Point Terraform Provider |
| CCCS-16 | Industry Skill | Using Aviatrix Firenet to deploy Check Point for Multi-Cloud Security | - |

<br />

## Lab Topology - Check Point

Image Coming Soon!

<br />

## Lab Topology - AWS & Azure Architecture 

Image Coming Soon!