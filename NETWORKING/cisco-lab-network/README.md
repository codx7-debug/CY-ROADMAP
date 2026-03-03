# Cisco VLAN Lab – Inter-VLAN Routing

## 📌 Overview
This lab demonstrates VLAN segmentation and inter-VLAN routing using a Cisco ISR4331 router and two Layer 2 switches.

## 🖥 Devices Used
- 1x ISR4331 Router
- 2x Cisco 2960 Switches
- 8 PCs

## 🌐 VLAN Configuration
- VLAN 10 – 192.168.10.0/24
- VLAN 20 – 192.168.20.0/24
- VLAN 30 – 192.168.30.0/24
- vlan 40 - 192.168.40.0/24

## 🔁 Routing Method
Router-on-a-Stick (802.1Q Trunking)

Subinterfaces were configured on the router:
- G0/0.10
- G0/0.20
- G0/1.30
- G0/1.40

## 🔧 Features Implemented
- VLAN segmentation
- Trunk configuration between switches and router
- Inter-VLAN routing
- IP addressing
- Connectivity testing using ping

## 🧠 Skills Demonstrated
- VLAN creation and assignment
- Subnetting
- Trunking configuration
- Router subinterfaces
- Basic troubleshooting
