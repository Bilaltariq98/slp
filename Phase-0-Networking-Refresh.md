# (2–3 weeks)

## Why
Rusty networking can block exploit understanding. Quick refresher makes later work smoother.

## Resources

### Primary YouTube Channels
- [Practical Networking](https://www.youtube.com/watch?v=bj-Yfakjllc&list=PLIFyRwBY_4bRLmKfP1KnZA6rZbRHtxmXi) – clear, visual explainers. Best for TCP/IP, subnetting, routing.
	- [Network Devices Fundamentals 1a ](https://summarize.ing/video-73702-Network-Devices-Hosts-IP-Addresses-Networks-Networking-Fundamentals-Lesson-1a?utm_source=chatgpt.com)
	- 
- [Professor Messer Security+ (SY0-601)](https://www.professormesser.com/security-plus/sy0-601/sy0-601-training-course/) – free structured lessons covering networking fundamentals.

### Supplementary Channels
- [NetworkChuck](https://www.youtube.com/@NetworkChuck) – engaging beginner-friendly content on protocols, subnetting, VLANs.
- [David Bombal](https://www.youtube.com/@davidbombal) – networking + security context, Wireshark tutorials.
- [Sunny Classroom - Subnetting Playlist](https://www.youtube.com/watch?v=ecCuyq-Wprc) – if subnetting needs deeper focus.

### Books

#### Essential (Pick 1-2)
- **"Computer Networking: A Top-Down Approach"** by Kurose & Ross (~£40)
  - Best for beginners, application-layer down approach
  - University textbook standard, real-world examples
  - Easier to digest than Stevens

- **"TCP/IP Illustrated, Volume 1"** by Stevens & Fall (~£35)
  - Deep protocol-level understanding with network traces
  - More technical, bottom-up approach (link layer → application)
  - Industry classic for those who want mastery

- **"Practical Packet Analysis" (3rd Ed)** by Chris Sanders (~£30)
  - Hands-on Wireshark focused
  - Perfect for beginner→intermediate
  - Real-world troubleshooting scenarios
  - **Highly recommended for Phase 0-1 transition**

#### Supplementary
- **"Wireshark 101" (2nd Ed)** by Laura Chappell (~£25)
  - 46 step-by-step labs
  - Great companion to Sanders' book

- **"Network Warrior" (2nd Ed)** by Gary Donahue (~£35)
  - Cisco-centric, practical field experience
  - Good if you'll work with enterprise networks
  - Skip if focused purely on pentesting

#### Reference/Advanced (For Later)
- **"DNSSEC Mastery" (2nd Ed)** by Michael Lucas (~£30)
  - Deep dive on DNS security
  - Phase 1-2 material when studying DNS attacks

- **"Network Security Essentials"** by William Stallings (~£45)
  - Cryptography, firewalls, IDS, VPNs
  - Bridges networking → security topics

#### Budget Recommendation
**Start with:** Practical Packet Analysis (~£30) + YouTube channels = best ROI
**Add later:** Kurose & Ross if you need deeper fundamentals (~£40)

## Deliverables
- 10–12 notes on:
  - **TCP/UDP basics** – 3-way handshake, ports, connections
  - **HTTP/HTTPS deep dive** – Request/response cycle, headers, methods, status codes
  - **DNS** – Resolution process, records (A, AAAA, MX, TXT, CNAME)
  - **TLS/SSL** – Handshake, certificates, encryption basics
  - **Routing & subnets** – CIDR notation, subnet masks, calculation practice
  - **Common ports** – 21, 22, 23, 25, 53, 80, 443, 3389, 3306, 5432
  - **OSI model** – Conceptual understanding for troubleshooting
  - **ARP & MAC addressing** – Local network communication
  - **Proxies & VPNs** – Traffic redirection (context for Burp Suite later)
  - **NAT/PAT** – Internal vs external addressing
  - **Packet analysis basics** – Reading Wireshark captures
  - **Web authentication mechanisms** – Cookies, sessions, tokens
  - **"What a web exploit looks like on the wire"** – End-to-end attack flow

## Checklist

### Core Networking Concepts
- [ ] Watch TCP/UDP refresher (3-way handshake, ports, connections)
- [ ] Watch HTTP/HTTPS protocol explanation (methods, headers, status codes)
- [ ] Watch DNS resolution process
- [ ] Watch TLS/SSL handshake and certificate basics
- [ ] Watch OSI model overview
- [ ] Study common ports cheat sheet (create flash cards)

### Subnetting & Addressing
- [ ] Watch subnetting tutorials (CIDR, subnet masks)
- [ ] Complete 5–10 subnetting calculation exercises
- [ ] Learn ARP & MAC addressing
- [ ] Understand NAT/PAT basics

### Security Context
- [ ] Learn about proxies & VPNs (how traffic redirection works)
- [ ] Study web authentication mechanisms (cookies, sessions, tokens)
- [ ] Watch Wireshark basics tutorial

### Hands-On Practice
- [ ] Set up local web server (Python `http.server` or Apache)
- [ ] Capture HTTP traffic in Wireshark from local server
- [ ] Capture HTTPS/TLS handshake in Wireshark
- [ ] Analyze phishing email headers (find a sample online)
- [ ] Draw a simple network topology diagram (home/office network)

### Final Deliverable
- [ ] Write 1-page summary: "Exploit flow on the wire" (combines all concepts