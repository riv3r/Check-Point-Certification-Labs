# [ether-labs] Check Point Certified Troubleshooting Associate (CCTA)

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
This repository provides learning labs for the Check Point Certified Troubleshooting Associate (CCTA) certification.

You can find the official training brief [here](https://www.checkpoint.com/downloads/training/DOC-Training-Data-Sheet-CCTA-R81.10-V1.0.pdf).

ether-net produced lab manuals are 100% free to use. Always. You can fork and modify all exercises to your heart's content.

Detailed answer guides are coming soon as an optional paid resource through Leanpub while this repo is maintained.

<br />

## Pre-Requisites
The following are required or recommended:
1. Check Point Certified Security Administrator (CCSA) or ideally Security Expert (CCSE) knowledge / equivalent experience
2. Familiarity with bash and Linux fundamentals
3. A device with Terraform installed and configured with AWS

<br />

## CCTA Exam Domains
Please note that Check Point do not release weightings for each domain.
* Domain 1: Introduction to Troubleshooting
* Domain 2: Fundamentals of Traffic Monitoring
* Domain 3: SmartConsole and Policy Installation Troubleshooting
* Domain 4: Identity Awareness Troubleshooting
* Domain 5: Application Control and URL Filtering Troubleshooting
* Domain 6: Troubleshooting Issues with Network Address Translation
* Domain 7: Understanding Threat Prevention Policy
* Domain 8: License and Contracts Troubleshooting

<br />

## CCTA Learning Objectives
* Identify online resources for Check Point security products and solutions.
* Demonstrate understanding of capture packet technologies.
* Demonstrate understanding of Firewall chain modules, Kernel and User Mode, and Kernel and User Space.
* Use Linux and Check Point utilities to review processes and system information.
* Troubleshoot log collection issues and interrupted communications.
* Monitor network activity and traffic flow.
* Demonstrate understanding of Check Point SmartConsole and Policy installation.
* Investigate and troubleshoot issues with Check Point SmartConsole and Policy installation.
* Demonstrate understanding of Check Point Identity Awareness.
* Investigate and troubleshoot issues with Check Point Identity Awareness.
* Demonstrate understanding of Check Point Application Control and URL Filtering.
* Investigate and troubleshoot issues with Check Point Application Control and URL Filtering.
* Demonstrate understanding of Check Point Network Address Translation.
* Investigate and troubleshoot issues with Check Point Network Address Translation.
* Demonstrate understanding of Check Point Threat Prevention.
* Investigate and troubleshoot issues with Check Point Threat Prevention.
* Demonstrate understanding of Check Point licenses and contracts.
* Investigate and troubleshoot Check Point licenses and contracts.

<br />

## Lab Cost Estimate

TBA

<br />

## CCTA Labs
There are TWO (2) types of labs:
1. Certification Aligned = These are aligned with certification objectives
2. Industry Skill = Labs focused on common real-world tasks a CCAS may perform - these are not necessarily required to prepare for the certification exam.

| Lab ID  | Type | Description |
|---------|------|-------------|----------------|
| CCTA-01 | Certification Aligned | Using tcpdump and Wireshark | 
| CCTA-02 | Certification Aligned | Viewing Firewall Chain Modules |
| CCTA-03 | Certification Aligned | Using Basic Linux and Check Point Commands |
| CCTA-04 | Certification Aligned | Troubleshooting Logging Communication Issues | 
| CCTA-05 | Certification Aligned | Analyzing Traffic Captures |
| CCTA-06 | Certification Aligned | Troubleshooting SmartConsole and Using SmartConsole Tools |
| CCTA-07 | Certification Aligned | Troubleshooting Identity Awareness |
| CCTA-08 | Certification Aligned | Troubleshooting Application Control and URL Filtering |
| CCTA-09 | Certification Aligned | Investigating Network Address Translation Issues |
| CCTA-10 | Certification Aligned | Evaluating Advanced Threat Prevention Products |
| CCTA-11 | Certification Aligned | Verifying Licenses |
| CCTA-12 | Industry Skill | Ticket #1 - Network Team Cannot Remotely Access Infrastructure |
| CCTA-13 | Industry Skill | Ticket #2 - Security Operations Monitoring Failing |
| CCTA-14 | Industry Skill | Ticket #3 - SmartConsole Performance Degradation Reported |
| CCTA-15 | Industry Skill | Ticket #4 - Cannot Install New Access Control Policy |
| CCTA-16 | Industry Skill | Ticket #5 - Users Cannot Access Fileshares |
| CCTA-17 | Industry Skill | Ticket #6 - Traffic to O365 Sporadically Being Dropped |
| CCTA-18 | Industry Skill | Ticket #7 - ClusterXL Sync Issues Detected |
| CCTA-19 | Industry Skill | Ticket #8 - High CPU Utilisation Reported on Firewall |
| CCTA-20 | Industry Skill | Ticket #9 - Replaced Check Point Appliance Not Enforcing Security Policy |
| CCTA-21 | Industry Skill | Ticket #10 - Emergency Security Policy Unload Required |

<br />

## Lab Topology - Check Point

Image Coming Soon!

<br />

## Lab Topology - AWS Architecture 

Image Coming Soon!