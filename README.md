# Live Network Traffic Visualization & Analysis

![Kali Linux](https://img.shields.io/badge/OS-Kali%20Linux-blue?logo=kali-linux)
![VirtualBox](https://img.shields.io/badge/Environment-VirtualBox-blue?logo=virtualbox)
![EtherApe](https://img.shields.io/badge/Tool-EtherApe-orange)

This repository contains the documentation and visual results for a real-time network monitoring project. The project focuses on visualizing active packet exchanges between a local client and global web servers using a graphical topology map.

## 📂 Project Structure
* `Abstract.docx`: A high-level overview of the project objectives and findings.
* `Design_Report.docx`: Comprehensive documentation covering system architecture, network configuration, and technical implementation.
* `Screenshots/`: A collection of real-time captures showing the transition from a noisy network environment to a filtered, web-traffic-only view.

## 🚀 Project Overview
The objective of this project was to demystify the abstract concepts of the OSI model by creating a dynamic, real-time map of network traffic. Using **EtherApe** on **Kali Linux**, we intercepted live packets to visualize throughput, protocol distribution, and the client-server relationship.

### Key Features:
* **Real-Time Topology:** Graphical mapping of network nodes and TCP/IP streams.
* **Protocol Filtering:** Utilization of Berkeley Packet Filters (BPF) to isolate HTTP/HTTPS traffic (Ports 80/443).
* **Bridged Networking:** Direct physical network interaction through a virtualized environment.

## 🛠️ Technical Setup
* **Operating System:** Kali Linux (Rolling Release).
* **Virtualization:** Oracle VM VirtualBox.
* **Network Mode:** Bridged Adapter with Promiscuous Mode enabled.
* **Primary Tool:** EtherApe.

## Team Members
G Likith - 2420030056

J Hemanth - 2420039805

### Computer Networks - Section 11
