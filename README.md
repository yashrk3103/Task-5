# Task 5 – Capture and Analyze Network Traffic Using Wireshark

## ✅ Objective
Capture live network packets on Kali Linux and identify at least 3 protocols: **DNS**, **TCP**, and **HTTP**.

---

## 🛠️ Steps Performed

1. Installed Wireshark on Kali Linux.
2. Started Wireshark with `sudo wireshark`.
3. Captured packets on the active network interface (`eth0`).
4. Generated traffic by browsing websites and running `ping` and `curl`.
5. Stopped the capture after ~1 minute.
6. Applied filters to identify DNS, TCP, and HTTP packets.
7. Saved the capture as `task5_kali_capture.pcap`.
8. Took screenshots of filtered packets.

---

## 🔎 Protocols Identified

### 1️⃣ Domain Name System (DNS)
- **Purpose:** Resolves domain names (e.g., google.com) to IP addresses.
- **Example:** Standard DNS query and response for google.com.
- ![DNS Screenshot](images/DNS.png)

---

### 2️⃣ Transmission Control Protocol (TCP)
- **Purpose:** Reliable, connection-oriented protocol for data transfer.
- **Example:** TCP handshakes (SYN, ACK) between client and server.
- ![TCP Screenshot](images/tcp.png)

---

### 3️⃣ Hypertext Transfer Protocol (HTTP)
- **Purpose:** Protocol for unencrypted web communication (port 80).
- **Example:** HTTP GET requests for web resources.
- ![HTTP Screenshot](images/http.png)

---

## 📁 Files in This Repo
- `task5_kali_capture.pcap` – Packet capture file.
- `README.md` – This report.
- `images/DNS.png` – DNS protocol screenshot.
- `images/tcp.png` – TCP protocol screenshot.
- `images/http.png` – HTTP protocol screenshot.

---

## 📝 Key Learnings
- How to capture and analyze live network traffic with Wireshark.
- How to apply filters to isolate specific protocols.
- Gained understanding of basic protocols in the TCP/IP stack.

---

## 📚 Interview Questions & Answers

1. **What is Wireshark used for?**  
   Capturing and analyzing network packets for troubleshooting or research.

2. **What is a packet?**  
   A small chunk of data transmitted over a network.

3. **How to filter packets in Wireshark?**  
   Using the display filter bar (e.g., `dns`, `http`, `tcp`).

4. **Difference between TCP and UDP?**  
   TCP is reliable and connection-oriented; UDP is faster but unreliable.

5. **What is a DNS query packet?**  
   A request from a client to a DNS server to resolve a domain name.

6. **How can packet capture help in troubleshooting?**  
   By revealing communication issues, dropped packets, or misconfigurations.

7. **What is a protocol?**  
   A set of rules for communication between devices.

8. **Can Wireshark decrypt encrypted traffic?**  
   Only if you have the necessary encryption keys; otherwise, encrypted payloads remain unreadable.

---

