# [ether-labs] Check Point Advanced Networking

**Status**\
<span style="color:red">UNDER DEVELOPMENT<span>

**Last Updated**\
Thursday 29th September 2022

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
This repository provides learning labs for Check Point Security Engineers who wish to understand the product's advanced routing and switching capabilities.

There is no associated Check Point certification with this course.

ether-net produced lab manuals are 100% free to use. Always. You can fork and modify all exercises to your heart's content.

Detailed walk throughs and answer guides are coming soon as an optional paid resource through Leanpub while this repo is maintained.

<br />

## Learning Objectives
1. Describe Check Point Security Management architecture
2. Differentiate between the control, data, and management planes
3. Explain how packet processing occurs on Check Point Security Gateways
4. Identify the impact to packet processing on Check Point Security Gateways when NAT, VPNs, or QoS are configured
5. Examine the impact Check Point security enhancement and high availability technologies has on traffic forwarding, processing, and dynamic routing protocols:
    * 5.1. ClusterXL
    * 5.2. CoreXL
    * 5.3. SecureXL
6. Examine the impact Layer 2 protocols (e.g.: 802.1d STP) have on security management
7. Implement a VRF design across a DMZ using Check Point VSX
8. Configure and validate standard and advanced networking features on Check Point Security Gateways via Web Portal and CLISH:
    * 8.1 General administration
        * 8.1.a Managing MAC address table
        * 8.1.b Interfaces
        * 8.1.c Bonding
    * 8.2 Layer 2 Protocols
        * 8.2.a LLDP
    * 8.3 VLANs
    * 8.4 Routing Concepts
        * 8.4.a Static routes
        * 8.4.b Protocol Ranking (Administrative Distance)
        * 8.4.c Policy Based Routing
        * 8.4.d Route filtering 
        * 8.4.e Route aggregation
        * 8.4.f Route redistribution
        * 8.4.g Routing protocol authentication
        * 8.4.h Bidirectional Forwarding Detection (BFD)
    * 8.5 Check Point Advanced Routing Features
        * 8.5.a Multithreaded Routing Daemon
        * 8.5.b Route Injection Mechanism (RIM)
        * 8.5.c Logging & Debugging dyanmic routing protocols
    * 8.6 Routing Protocols
        * 8.6.a RIP and RIPng
        * 8.6.b OSPFv2 and OSPFv3
        * 8.6.c BGP
    * 8.7 Multicast
        * 8.7.a IGMPv2, IGMPv3
        * 8.7.b PIM (Dense Mode, Sparse Mode, Source-Specific)
    * 8.8 NAT
        * 8.8.a Hide NAT
        * 8.8.b Static NAT
        * 8.8.c Manual NAT Policy
    * 8.9 Virtual Private Networks (VPNs)
        * 8.9.a VPN Access Policies
        * 8.9.b IPSec VPN
        * 8.9.c Remote Access VPN
        * 8.9.d Mobile Access VPN
        * 8.9.e Layer 2 Tunneling Protocol (L2TP)
    * 8.10 Quality of Service (QoS)
        * 8.10.a QoS Rule Base
        * 8.10.b Guarantees & Limits
        * 8.10.c Differentiated Services (DiffServ)
        * 8.10.d Low Latency Queuing (LLQ)
        * 8.10.e Global & Interface Properties
        * 8.10.f QoS Log Collection
    * 8.11 Infrastructure Services
        * 8.11.a Secure Remote Access (AAA, LDAP, RADIUS, TACACS+)
        * 8.11.b DHCP
9. Implement simple automation using:
    * 9.1 SmartConsole scripts
    * 9.2 Bash scripts
    * 9.3 Check Point APIs
        * 9.3.a Management API
        * 9.3.b GAIA API
    * 9.4 Check Point Ansible Modules

## Pre-Requisites
The following are required or recommended:
1. Check Point Certified Security Administrator (CCSA) or Security Expert (CCSE) knowledge / equivalent experience
2. Familiarity with routing and switching concepts
<br />

## Lab Cost Estimate
TBA
<br />

## Learning Topics & Labs
| ID | Description |
|---------|-------------|
| **PART 1: GETTING STARTED WITH CHECK POINT** |
| **Chapter 1** | **Getting Started with Check Point** |
| Lab 1 | Creating a Check Point Account |
| **Chapter 2** | **Public Documentation & Community Resources** |
| Lab 2 | Creating a Check Mates Account |
| Lab 3 | Getting Help with Secure Knowledge (SK) Articles |
| **PART 2: CHECK POINT ARCHITECTURE** |
| **Chapter 3** |**Check Point Architecture** |
| **Chapter 4** | **Understanding the Control, Data, and Management Planes** |
| Lab 4 | Provisioning the Lab Environment |
| Lab 5 | Configure Network Interfaces & Bonding |
| Lab 6 | Enable Discoverability with LLDP & ICMP RD |
| Lab 7 | Secure Internal Communications (SIC)
| **PART 3: UNDERSTANDING TRAFFIC FLOWS** |
| **Chapter 5** | **How Layer 2 Impacts Security Management** |
| Lab 8 | Configuring VLANs |
| Lab 9 | Exploring ARP |
| Lab 10 | Exploring Suboptimal Traffic Forwarding Due to Layer 2 |
| **Chapter 6** | **Packet Processing Overview** |
| Lab 11 | Exploring SecureXL |
| Lab 12 | Exploring CoreXL |
| **Chapter 7** | **Packet Capturing Techniques** |
| Lab 13 | Packet Capturing - TCP Dump |
| Lab 14 | Packet Capturing - fw mon |
| Lab 15 | Identify Dropped Connections with Kernel Debug |
| Lab 16 | Traffic Mirroring & Decryption |
| Lab 17 | Analysing Traffic with NetFlow |
| **Chapter 8** | **Check Point VSX Overview** |
| Lab 18 | Using VSX to Extend a VRF across the Security Layer |
| **PART 4: DESIGNING FOR REDUNDANCY** |
| **Chapter 9** | **Virtual Routing Redundancy Protocol (VRRP)** |
| Lab 19 | VRRP - Basic Configuration & Validation |
| Lab 20 | VRRP - Authentication |
| Lab 21 | VRRP - Advanced Topics |
| **Chapter 10** | **Check Point ClusterXL** |
| Lab 22 | ClusterXL - High Availability Mode |
| Lab 23 | ClusterXL - Load Sharing Unicast Mode | 
| Lab 24 | ClusterXL - Active-Active Mode |
| **Chapter 11** | **Check Point Maestro** |
| **PART 5: ROUTING** |
| **Chapter 12** | **Unicast Routing Protocols & Tools** |
| Lab 25 | Exploring Limitation of Static Routes |
| Lab 26 | RIPv1 |
| Lab 27 | RIPv2 |
| Lab 28 | OSPF - Single Area Network |
| Lab 29 | OSPF - Multi Area Network |
| Lab 30 | OSPF - Area Types and Considerations |
| Lab 31 | OSPF - Virtual Links and GRE Tunnels |
| Lab 32 | OSPF - Exploring & Manipulating Path Selection |
| Lab 33 | OSPF - Authentication Methods |
| Lab 34 | OSPF - Aggregation |
| Lab 35 | OSPF - Redistribution |
| Lab 36 | OSPF - Filtering Techniques |
| Lab 37 | OSPF - Using the LSDB to Draw Network Diagrams |
| Lab 38 | BGP - Introduction & Basic Configuration |
| Lab 39 | BGP - eBGP |
| Lab 40 | BGP - Route Reflectors | 
| Lab 41 | BGP - Confederations |
| Lab 42 | BGP - Route Dampening |
| Lab 43 | BGP - Aggregation & Filtering |
| Lab 44 | BGP - IGP Redistribution Considerations |
| Lab 45 | BGP - TCP MD5 Authentication |
| Lab 46 | Policy Based Routing |
| Lab 47 | Bidirection Forwarding Detection (BFD) |
| **Chapter 13** | **Multicast Routing** |
| Lab 48 | Multicast - IGMP |
| Lab 49 | Multicast - PIM Dense Mode |
| Lab 50 | Multicast - PIM Sparse Mode |
| Lab 51 | Multicast - PIM Source-Specific Multicast |
| Lab 52 | Multicast - ClusterXL Multicast Load Sharing |
| Lab 53 | Check Point - Protocol Ranking / Admin Distance |
| Lab 54 | Check Point - ECMP |
| Lab 55 | Check Point - Route Conflict Management |
| Lab 56 | Check Point - Multithreading the Routing Daemon |
| Lab 57 | Check Point - Exploring Route Injection Mechanism (RIM) |
| Lab 58 | Check Point - Logging & Debugging Routing Protocols |
| Lab 59 | ClusterXL Implications with Dynamic Routing Protocols |
| **PART 6: VIRTUAL PRIVATE NETWORKS (VPNs)** |
| **Chapter 14** | **Check Point VPN Architecture & Types** |
| Lab 60 | Configuring the VPN Lab |
| Lab 61 | Exploring Impact VPNs have on Traffic Processing |
| Lab 62 | S2S VPN - Pure Check Point |
| Lab 63 | S2S VPN - Third Party (Cisco) |
| Lab 64 | Remote Access VPN - Access Policies |
| Lab 65 | Remote Access VPN - Hub Mode |
| Lab 66 | Remote Access VPN - Office Mode |
| Lab 67 | Remote Access VPN - Deploying the Remote Access Client |
| Lab 68 | Remote Access VPN - Enabling Mobile Access |
| Lab 69 | Remote Access VPN - MEPs & Secondary COnnect |
| Lab 70 | Layer 2 Tunneling Protocol (L2TP) |
| Lab 71 | Exploring VPN behind NAT'd Connection |
| Lab 72 | Troubleshooting Common VPN Issues |
| **PART 7: QUALITY OF SERVICE (QoS)** |
| **Chapter 15** | **Check Point QoS Architecture** |
| Lab 73 | Configuring the QoS Lab | 
| Lab 74 | Create a Basic QoS Policy |
| Lab 75 | Explore Impact QoS has on Traffic Processing |
| Lab 76 | QoS Guarantees and Limits |
| Lab 77 | Differentiated Services (DiffServ) |
| Lab 78 | Low Latency Queueing |
| Lab 79 | QoS Logging | 
| Lab 80 | Monitoring QoS Effectiveness |
| Lab 81 | Verify QoS end-to-end |
| **PART 8: INFRASTRUCTURE MAINTENANCE** |
| **Chapter 16** | **Check Point Configuration Hardening Tips** | 
| Lab 82 | SSH Passwordless Authentication |
| Lab 83 | AAA with RADIUS Server (Active Directory) |
| Lab 84 | AAA with TACACS+ Server (Cisco ISE) |
| Lab 85 | AAA with LDAP Server (Active Directory) |
| Lab 86 | Configuring Logging & Syslog Server |
| Lab 87 | Monitoring with SNMP |
| Lab 88 | Collecting Data for Check Point Support |
| **Chapter 17** | **Check Point Expert Mode** |
| Lab 89 | Exploring Expert Mode |
| **PART 9: INFRASTRUCTURE SERVICES**|
| **Chapter 18* | **Check Point & Network Address Translation (NAT)** |
| Lab 90 | Explore Impact NAT has on Traffic Processing |
| Lab 91 | Hide NAT |
| Lab 92 | Static NAT |
| Lab 93 | NAT Pools |
| **Chapter 19** | **Dynamic Host Configuration Protocol (DHCP)** |
| Lab 94 | DHCP Configuration |
| Lab 95 | DHCP Relay Agents |
| **PART 10: IPv6** |
| **Chapter 16** | **IPv6 Overview** |
| Lab 96 | Configuring the IPv6 Lab |
| Lab 97 | Enabling IPv6 Static Connectivity |
| Lab 98 | Creating an IPv6 Access Control Policy |
| Lab 99 | IPv6 Neighbour Discovery | 
| Lab 100 | VRRPv3 |
| **Chapter 17** | **IPv6 Routing Considerations** |
| Lab 101 | RIPng |
| Lab 102 | OSPFv3 Overview & Differences |
| Lab 103 | OSPFv3 IPSec Routing |
| Lab 104 | OSPFv3 ClusterXL Considerations |
| Lab 105 | MP-BGP - IPv6 Only |
| Lab 106 | MP-BGP - IPv4 and IPv6 |
| Lab 107 | IPv6 Aggregation, Filtering & Redistribution |
| Lab 108 | Exploring Dual Stack Environments |
| **PART 11: AUTOMATION & ORCHESTRATION** |
| **Chapter 22** | **Check Point Automation Capabilities** |
| Lab 109 | Configuring the Automation Lab |
| Lab 110 | Exploring SmartConsole Scripts |
| Lab 111 | Exploring Management API |
| Lab 112 | Exploring GAIA API |
| **Chapter 23** | **Check Point & Ansible**
| Lab 113 | Exploring Ansible Check Point Modules |
| Lab 114 | Orchestrating simple CRUD management operations |
| Lab 115 | Orchestrating configuration drift detection |
| **PART 12: TYING IT ALL TOGETHER** |
| Lab 116 | Challenge Lab 1 |
| Lab 117 | Challenge Lab 2 | 
| Lab 118 | Challenge Lab 3 |
| Lab 119 | Challenge Lab 4 |
| Lab 120 | Challenge Lab 5 |
| **PART 13: NEXT STEPS** |
| **Chapter 24** | **Check Point Training & Certification** |

<br />

## Lab Topologies - Check Point

Image Coming Soon!

<br />

## Lab Topology - Virtual Architecture

Image Coming Soon!