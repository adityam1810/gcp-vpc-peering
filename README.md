# gcp-vpc-peering
Hands-on implementation of Google Cloud VPC Peering using gcloud CLI and Google Cloud Console.



## Overview

This project demonstrates how to establish private communication between two Virtual Private Clouds (VPCs) using Google Cloud VPC Peering.

---

## Objectives

- Create two custom VPCs
- Configure subnets
- Launch Compute Engine VMs
- Configure firewall rules
- Establish VPC Peering
- Verify automatic route exchange

---

## Services Used

- Google Cloud Platform
- Compute Engine
- VPC Network
- Firewall Rules
- Cloud Shell
- gcloud CLI

---

## Architecture

                Internet
                     |
      -----------------------------
      |                           |
  Network-A                 Network-B
 10.0.0.0/16               10.8.0.0/16
      |                           |
     VM-A                       VM-B
         \                   /
          \                 /
              VPC Peering
---

## Project Workflow

1. Create VPC Network A
2. Create Subnet
3. Launch VM
4. Configure Firewall
5. Create VPC Network B
6. Configure Peering
7. Verify Routes
8. Test Connectivity

---

## Commands Used

See gcp-vpc-peering/commands

---

## Screenshots

<img width="1366" height="768" alt="Screenshot (316)" src="https://github.com/user-attachments/assets/2be98a3f-6a0b-4eb9-86ca-99acc82f376f" />


---

## Learning Outcomes

- Google Cloud Networking
- VPC Peering

  
- Route Propagation
- Firewall Configuration
- Cloud Shell
