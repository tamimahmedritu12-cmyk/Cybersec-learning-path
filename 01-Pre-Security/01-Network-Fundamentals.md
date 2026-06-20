# 🌐 Network Fundamentals - TryHackMe Notes

**Path:** Pre-Security  
**Status:**  Completed  

---

## 🎯 Rooms Covered
* What is Networking?
* Intro to LAN
* OSI Model
* Packets & Frames
* Extending Your Network

---

## 🧠 Key Technical Concepts

### 1. OSI Model (Open Systems Interconnection)
The OSI model consists of **7 layers** that standardize how data is transmitted over a network:
* **Layer 7 - Application:** Interface for applications (HTTP, SMTP, FTP).
* **Layer 6 - Presentation:** Data formatting, encryption, and compression.
* **Layer 5 - Session:** Establishes and manages connections between applications.
* **Layer 4 - Transport:** Handles flow control and error checking (TCP/UDP).
* **Layer 3 - Network:** Determines the best physical path for data (Routers, IP Addresses).
* **Layer 2 - Data Link:** Prepares data for physical transmission (Switches, MAC Addresses).
* **Layer 1 - Physical:** The actual hardware/cables transmitting binary data (1s and 0s).

### 2. Packets & Frames
* **Packets:** Data broken down at Layer 3 (Network Layer) containing Source and Destination IP addresses.
* **Frames:** Packets wrapped with MAC addresses at Layer 2 (Data Link Layer) for local network delivery.

### 3. LAN vs WAN
* **LAN (Local Area Network):** A private network connecting devices in a small geographic area (e.g., home or office).
* **WAN (Wide Area Network):** Connects multiple LANs across large distances (e.g., the Internet).

---

## 🛠️ Key Takeaway for Cybersecurity
Understanding network topology and the OSI model is crucial for analyzing traffic patterns and identifying where a cyber attack (like man-in-the-middle or packet sniffing) is occurring.
