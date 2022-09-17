# [ether-labs] Check Point Certified Troubleshooting Expert (CCTE)

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
This repository provides learning labs for the Check Point Certified Troubleshooting Expert (CCTE) certification.

You can find the official training brief [here](https://www.checkpoint.com/downloads/training/DOC-Training-Data-Sheet-CCTE-R81.10-V1.0.pdf).

ether-net produced lab manuals are 100% free to use. Always. You can fork and modify all exercises to your heart's content.

Detailed answer guides are coming soon as an optional paid resource through Leanpub while this repo is maintained.

<br />

## Pre-Requisites
The following are required or recommended:
1. Check Point Certified Security Expert (CCSE) and Check Point Certified Troubleshooting Administrator (CCTA) or equivalent knowledge/experience
2. Basic Linux systems administration skillset (e.g.: RHCSA or equivalent)
3. A device with Terraform installed and configured with AWS

<br />

## CCTE Exam Domains
Please note that Check Point do not release weightings for each domain.
* Domain 1: Advanced Troubleshooting Techniques
* Domain 2: Advanced Logs and Monitoring
* Domain 3: Management Database and Processes
* Domain 4: Advanced Kernel Debugging
* Domain 5: User Mode Troubleshooting
* Domain 6: Advanced Identity Awareness Troubleshooting
* Domain 7: Advanced Access Control
* Domain 8: Site-to-Site Virtual Private Network Troubleshooting
* Domain 9: Client-to-Site Virtual Private Networking Troubleshooting

<br />

## CCTE Learning Objectives
* Demonstrate understanding how to use advanced troubleshooting tools and techniques including: Interpreting diagnostic data with CPInfo, Collecting and reading statistical data using CPView, and Advanced troubleshooting risks.
Describe the use of Logs and SmartEvent in troubleshooting.
* Describe the log indexing system and issues that can occur.
* Discuss methods to troubleshoot log indexing in SmartLog and SmartEvent.
* Explain the databases used in Security Management operations.
* Identify common troubleshooting database issues.
* Discuss Management Processes.
* Demonstrate understanding of advance troubleshooting tools and techniques including: How the kernel handles traffic, How to troubleshoot issues using chain modules, How to use the two main procedures for debugging the Firewall kernel, and How the two main procedures for debugging the Firewall kernel differ.
* Demonstrate understanding of user mode debugging, including collecting and interpreting process debugs.
* Debug user mode processes.
* Discuss advanced Identity awareness troubleshooting.
* Learn to run debugs on Identity Awareness.
* Explain Unifed Access Control flow and processes.
* Explain Access Control kernel debugs.
* Describe Access Control process debugs.
* Explain basic and advanced Site-to-Site VPN troubleshooting tools and techniques, including: Packet captures, IKE debugs, and VPN process debugs.
* Explain Client-to-Site VPN troubleshooting tools and techniques, including: Remote access troubleshooting and Mobile access troubleshooting.

<br />

## Lab Cost Estimate

TBA

<br />

## CCTE Labs
There are TWO (2) types of labs:
1. Certification Aligned = These are aligned with certification objectives
2. Industry Skill = Labs focused on common real-world tasks a CCAS may perform - these are not necessarily required to prepare for the certification exam.

| Lab ID  | Type | Description | Estimated Cost |
|---------|------|-------------|----------------|
| CCTE-01 | Certification Aligned | Collecting and Reading CPInfo | - |
| CCTE-02 | Certification Aligned | Collecting and Reading CPView Data | - |
| CCTE-03 | Certification Aligned | Troubleshooting SmartLog | - |
| CCTE-04 | Certification Aligned | Troubleshooting SmartEvent | - |
| CCTE-05 | Certification Aligned | Troubleshooting Database Issues | - |
| CCTE-06 | Certification Aligned | Debugging Security Gateway Kernel | - |
| CCTE-07 | Certification Aligned | Debugging User Mode Processes | - |
| CCTE-08 | Certification Aligned | Debugging Identity Awareness | - |
| CCTE-09 | Certification Aligned | Debugging Unified Policy Inspection | - |
| CCTE-10 | Certification Aligned | Troubleshooting Site-to-Site VPN | - |
| CCTE-11 | Certification Aligned | Debugging Remote Access VPN | - |
| CCTE-12 | Industry Skill | Ticket #1 - x | - |
| CCTE-13 | Industry Skill | Ticket #2 - x | - |
| CCTE-14 | Industry Skill | Ticket #3 - x | - |
| CCTE-15 | Industry Skill | Ticket #4 - x | - |
| CCTE-16 | Industry Skill | Ticket #5 - x | - |
| CCTE-17 | Industry Skill | Ticket #6 - x | - |
| CCTE-18 | Industry Skill | Ticket #7 - x | - |
| CCTE-19 | Industry Skill | Ticket #8 - x | - |
| CCTE-20 | Industry Skill | Ticket #9 - x | - |
| CCTE-21 | Industry Skill | Ticket #10 - x | - |
| CCTE-22 | Industry Skill | Ticket #11 - x | - |
| CCTE-23 | Industry Skill | Ticket #12 - x | - |
| CCTE-24 | Industry Skill | Ticket #13 - x | - |
| CCTE-25 | Industry Skill | Ticket #14 - x | - |
| CCTE-26 | Industry Skill | Ticket #15 - x | - |
| CCTE-27 | Industry Skill | Ticket #16 - x | - |
| CCTE-28 | Industry Skill | Ticket #17 - x | - |
| CCTE-29 | Industry Skill | Ticket #18 - x | - |
| CCTE-30 | Industry Skill | Ticket #19 - x | - |
| CCTE-31 | Industry Skill | Ticket #20 - x | - |

<br />

## Lab Topology - Check Point

Image Coming Soon!

<br />

## Lab Topology - AWS Architecture 

Image Coming Soon!