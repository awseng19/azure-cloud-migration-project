# azure-cloud-migration-project
Design and implementation of a cloud infrastructure for a company using Microsoft Azure, including virtual machines, virtual networking, network security, backup, monitoring, and access control.
# Company IT Infrastructure Migration to Microsoft Azure

## Project Overview

This project demonstrates the migration of a company's IT infrastructure to Microsoft Azure.

The goal was to design and deploy a basic cloud infrastructure that provides virtual computing resources, networking, security, backup, monitoring, and access management.

## Scenario

A company wanted to move part of its existing IT infrastructure to the cloud to improve resource management, scalability, security, backup, and remote access.

## Azure Resources

- Resource Group
- Virtual Network (VNet)
- Subnet
- Network Security Group (NSG)
- Windows Virtual Machine
- Public IP Address
- Azure Backup
- Monitoring
- Role-Based Access Control (RBAC)

## Implementation

### 1. Resource Group

Created a dedicated Resource Group to organize and manage the Azure resources used in the project.

### 2. Virtual Network

Created a Virtual Network and Subnet to provide network connectivity for the virtual machine.

### 3. Network Security

Configured a Network Security Group to control inbound and outbound network traffic.

An RDP rule was configured for TCP port 3389 to support remote administration.

### 4. Virtual Machine

Deployed a Windows Virtual Machine as a cloud-based computing resource for the company.

### 5. Backup

Configured Azure Backup to provide data protection and recovery capabilities.

### 6. Monitoring

Configured monitoring to observe the virtual machine and infrastructure performance.

### 7. Access Management

Used Azure Role-Based Access Control (RBAC) concepts to manage permissions and control access to cloud resources.

## Skills Demonstrated

- Microsoft Azure
- Cloud Infrastructure
- Virtual Machines
- Virtual Networking
- Network Security
- NSG Configuration
- Backup and Recovery
- Cloud Monitoring
- RBAC
- Troubleshooting
- System Administration

## Project Status

The core Azure infrastructure was deployed and configured. Remote connectivity was tested as part of the troubleshooting process.
