# [ether-labs] Check Point Certified Automation Specialist (CCAS)

**Status**\
<span style="color:red">UNDER DEVELOPMENT<span>

**Last Updated**\
Friday 16th September 2022

**Target GAIA Version**\
R80.10 with R81.10 differences highlighted

<br />

## DISCLAIMER - READ THIS IF YOU WANT LABS TO WORK

By using any of the Terraform code in this repo you acknowledge that ether-net is not responsible for...:
1. The accuracy of cost estimates
2. Costs incurred by running these labs, including any unplanned costs
3. Damages incurred if you build your infrastructure within a production cloud environment

To prove that you have fully read, comprehended, and acknowledged this section you **must** change the `disclaimer_accepted` variable in tfvars.tf to `TRUE` for the Terraform build process to work.

<br />

## Overview
This repository provides learning labs for the Check Point Certified Automation Specialist (CCAS) certification.

You can find the official training brief [here](https://www.checkpoint.com/downloads/training/CCAS-R80-x-course-overview.pdf).

ether-net produced lab manuals are 100% free to use. Always. You can fork and modify all exercises to your heart's content.

Detailed answer guides are coming soon as an optional paid resource through Leanpub while this repo is maintained.

<br />

## Pre-Requisites
The following are required or recommended:
1. Check Point Certified Security Administrator (CCSA) or Security Expert (CCSE) knowledge / equivalent experience
2. Familiarity with bash, python, and REST APIs - we do not cover programming fundamentals here
3. A device with Terraform installed and configured with AWS

<br />

## CCAS Exam Domains
Please note that Check Point do not release weightings for each domain.
* Domain 1: Introduction to Automation and Orchestration
* Domain 2: Check Point APIs
* Domain 3: API Development
* Domain 4: API Troubleshooting
* Domain 5: Self-Service Web Portals

<br />

## CCAS Learning Objectives
* Explain how automation and orchestraton work together
* Understand the key drivers for incorporating automation and orchestration into security management
* Execute a shell script that demonstrates how to build a comprehensive Security Policy
* Recognize how the Check Point API framework integrates with R80 Security Management to support automation and orchestration of daily tasks
* Describe Check Point API tools and demonstrate how they are used to manage Check Point Security Management solutions
* Demonstrate how to define new objects and modify existing ones by using the Check Point API
* Demonstrae how to create API commands to efficiently maintain the Check Point Security Management Server database
* Demonstrate how to use different methods to update the database with API commands
* Become familiar with client-side and server-side scripting and scripting languages
* Understand how to use the Bash shell to develop APIs
* Recognize and describe many of the open source tools that are available to assist with API development
* Demonstrate how to use a custom REST application to update the database of a Security Management Server
* Demonstrate how to use Postman to manage the Security Policy database through the Check Point API
* Understand what steps to take to troubleshoot and debug API scripts
* Demonstrate basic troubleshooting techniques by debugging messages in various forms
* Understand how to use self-service poral capabilities to provide general IT services
* Recognize how automation tools work with Check Point APIs t automate security management tasks and orchestrate workflow behind service portals
* Demonstrate common tasks that are automated in a Web portal to manage the Security Policy

<br />

## Lab Cost Estimate

TBA

<br />

## CCAS Labs
There are TWO (2) types of labs:
1. Certification Aligned = These are aligned with certification objectives
2. Industry Skill = Labs focused on common real-world tasks a CCAS may perform - these are not necessarily required to prepare for the certification exam.

| Lab ID  | Type | Description | 
|---------|------|-------------|
| CCAS-01 | Certification Aligned | Demonstrate Check Point Automation & Orchestration |
| CCAS-02 | Certification Aligned | Manage objects using the Check Point API |
| CCAS-03 | Certification Aligned | Create a management API shell script |
| CCAS-04 | Certification Aligned | Execute API commands |
| CCAS-05 | Certification Aligned | Use a custom REST tool for API calls |
| CCAS-06 | Certification Aligned | Use Postman for API calls |
| CCAS-07 | Certification Aligned | Debug the Check Point Management API |
| CCAS-08 | Certification Aligned | Automate tasks using a Check Point API enabled Web Portal |
| CCAS-09 | Industry Skill | Bootstrapping Check Point Architecture |
| CCAS-10 | Industry Skill | Automate Security Gateway Onboarding |
| CCAS-11 | Industry Skill | Automate Security Gateway Configuration |
| CCAS-12 | Industry Skill | Automate Security Management Users, Groups, and Permissions |
| CCAS-13 | Industry Skill | Automate Unified Policy Management |
| CCAS-14 | Industry Skill | Automate Common Troubleshooting Checks |
| CCAS-15 | Industry Skill | Automate Security Policy Audit |
| CCAS-16 | Industry Skill | Automate VPN Commissioning & Tear-Down  |
| CCAS-17 | Industry Skill | Automate Simple Log Analysis |
| CCAS-18 | Industry Skill | Automate High Availability Management |
| CCAS-19 | Industry Skill | Ansible & Check Point |
| CCAS-20 | Industry Skill | Terraform & Check Point |

<br />

## Lab Topology - Check Point

Image Coming Soon!

<br />

## Lab Topology - AWS Architecture 

Image Coming Soon!