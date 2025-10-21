# Packet-Tracer-Network-simulation-tool
# 🖧 Basic Wired and Wireless Network Configuration (Cisco Packet Tracer)

## 📘 Project Overview
This project demonstrates how to configure **both a simple wired network** and a **basic wireless network** using **Cisco Packet Tracer**.  
It includes step-by-step setup instructions, IP configuration, connectivity verification, and packet simulation between devices.



## Part 1: Simple Wired Network

###  Objective
To create a basic wired LAN with two PCs and a switch, connect them using appropriate cables, configure IP addresses, and verify connectivity using ping tests and packet simulation.

### Steps

#### 1. Create the Network
- Add **two PCs** from the *End Devices* section.
- Add a **2960 Switch** from the *Switches* section.

#### 2. Connect Devices
- Use **Copper Straight-Through** cables.
- Connect:
  - **PC1 FastEthernet0 → Switch FastEthernet0/1**
  - **PC2 FastEthernet0 → Switch FastEthernet0/2**

#### 3. Configure IP Addresses
| Device | IP Address     | Subnet Mask     |
|---------|----------------|-----------------|
| PC1     | 192.168.1.1    | 255.255.255.0   |
| PC2     | 192.168.1.2    | 255.255.255.0   |

#### 4. Verify Connectivity
- On **PC1**, open Command Prompt and type:
  ```bash
  ping 192.168.1.2
