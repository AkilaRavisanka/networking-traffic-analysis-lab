# Networking & Traffic Analysis Lab

## 📌 Overview

This repository documents my practical learning and hands-on exercises in computer networking and network traffic analysis.

The purpose of this project is to develop a strong understanding of how devices communicate over networks, how common protocols operate, and how network traffic can be captured and analyzed.

---

## 🎯 Objectives

- Understand fundamental networking concepts
- Learn how TCP/IP communication works
- Analyze network traffic using Wireshark
- Understand common protocols such as HTTP, DNS and TELNET
- Practice basic network troubleshooting
- Understand how network information can be used during cybersecurity investigations

---

## 🧠 Topics Covered

### TCP/IP

- IP addressing
- TCP and UDP
- Ports
- Packets
- Client-server communication
- TCP connection establishment

### HTTP / HTTPS

- HTTP requests and responses
- HTTP methods
- Headers
- Status codes
- Basic web traffic analysis

### DNS

- Domain name resolution
- DNS queries and responses
- DNS records
- DNS traffic analysis

### TELNET

- Understanding the TELNET protocol
- Client-server communication
- Network ports
- Security limitations of unencrypted protocols

### Wireshark

- Packet capture
- Packet inspection
- Protocol filtering
- Following network conversations
- Identifying source and destination addresses
- Analyzing TCP traffic

---

## 🔬 Practical Labs

### Lab 01 — TCP/IP Fundamentals

**Objective:**  
Understand how network communication occurs between hosts using TCP/IP.

**Activities:**

- Identify IP addresses
- Identify source and destination ports
- Examine TCP connections
- Understand client-server communication

**Status:** 🟡 In Progress

---

### Lab 02 — HTTP Traffic Analysis

**Objective:**  
Capture and analyze HTTP network traffic.

**Activities:**

- Generate HTTP requests
- Capture traffic using Wireshark
- Identify HTTP requests and responses
- Examine HTTP headers
- Identify source and destination information

**Status:** 🟡 In Progress

---

### Lab 03 — DNS Traffic Analysis

**Objective:**  
Understand how DNS converts domain names into IP addresses.

**Activities:**

- Generate DNS queries
- Capture DNS traffic
- Identify DNS request and response packets
- Examine queried domains
- Analyze DNS communication

**Status:** 🟡 In Progress

---

### Lab 04 — TELNET

**Objective:**  
Understand how TELNET communication works and why unencrypted protocols can present security risks.

**Activities:**

- Establish a TELNET connection in a controlled lab environment
- Observe the communication
- Analyze the packets using Wireshark
- Identify security limitations

**Status:** 🟡 In Progress

---

## 🦈 Wireshark Analysis

Wireshark is being used to inspect network packets and understand how different protocols communicate.

Example filters being studied:

```text
tcp
http
dns
telnet
ip.addr == <IP_ADDRESS>
tcp.port == <PORT>
