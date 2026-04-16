# Network-Packet-Analysis-using-Wireshark
Analyzed real-time network traffic using Wireshark by capturing and inspecting DNS queries, TCP handshake, and HTTP requests to understand packet-level communication.
## Project Overview
This project focuses on analyzing real-time network traffic using Wireshark. It helps in understanding how data flows across a network at the packet level.

##  Objectives
* Capture network packets
* Analyze DNS queries
* Understand TCP 3-way handshake
* Inspect HTTP requests and responses

## Concepts Covered
* Packet Structure
* DNS (Domain Name System)
* TCP Handshake (SYN, SYN-ACK, ACK)
* HTTP Protocol
* Network Traffic Analysis

# Tool Used
* Wireshark

##  Steps Performed
Step 1: Start Packet Capture
* Open Wireshark
* Select active network interface (Wi-Fi)

 Step 2: Apply Filters

#### DNS Filter

text
dns
#### TCP Filter
text
tcp
#### HTTP Filter
text
http

### Step 3: Perform Actions
* Open browser and visit websites (e.g., google.com)
* Observe generated packets

## Observations

### DNS Analysis

* Client sends DNS query to resolve domain name
* Server responds with IP address

### TCP Handshake

* SYN → SYN-ACK → ACK
* Establishes reliable connection

### HTTP Request

* Browser sends GET request
* Server responds with webpage data

---

##  Data Flow
text
Client → DNS Request → Server  
Server → DNS Response → Client  

Client → SYN → Server  
Server → SYN-ACK → Client  
Client → ACK → Server  

Client → HTTP Request → Server  
Server → HTTP Response → Client

##  Conclusion

Wireshark helps in understanding real-time packet transmission and protocol behavior, which is essential for network debugging and analysis.


## Author

* Sanjana K L
