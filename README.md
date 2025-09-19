# OSI_TCPIP_PacketTracer
Hands-on Packet Tracer simulation exploring the OSI and TCP/IP models. Visualizes HTTP, TCP, DNS, and ARP traffic with step-by-step encapsulation and decapsulation. 

# Seeing the OSI Model Come Alive in Packet Tracer

When I first learned about the OSI and TCP/IP models, it felt like memorizing abstract layers: Application, Transport, Network, Data Link, Physical. Packet Tracer turned theory into reality, letting me watch data move through these layers.

## Why I Did This Project
I wanted to go beyond textbooks. Networking concepts like encapsulation, TCP handshakes, and DNS queries are essential for cybersecurity and cloud computing—the fields I'm building my career in. This project simulates web traffic, breaking it down layer by layer and protocol by protocol.

## Part 1: Watching HTTP Traffic in Action
Simulated a web request from a client PC to a server (`www.osi.local`) in Simulation Mode:

- **Layer 7 (Application):** HTTP requests fired off from the client.
- **Layer 4 (Transport):** TCP segments wrapped requests with port information.
- **Layer 3 (Network):** IP addresses ensured the request reached the server.
- **Layer 2 (Data Link):** MAC addresses moved frames across the LAN.
- **Layer 1 (Physical):** Bits moved across the wire.

**Key takeaway:** The OSI model is a choreography of protocols working in sync.

## Part 2: Exploring TCP, DNS, and ARP
- **DNS:** Client queries resolved `www.osi.local` to an IP address.
- **TCP Handshake:** Observed SYN → SYN/ACK → ACK establishing a reliable connection.
- **ARP:** Translated IP addresses to MAC addresses, enabling LAN delivery.

**Key takeaway:** Networking is coordination. Each protocol has a role, and without it, the system fails.

## What I Learned
- Theory is shallow until applied: Watching the handshake cemented the concept.
- Details matter: Port numbers like HTTP 80 or DNS 53 guide traffic.
- Networking is storytelling: Each packet has a source, destination, purpose, and process.

## Why This Project Belongs in My Portfolio
This project shows I can:
- Investigate protocols at every OSI layer.
- Visualize network processes step by step.
- Develop practical intuition for how data travels.

It demonstrates actionable skills in cybersecurity, cloud security, or SOC analysis, not just theoretical knowledge.

## Screenshots
See`images/` folder

## Optional: Full Report
The full assignment PDF is available in the `reports/` folder for those who want the details.

---

