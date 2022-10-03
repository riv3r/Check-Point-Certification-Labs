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
| Chapter | Description |
|---------|-------------|
| **PART 1: CHECK POINT ARCHITECTURE** |
| 1 |**Check Point Architecture** |
| 2 | **Understanding the Control, Data, and Management Planes** |
| 3 | Lab 1: Provisioning the Lab Environment |
| 4 | Lab 2: Configure Network Interfaces & Bonding |
| 5 | Lab 3: Enable Discoverability with LLDP & ICMP RD |
| **PART 2: UNDERSTANDING TRAFFIC FLOWS** |
| 6 | **How Layer 2 Impacts Security Management** |
| 7 | Lab 4: Configuring VLANs |
| 8 | Lab 5: Exploring ARP |
| 9 | Lab 6: Exploring Suboptimal Traffic Forwarding Due to Layer 2 |
| 10 | **Packet Processing Overview** |
| 11 | Lab 7: Exploring SecureXL |
| 12 | Lab 8: Exploring CoreXL |
| 13 | **Packet Capturing Techniques** |
| 14 | Lab 9: Packet Capturing - TCP Dump |
| 15 | Lab 10: Packet Capturing - fw mon |
| 16 | Lab 11: Identify Dropped Connections with Kernel Debug |
| 17 | Lab 12: Traffic Mirroring & Decryption |
| 18 | Lab 13: Analysing Traffic with NetFlow |
| 19 | **Check Point VSX Overview** |
| 20 | Lab 14: Using VSX to Extend a VRF across the Security Layer |
| **PART 3: DESIGNING FOR REDUNDANCY** |
| 21 | **Virtual Routing Redundancy Protocol (VRRP)** |
| 22 | Lab 15: VRRP - Basic Configuration & Validation |
| 23 | Lab 16: VRRP - Authentication |
| 24 | Lab 17: VRRP - Advanced Topics |
| 25 | **Check Point ClusterXL** |
| 26 | Lab 18: ClusterXL - High Availability Mode |
| 27 | Lab 19: ClusterXL - Load Sharing Unicast Mode | 
| 28 | Lab 20: ClusterXL - Active-Active Mode |
| **PART 4: ROUTING** |
| 29 | **Routing Protocols & Tools** |
| 30 | Lab 21: Exploring Limitation of Static Routes |
| 31 | Lab 22: RIPv1 |
| 32 | Lab 23: RIPv2 |
| 33 | Lab 24: RIPng |
| 34 | Lab 25: OSPF - Single Area Network |
| 35 | Lab 26: OSPF - Multi Area Network |
| 36 | Lab 27: OSPF - Area Types and Considerations |
| 37 | Lab 28: OSPF - Virtual Links and GRE Tunnels |
| 38 | Lab 29: OSPF - Exploring & Manipulating Path Selection |
| 39 | Lab 30: OSPF - Authentication Methods |
| 40 | Lab 31: OSPF - Aggregation |
| 41 | Lab 32: OSPF - Redistribution |
| 42 | Lab 33: OSPF - Filtering Techniques |
| 43 | Lab 34: OSPFv3 Overview |
| 44 | Lab 35: OSPF - Using the LSDB to Draw Network Diagrams |
| 45 | Lab 36: BGP - Introduction & Basic Configuration |
| 46 | Lab 37: BGP - eBGP |
| 47 | Lab 38: BGP - Route Reflectors | 
| 48 | Lab 39: BGP - Confederations |
| 49 | Lab 40: BGP - Route Dampening |
| 50 | Lab 41: BGP - Aggregation & Filtering |
| 51 | Lab 42: BGP - IGP Redistribution Considerations |
| 52 | Lab 43: BGP - TCP MD5 Authentication |
| 53 | Lab 44: Policy Based Routing |
| 54 | Lab 45: Bidirection Forwarding Detection (BFD) |
| 55 | Lab 46: Multicast - IGMP |
| 56 | Lab 47: Multicast - PIM Dense Mode |
| 57 | Lab 48: Multicast - PIM Sparse Mode |
| 58 | Lab 49: Multicast - PIM Source-Specific Multicast |
| 59 | Lab 50: Multicast - ClusterXL Multicast Load Sharing |
| 60 | Lab 51: Check Point - Protocol Ranking / Admin Distance |
| 61 | Lab 52: Check Point - ECMP |
| 62 | Lab 53: Check Point - Route Conflict Management |
| 63 | Lab 54: Check Point - Multithreading the Routing Daemon |
| 64 | Lab 55: Check Point - Exploring Route Injection Mechanism (RIM) |
| 65 | Lab 56: Check Point - Logging & Debugging Routing Protocols |
| 66 | Lab 57: ClusterXL Implications with Dynamic Routing Protocols |
| **PART 5: VIRTUAL PRIVATE NETWORKS (VPNs)** |
| 67 | **Check Point VPN Architecture & Types** |
| 68 | Lab 58: Configuring the VPN Lab |
| 69 | Lab 59: Exploring Impact VPNs have on Traffic Processing |
| 70 | Lab 60: S2S VPN - Pure Check Point |
| 71 | Lab 61: S2S VPN - Third Party (Cisco) |
| 72 | Lab 62: Remote Access VPN - Access Policies |
| 73 | Lab 63: Remote Access VPN - Hub Mode |
| 74 | Lab 64: Remote Access VPN - Office Mode |
| 75 | Lab 64: Remote Access VPN - Deploying the Remote Access Client |
| 76 | Lab 65: Remote Access VPN - Enabling Mobile Access |
| 77 | Lab 66: Remote Access VPN - MEPs & Secondary COnnect |
| 78 | Lab 67: Layer 2 Tunneling Protocol (L2TP) |
| 79 | Lab 68: Exploring VPN behind NAT'd Connection |
| 80 | Lab 69: Troubleshooting Common VPN Issues |
| **PART 6: QUALITY OF SERVICE (QoS)** |
| 81 | **Check Point QoS Architecture** |
| 82 | Lab 70: Configuring the QoS Lab | 
| 83 | Lab 71: Create a Basic QoS Policy |
| 84 | Lab 72: Explore Impact QoS has on Traffic Processing |
| 85 | Lab 73: QoS Guarantees and Limits |
| 86 | Lab 74: Differentiated Services (DiffServ) |
| 87 | Lab 75: Low Latency Queueing |
| 88 | Lab 76: QoS Logging | 
| 89 | Lab 77: Monitoring QoS Effectiveness |
| 90 | Lab 78: Verify QoS end-to-end |
| **PART 7: INFRASTRUCTURE MAINTENANCE** |
| 91 | **Check Point Configuration Hardening Tips** | 
| 92 | Lab 79: SSH Passwordless Authentication |
| 93 | Lab 80: AAA with RADIUS Server (Active Directory) |
| 94 | Lab 81: AAA with TACACS+ Server (Cisco ISE) |
| 95 | Lab 82: AAA with LDAP Server (Active Directory) |
| 96 | Lab 83: Configuring Logging & Syslog Server |
| 97 | Lab 84: Monitoring with SNMP |
| 98 | Lab 85: Collecting Data for Check Point Support |
| 99 | **Check Point Expert Mode** |
| 100 | Lab 86: Exploring Expert Mode |
| **PART 8: INFRASTRUCTURE SERVICES**|
| 101 | **Check Point & Network Address Translation (NAT)** |
| 102 | Lab 87: Explore Impact NAT has on Traffic Processing |
| 103 | Lab 88: NAT - Configure Hide NAT |
| 104 | Lab 89: NAT - Conifgure Static NAT 
| 105 | **Dynamic Host Configuration Protocol (DHCP)** |
| 106 | Lab 90: DHCP - Configuration |
| 107 | Lab 91: DHCP - Relay Agents
| **PART 9: AUTOMATION** |
| 108 | **Check Point Automation Capabilities** |
| 109 | Lab 92: Configuring the Automation Lab |
| 110 | Lab 93: Exploring SmartConsole Scripts |
| 111 | Lab 94: Exploring Management API |
| 112 | Lab 95: Exploring GAIA API |
| 113 | Lab 96: Exploring Ansible Check Point Modules |
| 114 | Lab 97: Orchestrating simple CRUD management operations |
| 115 | Lab 98: Orchestrating configuration drift detection |
| **PART 10: TYING IT ALL TOGETHER** |
| 116 | Lab 99: Challenge Lab 1 |
| 117 | Lab 100: Challenge Lab 2 | 
| 118 | Lab 101: Challenge Lab 3 |
| 119 | Lab 102: Challenge Lab 4 |
| 120 | Lab 103: Challenge Lab 5 |

<br />

## Lab Topologies - Check Point

Image Coming Soon!

<br />

## Lab Topology - Virtual Architecture

Image Coming Soon!